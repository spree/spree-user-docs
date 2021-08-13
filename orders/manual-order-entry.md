# Manual Order Entry

### [Introduction](manual-order-entry.md#introduction) <a id="introduction"></a>

An order can be created in one of two ways:

1. An order is generated when a customer purchases an item from your store.
2. An order can be created manually in your store’s Admin panel

This guide covers how to create a manual order in the Admin Panel.

### [Add Products](manual-order-entry.md#add-products) <a id="add-products"></a>

To create a new order manually, go into the Admin Interface, click the “Orders” tab and then click the “New Order” button.

![Create New Order](https://guides.spreecommerce.org/static/f309c8d704daef125f5662312282588c/03ffe/create_new_order.jpg)Create New Order

Type the name of the product you would like to add to the order in the search field. A list of matching product and variant combinations will show up in the drop-down menu. Select the product/variant option you want to add to the order.

![Create New Order](https://guides.spreecommerce.org/static/7a05bc88eb944431fc4cb6a0ae985cba/03ffe/order_product_search.jpg)Create New Order

The interface will show you how many of that product/variant you currently have “on hand”. Enter the quantity to add to the new order, and click the “Add” icon next to the item.

![Product Added to Order](https://guides.spreecommerce.org/static/6cd964ee442aa3e027b97cbf44992adc/03ffe/order_product_added.jpg)Product Added to Order

The system creates the order and shows you the line items in it.

![Manual Order With Product](https://guides.spreecommerce.org/static/6660a12d9e0a580d22fdf6abe43dd539/03ffe/manual_order_with_product.jpg)Manual Order With Product

Follow the same steps to add more products to the order.

### [Customer Details](manual-order-entry.md#customer-details) <a id="customer-details"></a>

Click the “Customer” link. You can either select a name from the “Customer Search” field if the customer has ordered from you before, or you can enter the customer’s email address in the “Email” field of the “Account” section. The setting for “Guest Checkout” will automatically change accordingly.

Enter the customer’s billing address and the shipping address for the order. You can click “USE BILLING ADDRESS” checkbox to use the same address for both. If you do so, the shipping address fields will become invisible.

![Enter Customer Details](https://guides.spreecommerce.org/static/7a04cb15d5b0e2e1974c2e6b63db3c32/03ffe/order_customer_details.jpg)Enter Customer Details

Click the “Update” button.

### [Shipments](manual-order-entry.md#shipments) <a id="shipments"></a>

After you input the customer information, you might want to choose a shipping method. When you press the “Update” button, the page will reload in the “Shipments” tab.

The default shipping method for your store \(if you have one\) should already be assigned to this order. Depending on the items you added and the location you’re shipping to, there may be additional methods available. You might also have shipping methods that are only available for your site’s administrator to assign \(in-store pickup, for example\).

Click the “Edit” link next to the order’s shipping line.

![Edit Order Shipping Info](https://guides.spreecommerce.org/static/6b04be3f5b3103d155fb489dadf74059/03ffe/edit_shipping_on_order_link.jpg)Edit Order Shipping Info

Click the “Shipping Method” drop-down menu, and make your selection.

![Edit Shipping Options](https://guides.spreecommerce.org/static/95a994f0c54b2632acd00a0107b86e43/03ffe/edit_shipping_options.jpg)Edit Shipping Options

Click the “Save” icon to confirm your change. Your Spree site will re-calculate the shipping, any relevant adjustments, and the total for your order.

### [Adjustments](manual-order-entry.md#adjustments) <a id="adjustments"></a>

The Spree shopping cart will automatically add the cost of the Shipping Method to your order as an adjustment. You can change or remove this.

#### [Editing Adjustments](manual-order-entry.md#editing-adjustments) <a id="editing-adjustments"></a>

To edit an existing order adjustment, just click the “Adjustments” link in the order summary, then click the “Edit” icon next to the adjustment in the Adjustments list.

![Edit Adjustment Icon](https://guides.spreecommerce.org/static/db8e7896225d614987a58fb3811c22d6/71af9/edit_adjustment_icon.jpg)Edit Adjustment Icon

#### [Deleting Adjustments](manual-order-entry.md#deleting-adjustments) <a id="deleting-adjustments"></a>

To remove an adjustment, click the “Delete” icon next to it in the Adjustments list.

![Delete Adjustment Icon](https://guides.spreecommerce.org/static/a74c3d03f58830743c3784cfb0da584e/71af9/delete_adjustment_icon.jpg)Delete Adjustment Icon

Confirm the deletion by clicking “OK”.

#### [Opening and Closing Adjustments](manual-order-entry.md#opening-and-closing-adjustments) <a id="opening-and-closing-adjustments"></a>

Some types of adjustments - such as tax and shipping - may re-calculate as the order changes; for example, as new products are added to it. If you want to be sure that the amount of an adjustment will remain the same, you can lock them. This is also known as closing the adjustments.

Closed adjustments can be re-opened and changed up to the moment when the order is shipped. At that point, the adjustment is finalized and cannot be changed.

To open or close all of the adjustments in an order, just click the “Open All Adjustments” or “Close All Adjustments” buttons on the Adjustments list.

![Mass Open and Close Adjustments](https://guides.spreecommerce.org/static/f80e0849787b3f9bebd47a80d3fba0f9/71af9/mass_open_close_adjustments.jpg)Mass Open and Close Adjustments

#### [Adding Adjustments](manual-order-entry.md#adding-adjustments) <a id="adding-adjustments"></a>

You can also add further adjustments - positive or negative - to the order to account for things like handling charges, store credits, etc. To add a new adjustment, click the “New Adjustment” button.

![New Adjustment Button](https://guides.spreecommerce.org/static/0bfac0560189f3121e7e064622fb50b2/03ffe/new_adjustment_button.jpg)New Adjustment Button

You need only enter the “Amount” \(positive for a charge on the order; negative for credit\) and a “Description”, then click the “Continue” button.

![New Adjustment Form](https://guides.spreecommerce.org/static/90863b2cc4b21cd2faabb30da7ed7af8/03ffe/new_adjustment_form.jpg)New Adjustment Form

For a better understanding of adjustments, please read the [Developer Adjustments Guide](https://guides.spreecommerce.org/developer/internals/adjustments.html).

Once you have finished all of the changes you want in the order’s Adjustments, click “Continue”.

### [Payments](manual-order-entry.md#payments) <a id="payments"></a>

If you are manually entering this order, it is presumed that you have received payment either in person, on the phone, or through some other non-website means. You can manually enter payments using any of your site’s configured [payment methods](https://guides.spreecommerce.org/user/payments/payment_methods.html).

Just click the “Payments” link in the right panel section.

![Payments Link](https://guides.spreecommerce.org/static/305dbb4a47d8de5d83cdd058d5a02758/03ffe/payments_link.jpg)Payments Link

This form is pretty self-explanatory; you enter the amount of the payment, the method, and the credit card information \(if applicable\).

One thing to note is that you can enter multiple payments on the same order. This is useful if, for example, a customer wants to pay part of their order in cash and put the rest on a credit card. In that case, all you have to do is create the first payment for the cash amount, check the “Cash” payment method \(be sure that you have it configured in your store first!\), and click “Update”.

Then, click the “New Payment” link to enter the information for the credit card portion of the payment.

![New Payment Method Link](https://guides.spreecommerce.org/static/f3b0f5bdd1e8b50163c8f92ec9a47b47/03ffe/new_payment_method_link.jpg)New Payment Method Link

Don’t forget that you will need to [capture the payment](https://guides.spreecommerce.org/user/payments/payment_states.html#authorize-vs-capture) on the credit card \(unless your store is set up to automatically authorize and capture payments\).

For more on payments, be sure to read both the [Payment Methods](https://guides.spreecommerce.org/user/payments/payment_methods.html) and [Payment States](https://guides.spreecommerce.org/user/payments/payment_states.html) guides.

