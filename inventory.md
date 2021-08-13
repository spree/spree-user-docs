---
title: Store Credit Categories
---

# Inventory

### [Introduction](https://guides.spreecommerce.org/user/configuration/configuring_inventory.html#introduction) <a id="introduction"></a>

The Spree store gives you a great deal of leverage in managing your business’ inventory. You can set up multiple [stock locations](https://guides.spreecommerce.org/user/configuration/configuring_inventory.html#stock-locations), each of which represents a physical location where you store your products for delivery to customers. As you add new products and make sales, [stock movements](https://guides.spreecommerce.org/user/configuration/configuring_inventory.html#stock-movements) are recorded. You can receive stock from a supplier, and even move products from one stock location to another by recording [stock transfers](https://guides.spreecommerce.org/user/configuration/configuring_inventory.html#stock-transfers). All of this helps to keep your inventorying manageable and current.

### [Stock Locations](https://guides.spreecommerce.org/user/configuration/configuring_inventory.html#stock-locations) <a id="stock-locations"></a>

To reach the Stock Locations management panel, go to your Admin Interface, click “Configuration”, then click “Stock Locations”. Your store should already have at least one default stock location. If you keep all of your inventory in one place, this may be all you need.

#### [Creating a New Stock Location](https://guides.spreecommerce.org/user/configuration/configuring_inventory.html#creating-a-new-stock-location) <a id="creating-a-new-stock-location"></a>

To add a stock location to your store, click the “New Stock Location” button.

![New Stock Location](https://guides.spreecommerce.org/static/b2fdd33a18582178058803c87a6ada4f/03ffe/new_stock_location.jpg)New Stock Location

Here, you can input everything of relevance about your stock location: name, address, and phone are the most obvious. The three checkboxes on the right-hand side merit more explanation:

* **Active** - Denotes whether the stock location is currently in operation and serving inventory for orders.
* **Backorderable Default** - Controls whether inventory items at this location can be backordered when they run out. You can still change this on an item-by-item basis as needed.
* **Propagate All Variants** - Checking this option when you create a new stock location will loop through all of the products you already have in your store, and create an entry for each one at your new location, with a starting inventory amount of 0.

Input the values for all of the fields, and click “Create” to add your new stock location.

#### [Editing a Stock Location](https://guides.spreecommerce.org/user/configuration/configuring_inventory.html#editing-a-stock-location) <a id="editing-a-stock-location"></a>

To edit a stock location, click the “Edit” icon next to it in the Stock Locations list.

![Edit Stock Location Icon](https://guides.spreecommerce.org/static/22ff24b26901e04c9f87ff40b6730bbd/eef13/edit_stock_location_icon.jpg)Edit Stock Location Icon

Make the desired changes in the form and click “Update”.

#### [Deleting a Stock Location](https://guides.spreecommerce.org/user/configuration/configuring_inventory.html#deleting-a-stock-location) <a id="deleting-a-stock-location"></a>

To remove a stock location, click the “Delete” icon next to it in the Stock Locations list.

![Delete Stock Location Icon](https://guides.spreecommerce.org/static/858458dac7d6aae12bba77851e609f0f/07a40/delete_stock_location_icon.jpg)Delete Stock Location Icon

Click “OK” to confirm the deletion.

### [Stock Movements](https://guides.spreecommerce.org/user/configuration/configuring_inventory.html#stock-movements) <a id="stock-movements"></a>

Note the “Stock Movements” link on the Stock Locations list.

![Stock Movements Link](https://guides.spreecommerce.org/static/9c6f66ae468eb4c7fde0741744e9c4b4/7d1e4/stock_movements_link.jpg)Stock Movements Link

Clicking this link will show you all of the stock movements that have taken place for this stock location, both positive and negative.

Stock movements are actions that happen automatically through the normal management and functioning of your store. You do not have to \(and in fact, can not\) manually manipulate them. This is just a way for you to see which things are moving in and out of a particular stock location.

### [Stock Transfers](https://guides.spreecommerce.org/user/configuration/configuring_inventory.html#stock-transfers) <a id="stock-transfers"></a>

If you have more than one stock location, your Spree store offers you a way to record the movement of inventory from one location to another: the stock transfer.

To create a new stock transfer, go to your Admin Interface, click “Configuration”, followed by “Stock Transfers”, then click the “New Stock Transfer” button.

![New Stock Transfer](https://guides.spreecommerce.org/static/f346f5d5ee5856ce9b0226741d7a5917/33bac/new_stock_transfer.jpg)New Stock Transfer

You can enter an optional Reference Number that can correlate to a PO number, a transfer request number, a tracking number, or any other identifier you wish to use.

Next, select your Source and Destination stock locations. If you are receiving stock from a supplier, check the “Receive Stock” checkbox and the “Source” drop-down box will be hidden.

Select a product variant from the “Variant” drop-down list and enter the quantity of the product being transferred. Click the “Add” button.

![Stock Transfer Readied](https://guides.spreecommerce.org/static/6b4623fa389f7052f6629327939d4c3a/03ffe/stock_transfer.jpg)Stock Transfer Readied

If you try to transfer an item that you do not have in stock at your Source location, the Spree system will record a stock transfer with a quantity of 0.

The new stock transfer is readied. Once you have added all of the items you want to transfer, click the “Transfer Stock” button.

![Stock Transfer Complete](https://guides.spreecommerce.org/static/158b46fb59b204c22e438d1f932b515c/03ffe/stock_transfer_complete.jpg)Stock Transfer Complete

Now, when you look at the [Stock Movements](https://guides.spreecommerce.org/user/configuration/configuring_inventory.html#stock-movements) for each of the stock locations, you see that there are two new entries that correspond to the stock transfer, both with a system-assigned “Action” number \(actually, the ID for the stock transfer\).

![Resulting Stock Movements](https://guides.spreecommerce.org/static/696f283f40e5607d844772cac84b5467/03ffe/resulting_stock_movements.jpg)Resulting Stock Movements

