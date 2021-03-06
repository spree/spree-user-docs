# Payment States

### [Introduction](payment-states.md#introduction) <a id="introduction"></a>

When an order is initiated for a customer purchase, a payment is created in the Spree system. The payment goes through various states while being processed.

### [Payment States](payment-states.md#payment-states) <a id="payment-states"></a>

The possible payment states are:

* **Checkout** - The checkout has not been completed.
* **Processing** - The payment is being processed.
* **Pending** - The payment has been processed but is not yet complete \(eg. authorized but not captured\).
* **Failed** - The payment was rejected \(eg. credit card was declined\).
* **Void** - The payment should not be applied to the order.
* **Completed** - The payment is completed. Only payments in this state count against the order total.

Payment does not necessarily go through each of these states in sequential order as illustrated below:

![](../.gitbook/assets/payment_flow.jpg)

You can determine the payment state for a particular order by going to the Admin Interface and clicking on the “Orders” tab. Find the order you want to look up and click on it. Then click on the “Payments” link.



![](../.gitbook/assets/zrzut-ekranu-2021-08-19-135155.jpg)

The details for the payment will appear. The “Payment State” column will display one of the possible payment states listed above.

### [Authorize vs Capture](payment-states.md#authorize-vs-capture) <a id="authorize-vs-capture"></a>

Authorizing a payment is the process of confirming the availability of funds for a transaction with the purchaser’s credit card company. Capturing a payment is the process of telling the credit card company that you would like to get paid for the transaction amount. Typically, this two-step process of first authorizing the payment and then capturing the payment is used by online retailers to delay charging the customer until the product\(s\) purchased have been fulfilled \(shipped\).

By default, Spree automatically handles authorizing the payment for a transaction. For capturing payments, we give you the choice of auto-capturing the payment or manually capturing the payment via the Admin Interface. If you like, you can read further [documentation about auto-capturing payments](https://guides.spreecommerce.org/developer/internals/payments.html#auto-capturing).

Note: Not all payment gateways allow for the two-step _authorize and then capture_ payment process. If this functionality is required for your store, please confirm with your payment gateway that they can support this process.

## [Capture a Payment via the Admin](payment-states.md#capture-a-payment-via-the-admin) <a id="capture-a-payment-via-the-admin"></a>

To capture a payment using the Admin Interface, click on the “Orders” tab. Find the order you want to look up and click on it. Then click on the “Payments” link. The order details will appear. Click on the “Capture” icon to initiate the capture process.



![Capture a Payment](https://guides.spreecommerce.org/static/2eb05af81064fdab91c0866dc6428e86/71af9/payment_capture.jpg)

### [Void a Payment](payment-states.md#void-a-payment) <a id="void-a-payment"></a>

To void a payment, go to the Admin Interface and click on the “Orders” tab. Find the order you want to look up and click on it. Then click on the “Payments” link. The order details will appear. Click on the “Void” icon to void the transaction.



![Void a Payment](https://guides.spreecommerce.org/static/928565dcd581c00feeb1a82213d4d2ed/a6e4d/payment_void.jpg)

### [Edit the Payment Amount](payment-states.md#edit-the-payment-amount) <a id="edit-the-payment-amount"></a>

Additionally, before accepting or voiding the payment you can edit the amount by clicking the “Edit” button.



![Edit button](https://guides.spreecommerce.org/static/ebc801987172847707553e402fa5bf98/9eded/payment_edit_button.jpg)

