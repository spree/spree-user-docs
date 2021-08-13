---
title: Roles
---

# Taxes

### [Introduction](taxes.md#introduction) <a id="introduction"></a>

As you undoubtedly already know, it can be challenging to manage taxation settings in an e-commerce store—particularly when you sell a variety of types of goods. The Spree shopping cart system gives you simple yet effective tools to manage taxes with ease.

There are a few concepts you need to understand in order to configure your site adequately:

* [Tax Categories](taxes.md#tax-categories)
* [Zones](taxes.md#zones)
* [Tax Rates](taxes.md#tax-rates)
* [Tax Settings](taxes.md#tax-settings)

### [Tax Categories](taxes.md#tax-categories) <a id="tax-categories"></a>

Tax Categories is Spree’s way of grouping products that are taxed in the same way. This is a behind-the-scenes functionality; the customer never sees the category a product is in. They only see the amount they will be charged based on their order’s delivery address.

To access your store’s existing Tax Categories, go to your Admin Interface and click “Configuration” then “Tax Categories”.

![Tax Categories](../.gitbook/assets/image%20%2818%29.png)

You can edit existing Tax Categories by clicking the “Edit” icon next to each category in the list.

![Edit Tax Category Link](../.gitbook/assets/image%20%2814%29.png)

You can also remove a Tax Category by clicking the “Delete” icon next to the category, then clicking “OK” to confirm.

![Delete Tax Category Link](../.gitbook/assets/image%20%2817%29.png)

To create a new Tax Category, click the “New Tax Category” button.

![New Tax Category Form](../.gitbook/assets/image%20%2816%29.png)

You supply a name, an optional description, and whether or not this is the default tax category for this store.

Each product in your store will need a tax category assigned to it in order to accurately calculate the tax payable on an order. Any product that does not have a tax category assigned will automatically be assigned the default tax category. If there is no default tax category set, the item will be treated as non-taxable.

### [Zones](taxes.md#zones) <a id="zones"></a>

In addition to a product’s tax category, the zone that an order is being shipped to will play a role in determining the tax amount. You can read more about how zones work in the [Zones guide](../shipments/zones.md).

### [Tax Rates](taxes.md#tax-rates) <a id="tax-rates"></a>

Tax rates are how it all comes together. A product with a given [Tax Category](taxes.md#tax-categories), being shipped to a particular [Zone](taxes.md#zones), will accrue tax charges based on the relevant tax rate that you create.

To add a new Tax Rate, go to your Admin Interface and click “Configuration” then “Tax Rates”.

![Tax Rates](../.gitbook/assets/image%20%2810%29.png)

Here, you can see all of your existing tax rates and how they are configured. To create a new tax rate, click the “New Tax Rate” button.

![New Tax Rate](../.gitbook/assets/image%20%289%29.png)

* **Name** - Give your new tax rate a meaningful name \(like “Taxable US Goods”, for example\)
* **Zone** - You’ll need to make separate tax rates for each zone you serve, per category. Suppose you have a “Clothing” tax category, and you sell to both the US and Europe; you’ll need to make two different tax rates, one for the US zone, and one for the European zone.
* **Rate** - The actual percentage amount you are charging. 8% would be expressed as .08 in this field.
* **Tax Category** - The [tax category](taxes.md#tax-categories) that relates to this tax rate.
* **Included in Price** - Check this box if you have already added the cost of tax into the price of the items.
* **Show Rate in Label** - When this box is checked, order summaries will include the tax rate, not just the tax amount.
* **Calculator** - By default, Spree uses the Default Tax calculator \(the calculation being the simple tax rate multiplied by item price, with adjustments made for any promotions\) to determine tax. If you need something more specific or customized than this, you can work with your development team to make it happen.

### [Tax Settings](taxes.md#tax-settings) <a id="tax-settings"></a>

Finally, European stores will benefit from the Tax Settings page.

![Tax Settings](../.gitbook/assets/image%20%2815%29.png)

When this option is checked, your Spree site will take it as a default [tax category](taxes.md#tax-categories), find the corresponding [tax rate](taxes.md#tax-rates), and multiply it by the shipping rate for each available [shipping method](../shipments/shipping-methods.md) offered to a customer during checkout.

