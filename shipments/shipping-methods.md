# Shipping Methods

### [Shipping Methods](https://guides.spreecommerce.org/user/shipments/shipping_methods.html#shipping-methods) <a id="shipping-methods"></a>

Now that you have set up all of the elements you need, it’s time to put them together into the shipping options that the customer sees when they reach the checkout. These options are called Shipping Methods; they are the carriers and services used to send your products.

#### [Adding a Shipping Method](https://guides.spreecommerce.org/user/shipments/shipping_methods.html#adding-a-shipping-method) <a id="adding-a-shipping-method"></a>

To add a new shipping method to your store, go to the Admin Interface and click “Configuration”, then “Shipping Methods”. Click the “New Shipping Method” button to open the New Shipping Method form.

![New Shipping Method](https://guides.spreecommerce.org/static/ed19a7a6a96722c7ca7d3aae6800eb93/03ffe/new_shipping_method.jpg)New Shipping Method

#### [Name](https://guides.spreecommerce.org/user/shipments/shipping_methods.html#name) <a id="name"></a>

Enter a name for the shipping method. This is the exact wording that the customer will see at the checkout. This should include both the carrier \(USPS, UPS, FedEx, DHL, etc.\) as well as the service type \(First Class Mail, Overnight, Ground, etc.\) It is very common to need several shipping methods for your store, for example:

* USPS First Class
* USPS First Class International
* USPS Priority
* USPS MediaMail
* UPS Two-Day
* UPS Ground
* FedEx Overnight

Remember that you will need to associate one or more [zones](https://guides.spreecommerce.org/user/shipments/shipping_methods.html#zones) with each shipping method in order for it to appear as an option at checkout.

#### [Display](https://guides.spreecommerce.org/user/shipments/shipping_methods.html#display) <a id="display"></a>

From the “Display” drop-down box, choose whether you want to have the option display only on the backend, the frontend, or both.

Shipping methods that are displayed on the frontend can be chosen by your store’s customers at checkout time, as long as the products in the order can be shipped by that carrier and the shipping address is one the carrier serves.

If a shipping method is available only on backend, then only your store’s administrators can assign it to an order. Some examples of cases where you might want to use a backend-only shipping method:

* You sell handmade wind chimes. You want to offer a “Pick-up in Store” option, but only to certain customers.
* You want to provide personal delivery of goods only to your best local customers.
* Your photography studio usually sells prints that are physically delivered; however, some clients are willing to receive electronic media that they can print themselves.

#### [Tracking URL](https://guides.spreecommerce.org/user/shipments/shipping_methods.html#tracking-url) <a id="tracking-url"></a>

You can optionally input a tracking URL for your new shipping method. This allows customers to track the progress of their package from your [Stock Location](https://guides.spreecommerce.org/user/configuration/configuring_inventory.html) to the order’s shipping address. The string “:tracking” will be replaced with the tracking number you input once you actually process the order.

You may need to check with the shipping carrier to see if they have a Shipping Confirmation URL that customers can use for this service. Some [commonly-used tracking URLs](http://verysimple.com/2011/07/06/ups-tracking-url/) are available online.

!!! Please note that Spree Commerce, Inc. makes no claims of warranty or accuracy for the information presented on third-party websites. We strongly urge you to verify the information independently before you put it into production on your store. !!!

#### [Categories](https://guides.spreecommerce.org/user/shipments/shipping_methods.html#categories) <a id="categories"></a>

Some shipping methods may only apply to certain types of products in your store, regardless of where those items are being shipped. You may only want to send over-sized items via UPS Ground, for example, and not via USPS Priority. The options shown in the “Categories” section correspond to the [Shipping Categories](https://guides.spreecommerce.org/user/shipments/shipping_categories.html) you set up in an earlier section of this guide series.

![Shipping Method Categories](https://guides.spreecommerce.org/static/ef22162760a3b9e5e4c483e8a939e606/03ffe/shipping_method_categories.jpg)Shipping Method Categories

Check the boxes next to the categories you want served by your new shipping method.

#### [Zones](https://guides.spreecommerce.org/user/shipments/shipping_methods.html#zones) <a id="zones"></a>

In [a previous step to this guide](https://guides.spreecommerce.org/user/shipments/zones.html) you learned how to set up geographical zones for your store. Within the “Zones” section of the form, you need to specify which zones are served by this shipping method. The “EU_VAT” \(European Value-Added Tax\) zone could be served by USPS First Class International, but could \_not_ be served by USPS Priority Mail.

![Shipping Method Zones](https://guides.spreecommerce.org/static/2d5f9458ca978c2c8291cc0dc64a5e66/03ffe/shipping_method_zones.jpg)Shipping Method Zones

Check the boxes next to any zones you want served by this shipping method.

#### [Calculator](https://guides.spreecommerce.org/user/shipments/shipping_methods.html#calculator) <a id="calculator"></a>

Each shipping method is associated with one [Calculator](https://guides.spreecommerce.org/user/shipments/calculators.html). You can choose one of the built-in Spree calculators or one you have made yourself.

![Shipping Method Calculator](https://guides.spreecommerce.org/static/edb61f90dcf5efddf16bc1e474125138/03ffe/shipping_method_calculator.jpg)Shipping Method Calculator

Once you’ve made your calculator selection, click the “Create” button to finalize your new shipping method. The screen will refresh with one or more fields which you then use to set the parameters of your calculator. For example, creating a shipping method with a flat percent calculator will produce a screen like this:

![Shipping Method Flat Percent](https://guides.spreecommerce.org/static/3ca9a7cc8da5f7fca694ab7d7ed7dac5/03ffe/shipping_method_flat_percent.jpg)Shipping Method Flat Percent

If necessary, you can re-read the [Calculators](https://guides.spreecommerce.org/user/shipments/calculators.html) portion of this guide series to better understand the options. Click the “Update” button, and your shipping method is now complete!

#### [Editing a Shipping Method](https://guides.spreecommerce.org/user/shipments/shipping_methods.html#editing-a-shipping-method) <a id="editing-a-shipping-method"></a>

To edit an existing method, go to the Admin Interface and click “Configuration”, then “Shipping Methods”. Click the “Edit” icon next to any of the shipping methods in the list.

![Edit Shipping Method](https://guides.spreecommerce.org/static/9dd36bb43270d25c8fbd8eca2394383c/3bda4/edit_shipping_method.jpg)Edit Shipping Method

The form and all options that come up are the same as those you used in creating your shipping methods.

#### [Deleting a Shipping Method](https://guides.spreecommerce.org/user/shipments/shipping_methods.html#deleting-a-shipping-method) <a id="deleting-a-shipping-method"></a>

To delete a shipping method, go to the Admin Interface and click “Configuration”, then “Shipping Methods”. Click the “Delete” icon next to any of the shipping methods in the list.

![Delete Shipping Method](https://guides.spreecommerce.org/static/4e27664d84194452406c88188cd14dd9/3bda4/delete_shipping_method.jpg)Delete Shipping Method

Confirm that you want to delete the shipping method by clicking “OK”.

