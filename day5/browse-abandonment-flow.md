The Viewed Product event has been successfully implemented and is live on the Farm2Home website.

How it works

1. When a customer views a product page, a custom Viewed Product event is sent to Klaviyo.

2. The event includes:
   - Customer email
   - Username (mapped to first_name)
   - Product ID
   - Product Name
   - Category
   - Price
   - Product Image URL(we are sending the image link using ngrok)
   - Product URL
   - Three category-based product recommendations

3. The event is used to trigger the Browse Abandonment Flow.

#### Browse Abandonment Flow Logic

Customer views a product -->Viewed Product Event-->Wait Period-->Check if customer placed an order

#### Flow Trigger Conditions

The flow is configured with:

Trigger:
Viewed Product

Profile Filter:

Placed Order zero times in the last 1 day

Re-entry:

Allow re-entry after 7 days

If a customer:

Views a product

Does not add it to cart / does not purchase

then the Browse Abandonment flow is triggered and sends:

1. Product reminder email
   - Displays the viewed product
   - Includes product image, name, description, and price
   - CTA: Add to Cart

2. Product recommendation email
   - Displays three similar products from the same category
   - Encourages the customer to continue shopping

#### Current Status

Viewed Product event triggered successfully from the website

Product details passed to Klaviyo

Username mapped to first_name

Product recommendation logic implemented

Browse Abandonment Flow configured

Reminder email created

Recommendation email created

Flow tested successfully with sample products (e.g., Onion, Mango)

This ensures that customers who browse products but leave without purchasing are automatically re-engaged with personalized product reminders and recommendations.
