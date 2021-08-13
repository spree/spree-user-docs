# Searching Orders

When you click the **Orders** tab on the Admin Interface, you are instantly presented with a summary of the most recent orders your store has received.

![Initial List of Orders](../.gitbook/assets/image%20%2895%29.png)

The list shows you the following information about each order:

* **Completed At** - The date on which the user finalized their order.
* **Number** - The Spree-generated order number.
* **State** - The current state of the order. You can learn more about [order states in another guide](order-states.md).
* **Payment State** - Spree tracks the state of an order’s payment separately from the state of the order itself. As payment is received, the state of the order progresses.
* **Shipment State** - Having the Shipment State outlined separately lets you quickly see which orders are paid and need to be packed and shipped, improving your store’s workflow.
* **Customer Email** - As supplied by the customer.
* **Total** - This amount includes item totals, tax, shipping, and any promotions or adjustments made to the order.

Next to each row is an “Edit” icon. Clicking this icon allows you to [make changes to an order](editing-an-order.md).

### [Filtering Results](searching-orders.md#filtering-results) <a id="filtering-results"></a>

You may not always want to see all of the most recent orders, as is the Spree default. You might want to view only those orders that you need to pack and ship, or only those from a particular customer. Spree gives you the flexibility to quickly find the specific orders you need.

![Order Filter Options](../.gitbook/assets/image%20%2891%29.png)

You can choose one or more of the following options to narrow your order search, then click the **Filter Results** button to update the results.

#### [Date Range](searching-orders.md#date-range) <a id="date-range"></a>

You can input a **Start** and/or **Stop** date. If you enter both, the results shown will be all orders that fall on or between those dates.

If you input only a **Start** date, you will get all orders placed on or after that date.

If you input only a **Stop** date, the results will include all orders placed on or before that date.

#### [Status](searching-orders.md#status) <a id="status"></a>

You can restrict orders to only those with a particular status. Available status options include:

* **cart** - Customer has added items to a shopping cart, but has not yet checked out.
* **address** - Customer has entered the checkout process, but has not yet completed input of shipping and/or billing address\(es\).
* **delivery** - Customer has completed entry of addresses, but has not yet completed selection of delivery method\(s\).
* **payment** - Customer has entered addresses and chosen a delivery method, but still needs to enter a payment method.
* **confirm** - All required information has been entered; customer just needs to confirm the order.
* **complete** - All required information is present, customer has confirmed the order, payment has not yet been received or processed.
* **canceled** - Either customer or store admin has chosen to cancel the order.
* **awaiting return** - Customer has elected to return products, but they have not yet been received.
* **return** - A return has been processed.
* **resumed** - A formerly canceled order has been reactivated.

#### [Order Number](searching-orders.md#order-number) <a id="order-number"></a>

Spree generates a unique order number for each order when the first item is added to a shopping cart. Order numbers begin with the letter R, followed by 9 random numbers. If you are searching for a particular order, you can just input the entire order number and that order is all that will be returned.

#### [Email](searching-orders.md#email) <a id="email"></a>

At this time, the filter does not allow you to search for only part of an email address. If you want to find all orders from `jane_doe@example.com`, you will have to use the full address. Inputting only “jane\_doe” will result in a pop-up alert regarding the entry of a valid email address.

#### [Name](searching-orders.md#name) <a id="name"></a>

The **First Name Begins With** and **Last Name Begins With** fields let you filter order results by name, based on the _billing address_ not on the shipping address. You can use any number of letters, from just an initial to the full first and/or last name.

#### [Complete](searching-orders.md#complete) <a id="complete"></a>

By default, the filter restricts results to only orders that have reached the `complete` order state. To remove this restriction, uncheck the box that is marked **Only Show Complete Orders**.

#### [Unfulfilled](searching-orders.md#unfulfilled) <a id="unfulfilled"></a>

If you only want to review orders that have not been shipped, you can check the box marked **Show Only Unfulfilled Orders**.

