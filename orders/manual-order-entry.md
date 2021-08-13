# Manual Order Entry

### [Introduction](manual-order-entry.md#introduction) <a id="introduction"></a>

An order can be created in one of two ways:

1. An order is generated when a customer purchases an item from your store.
2. An order can be created manually in your store’s Admin panel

This guide covers how to create a manual order in the Admin Panel.

### [Add Products](manual-order-entry.md#add-products) <a id="add-products"></a>

To create a new order manually, go into the Admin Interface, click the “Orders” tab and then click the “New Order” button.

![Create New Order](../.gitbook/assets/image%20%2870%29.png)

Type the name of the product you would like to add to the order in the search field. A list of matching product and variant combinations will show up in the drop-down menu. Select the product/variant option you want to add to the order.

![Create New Order](../.gitbook/assets/image%20%2873%29.png)

The interface will show you how many of that product/variant you currently have “on hand”. Enter the quantity to add to the new order, and click the “Add” icon next to the item.

![Product Added to Order](../.gitbook/assets/image%20%2867%29.png)

The system creates the order and shows you the line items in it.

![Manual Order With Product](../.gitbook/assets/image%20%2865%29.png)

Follow the same steps to add more products to the order.

### [Customer Details](manual-order-entry.md#customer-details) <a id="customer-details"></a>

Click the “Customer” link. You can either select a name from the “Customer Search” field if the customer has ordered from you before, or you can enter the customer’s email address in the “Email” field of the “Account” section. The setting for “Guest Checkout” will automatically change accordingly.

Enter the customer’s billing address and the shipping address for the order. You can click “USE BILLING ADDRESS” checkbox to use the same address for both. If you do so, the shipping address fields will become invisible.

![Enter Customer Details](../.gitbook/assets/image%20%2864%29.png)

Click the “Update” button.

### [Shipments](manual-order-entry.md#shipments) <a id="shipments"></a>

After you input the customer information, you might want to choose a shipping method. When you press the “Update” button, the page will reload in the “Shipments” tab.

The default shipping method for your store \(if you have one\) should already be assigned to this order. Depending on the items you added and the location you’re shipping to, there may be additional methods available. You might also have shipping methods that are only available for your site’s administrator to assign \(in-store pickup, for example\).

Click the “Edit” link next to the order’s shipping line.

![Edit Order Shipping Info](../.gitbook/assets/image%20%2871%29.png)

Click the “Shipping Method” drop-down menu, and make your selection.

![Edit Shipping Options](../.gitbook/assets/image%20%2872%29.png)

Click the “Save” icon to confirm your change. Your Spree site will re-calculate the shipping, any relevant adjustments, and the total for your order.

### [Adjustments](manual-order-entry.md#adjustments) <a id="adjustments"></a>

The Spree shopping cart will automatically add the cost of the Shipping Method to your order as an adjustment. You can change or remove this.

#### [Editing Adjustments](manual-order-entry.md#editing-adjustments) <a id="editing-adjustments"></a>

To edit an existing order adjustment, just click the “Adjustments” link in the order summary, then click the “Edit” icon next to the adjustment in the Adjustments list.

![Edit Adjustment Icon](../.gitbook/assets/image%20%2869%29.png)

#### [Deleting Adjustments](manual-order-entry.md#deleting-adjustments) <a id="deleting-adjustments"></a>

To remove an adjustment, click the “Delete” icon next to it in the Adjustments list.

![Delete Adjustment Icon](../.gitbook/assets/image%20%2862%29.png)

Confirm the deletion by clicking “OK”.

#### [Opening and Closing Adjustments](manual-order-entry.md#opening-and-closing-adjustments) <a id="opening-and-closing-adjustments"></a>

Some types of adjustments - such as tax and shipping - may re-calculate as the order changes; for example, as new products are added to it. If you want to be sure that the amount of an adjustment will remain the same, you can lock them. This is also known as closing the adjustments.

Closed adjustments can be re-opened and changed up to the moment when the order is shipped. At that point, the adjustment is finalized and cannot be changed.

To open or close all of the adjustments in an order, just click the “Open All Adjustments” or “Close All Adjustments” buttons on the Adjustments list.

![Mass Open and Close Adjustments](../.gitbook/assets/image%20%2868%29.png)

#### [Adding Adjustments](manual-order-entry.md#adding-adjustments) <a id="adding-adjustments"></a>

You can also add further adjustments - positive or negative - to the order to account for things like handling charges, store credits, etc. To add a new adjustment, click the “New Adjustment” button.

![New Adjustment Button](../.gitbook/assets/image%20%2861%29.png)

You need only enter the “Amount” \(positive for a charge on the order; negative for credit\) and a “Description”, then click the “Continue” button.

![New Adjustment Form](../.gitbook/assets/image%20%2863%29.png)

For a better understanding of adjustments, please read the [Developer Adjustments Guide](https://app.gitbook.com/@spark-solutions/s/spree-developer-documentation/internals/adjustments).

Once you have finished all of the changes you want in the order’s Adjustments, click “Continue”.

### [Payments](manual-order-entry.md#payments) <a id="payments"></a>

If you are manually entering this order, it is presumed that you have received payment either in person, on the phone, or through some other non-website means. You can manually enter payments using any of your site’s configured [payment methods](../payments/payment-methods.md).

Just click the “Payments” link in the right panel section.

![Payments Link](../.gitbook/assets/image%20%2874%29.png)

This form is pretty self-explanatory; you enter the amount of the payment, the method, and the credit card information \(if applicable\).

One thing to note is that you can enter multiple payments on the same order. This is useful if, for example, a customer wants to pay part of their order in cash and put the rest on a credit card. In that case, all you have to do is create the first payment for the cash amount, check the “Cash” payment method \(be sure that you have it configured in your store first!\), and click “Update”.

Then, click the “New Payment” link to enter the information for the credit card portion of the payment.

![New Payment Method Link](../.gitbook/assets/image%20%2866%29.png)

Don’t forget that you will need to [capture the payment](../payments/payment-states.md) on the credit card \(unless your store is set up to automatically authorize and capture payments\).

For more on payments, be sure to read both the [Payment Methods](../payments/payment-methods.md) and [Payment States](../payments/payment-states.md) guides.

