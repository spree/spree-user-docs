---
title: Roles
---

# Taxes

### Introduction <a id="introduction"></a>

As you undoubtedly already know, it can be challenging to manage taxation settings in an e-commerce store—particularly when you sell a variety of types of goods. The Spree shopping cart system gives you simple yet effective tools to manage taxes with ease.

There are a few concepts you need to understand in order to configure your site adequately:

* [Tax Categories](https://guides.spreecommerce.org/user/configuration/configuring_taxes.html#tax-categories)
* [Zones](https://guides.spreecommerce.org/user/configuration/configuring_taxes.html#zones)
* [Tax Rates](https://guides.spreecommerce.org/user/configuration/configuring_taxes.html#tax-rates)
* [Tax Settings](https://guides.spreecommerce.org/user/configuration/configuring_taxes.html#tax-settings)

### Tax Categories <a id="tax-categories"></a>

Tax Categories is Spree’s way of grouping products that are taxed in the same way. This is a behind-the-scenes functionality; the customer never sees the category a product is in. They only see the amount they will be charged based on their order’s delivery address.

To access your store’s existing Tax Categories, go to your Admin Interface and click “Configuration” then “Tax Categories”.

![Tax Categories](https://guides.spreecommerce.org/static/31df4b8645d1fb2f59bc181e00146ef2/a56d7/tax_categories.jpg)Tax Categories

You can edit existing Tax Categories by clicking the “Edit” icon next to each category in the list.

![Edit Tax Category Link](https://guides.spreecommerce.org/static/9f79bec2cff00d03fe9dd76ba6f5fee8/096b1/edit_tax_category_link.jpg)Edit Tax Category Link

You can also remove a Tax Category by clicking the “Delete” icon next to the category, then clicking “OK” to confirm.

![Delete Tax Category Link](https://guides.spreecommerce.org/static/47bdca6c5c471fa9fda02f91f72dd44c/253f8/delete_tax_category_link.jpg)Delete Tax Category Link

To create a new Tax Category, click the “New Tax Category” button.

![New Tax Category Form](https://guides.spreecommerce.org/static/ac13af987f6b1ea103c2bacd493a7794/d2252/new_tax_category_form.jpg)New Tax Category Form

You supply a name, an optional description, and whether or not this is the default tax category for this store.

Each product in your store will need a tax category assigned to it in order to accurately calculate the tax payable on an order. Any product that does not have a tax category assigned will automatically be assigned the default tax category. If there is no default tax category set, the item will be treated as non-taxable.

### Zones <a id="zones"></a>

In addition to a product’s tax category, the zone that an order is being shipped to will play a role in determining the tax amount. You can read more about how zones work in the [Zones guide](https://guides.spreecommerce.org/user/shipments/zones.html).

### Tax Rates <a id="tax-rates"></a>

Tax rates are how it all comes together. A product with a given [Tax Category](https://guides.spreecommerce.org/user/configuration/configuring_taxes.html#tax-categories), being shipped to a particular [Zone](https://guides.spreecommerce.org/user/configuration/configuring_taxes.html#zones), will accrue tax charges based on the relevant tax rate that you create.

To add a new Tax Rate, go to your Admin Interface and click “Configuration” then “Tax Rates”.

![Tax Rates](https://guides.spreecommerce.org/static/a65099af6798d906a59cdb56330aa2ee/baf3d/tax_rates.jpg)Tax Rates

Here, you can see all of your existing tax rates and how they are configured. To create a new tax rate, click the “New Tax Rate” button.

![New Tax Rate](https://guides.spreecommerce.org/static/a9f6544772d72a09bdb55c49b8f2c173/1060f/new_tax_rate.jpg)New Tax Rate

* **Name** - Give your new tax rate a meaningful name \(like “Taxable US Goods”, for example\)
* **Zone** - You’ll need to make separate tax rates for each zone you serve, per category. Suppose you have a “Clothing” tax category, and you sell to both the US and Europe; you’ll need to make two different tax rates, one for the US zone, and one for the European zone.
* **Rate** - The actual percentage amount you are charging. 8% would be expressed as .08 in this field.
* **Tax Category** - The [tax category](https://guides.spreecommerce.org/user/configuration/configuring_taxes.html#tax-categories) that relates to this tax rate.
* **Included in Price** - Check this box if you have already added the cost of tax into the price of the items.
* **Show Rate in Label** - When this box is checked, order summaries will include the tax rate, not just the tax amount.
* **Calculator** - By default, Spree uses the Default Tax calculator \(the calculation being the simple tax rate multiplied by item price, with adjustments made for any promotions\) to determine tax. If you need something more specific or customized than this, you can work with your development team to make it happen.

### Tax Settings <a id="tax-settings"></a>

Finally, European stores will benefit from the Tax Settings page.

![Tax Settings](https://guides.spreecommerce.org/static/d3c6c0235543052c3ffb8dc29fac3cfd/fabf6/tax_settings.jpg)Tax Settings

When this option is checked, your Spree site will take it as a default [tax category](https://guides.spreecommerce.org/user/configuration/configuring_taxes.html#tax-categories), find the corresponding [tax rate](https://guides.spreecommerce.org/user/configuration/configuring_taxes.html#tax-rates), and multiply it by the shipping rate for each available [shipping method](https://guides.spreecommerce.org/user/shipments/shipping_methods.html) offered to a customer during checkout.

