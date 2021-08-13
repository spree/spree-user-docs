# Processing Orders

### [Introduction](processing-orders.md#introduction) <a id="introduction"></a>

Once an order comes into your store - whether it is entered by a customer through the website frontend or you [manually enter it yourself](manual-order-entry.md) through the admin backend - it needs to be processed. That means these steps need to be taken:

1. Verify that the products are, in fact, in stock and shippable.
2. Process the payment\(s\) on the order.
3. Package and ship the order.
4. Record the shipment information on the order.

Steps 1 and 3 you would obviously do physically at your stocking location\(s\). This guide covers how you use your Spree store to manage steps 2 and 4.

### [Processing Payments](processing-orders.md#processing-payments) <a id="processing-payments"></a>

You have received an order in your store - hooray! Either the items are all in stock, or you have adjusted the order to include only those items you can sell to the customer.

Now you need to process the payment on the order. You know best how your store processes things like checks, money orders, and cash, so this guide will focus on processing credit card payments.

![Order to Process](../.gitbook/assets/image%20%2876%29.png)

Pictured above is an order that is ripe for processing. The current order State is “Complete”, meaning that all of the information the customer needs to provide is present. The Payment State is “Balance Due”, meaning that there is an unpaid balance on the order. The Shipment State is “Pending” because you can’t ship an order before you collect payment on it.

If you click either the Order Number or the “Edit” icon, you will open the order in Edit mode. Instead, click the “Balance Due” payment state to open the order’s payment info page.

![Payment to Process](../.gitbook/assets/image%20%2886%29.png)

As you can see above, we have only a single payment to process, for the full amount \($131.93\). Processing this payment is literally a click away; just click on the “Capture” icon next to the payment.

If the payment is processed successfully, the page will re-load, showing you that the payment state has progressed from “Pending” to “Completed”.

![Completed Payment](../.gitbook/assets/image%20%2875%29.png)

That’s all! Now you can prepare your packages for shipment, then update the order with the shipment information.

### [Processing Shipments](processing-orders.md#processing-shipments) <a id="processing-shipments"></a>

Now, when you visit the Order Summary, you can see that there is a new “Ship” button in the middle of the page.

![Ship Button](../.gitbook/assets/image%20%2878%29.png)

Clicking this button moves the Shipment State from “Ready” to “Shipped”.

![Order Marked Shipped](../.gitbook/assets/image%20%2889%29.png)

The only thing that remains to do now is to click the “Edit” icon next to the tracking details line, and provide tracking info for the package\(s\). Click the “Save” icon to record this information.

![Input Tracking Info](../.gitbook/assets/image%20%2877%29.png)

