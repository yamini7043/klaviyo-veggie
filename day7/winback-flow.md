Segments Created

1. Lapsed Regulars (High Priority)

Customers who:

Have placed 3 or more orders
Have not placed an order in the last 30 days

Purpose:
Target previously loyal customers who have stopped purchasing recently.

2. Lapsed New Customers (Medium Priority)

Customers who:

Have placed 1–2 orders
Have not placed an order in the last 45 days

Purpose:
Re-engage newer customers before they become inactive permanently.

3. Unengaged (List Hygiene Segment)

Customers who:

Have not opened any email in the last 90 days

Purpose:
Identify inactive subscribers and reduce email frequency to maintain deliverability and list quality.

Winback Flow

Flow Name: Winback Campaign

Trigger:

Segment Trigger

Lapsed Regulars/Lapsed New Customers
Combined segement is Winback audience
Customers enter the flow when they qualify for either segment.

Flow Filter

Customers exit the flow immediately if:

Placed Order at least once since starting this flow

This prevents customers from receiving winback emails after returning and making a purchase.

Post-Flow Logic

After Email 3:

If Customer Places an Order
Exit flow immediately
Return to normal customer lifecycle campaigns
If Customer Does Not Place an Order
Move customer into the Unengaged segment
Reduce marketing email frequency
Exclude from high-frequency promotional campaigns
Post-Flow Plan for Non-Converters

Customers who complete the winback flow without purchasing:

Added to the Unengaged audience
Receive fewer promotional emails
Included only in major seasonal campaigns
Monitored for future engagement
Removed from regular marketing sequences to protect deliverability and sender reputation
Current Implementation Status

Lapsed Regulars segment created

Lapsed New Customers segment created

Winback audience segment is created combining Lapsed Regulars and Lapsed New Customers

Unengaged segment created

Winback flow configured

3-email sequence planned

Exit flow filter configured for purchasers

Post-flow handling documented for non-converters
