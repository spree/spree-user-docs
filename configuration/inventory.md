---
title: Store Credit Categories
---

# Inventory

### [Introduction](inventory.md#introduction) <a id="introduction"></a>

The Spree store gives you a great deal of leverage in managing your business’ inventory. You can set up multiple [stock locations](inventory.md#stock-locations), each of which represents a physical location where you store your products for delivery to customers. As you add new products and make sales, [stock movements](inventory.md#stock-movements) are recorded. You can receive stock from a supplier, and even move products from one stock location to another by recording [stock transfers](inventory.md#stock-transfers). All of this helps to keep your inventorying manageable and current.

### [Stock Locations](inventory.md#stock-locations) <a id="stock-locations"></a>

To reach the Stock Locations management panel, go to your Admin Interface, click “Configuration”, then click “Stock Locations”. Your store should already have at least one default stock location. If you keep all of your inventory in one place, this may be all you need.

#### [Creating a New Stock Location](inventory.md#creating-a-new-stock-location) <a id="creating-a-new-stock-location"></a>

To add a stock location to your store, click the “New Stock Location” button.

![New Stock Location](../.gitbook/assets/image%20%288%29.png)

Here, you can input everything of relevance about your stock location: name, address, and phone are the most obvious. The three checkboxes on the right-hand side merit more explanation:

* **Active** - Denotes whether the stock location is currently in operation and serving inventory for orders.
* **Backorderable Default** - Controls whether inventory items at this location can be backordered when they run out. You can still change this on an item-by-item basis as needed.
* **Propagate All Variants** - Checking this option when you create a new stock location will loop through all of the products you already have in your store, and create an entry for each one at your new location, with a starting inventory amount of 0.

Input the values for all of the fields, and click “Create” to add your new stock location.

#### [Editing a Stock Location](inventory.md#editing-a-stock-location) <a id="editing-a-stock-location"></a>

To edit a stock location, click the “Edit” icon next to it in the Stock Locations list.

![Edit Stock Location Icon](../.gitbook/assets/image%20%28124%29.png)

Make the desired changes in the form and click “Update”.

#### [Deleting a Stock Location](inventory.md#deleting-a-stock-location) <a id="deleting-a-stock-location"></a>

To remove a stock location, click the “Delete” icon next to it in the Stock Locations list.

![Delete Stock Location Icon](../.gitbook/assets/image%20%28125%29.png)

Click “OK” to confirm the deletion.

### [Stock Movements](inventory.md#stock-movements) <a id="stock-movements"></a>

Note the “Stock Movements” link on the Stock Locations list.

![Stock Movements Link](../.gitbook/assets/image%20%28130%29.png)

Clicking this link will show you all of the stock movements that have taken place for this stock location, both positive and negative.

Stock movements are actions that happen automatically through the normal management and functioning of your store. You do not have to \(and in fact, can not\) manually manipulate them. This is just a way for you to see which things are moving in and out of a particular stock location.

### [Stock Transfers](inventory.md#stock-transfers) <a id="stock-transfers"></a>

If you have more than one stock location, your Spree store offers you a way to record the movement of inventory from one location to another: the stock transfer.

To create a new stock transfer, go to your Admin Interface, click “Configuration”, followed by “Stock Transfers”, then click the “New Stock Transfer” button.

![New Stock Transfer](../.gitbook/assets/image%20%286%29.png)

You can enter an optional Reference Number that can correlate to a PO number, a transfer request number, a tracking number, or any other identifier you wish to use.

Next, select your Source and Destination stock locations. If you are receiving stock from a supplier, check the “Receive Stock” checkbox and the “Source” drop-down box will be hidden.

Select a product variant from the “Variant” drop-down list and enter the quantity of the product being transferred. Click the “Add” button.

![Stock Transfer Readied](../.gitbook/assets/image%20%287%29.png)

{% hint style="danger" %}

The new stock transfer is readied. Once you have added all of the items you want to transfer, click the “Transfer Stock” button.

![Stock Transfer Complete](../.gitbook/assets/image%20%2812%29.png)

Now, when you look at the [Stock Movements](inventory.md#stock-movements) for each of the stock locations, you see that there are two new entries that correspond to the stock transfer, both with a system-assigned “Action” number \(actually, the ID for the stock transfer\).

![Resulting Stock Movements](../.gitbook/assets/image%20%2811%29.png)

