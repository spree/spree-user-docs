# Prototypes

### [Introduction](prototypes.md#introduction) <a id="introduction"></a>

A Prototype is like a Product blueprint; it’s useful for helping you add a group of similar new products to your store more quickly. The general procedure is that you create a Prototype which is associated with certain [Option Types](product-options.md) and [Properties](product-properties.md); you then create products based on that Prototype, and only need to fill in the values for those Option Types and Properties.

Imagine that you’ve just received a new shipment of picture frames from your supplier. Your new stock encompasses a variety of brands, sizes, colors, and materials, but they are all basically the same type of product. This is a prime use case for prototypes.

This guide presumes you have already created the [Option Types](product-options.md) and [Properties](product-properties.md) you need for your new prototype. If you haven’t, you should do that first before proceeding.

#### [Creating a Prototype](prototypes.md#creating-a-prototype) <a id="creating-a-prototype"></a>

To create a prototype, go to the Admin Interface and click “Products”, then “Prototypes”. Click the “New Prototype” button.

![New Prototype Form](https://guides.spreecommerce.org/static/ab80a76c2319d4d758330fb459a478f8/03ffe/new_prototype.jpg)New Prototype Form

Input a value for the “Name” field \(such as “Picture Frames”\), and choose the properties and options you want to associate with this type of product.

![Filled-In Prototype Form](https://guides.spreecommerce.org/static/9674b69afc15a805e242a2418460db08/03ffe/picture_frame_prototype.jpg)Filled-In Prototype Form

Click the “Create” button. You should now see your new prototype in the “Prototypes” list.

![Prototypes List](https://guides.spreecommerce.org/static/0a2d966865e042eb3b5f200175e51e9f/b9b0e/prototypes.jpg)Prototypes List

## [Using a Prototype to Create Products](prototypes.md#using-a-prototype-to-create-products) <a id="using-a-prototype-to-create-products"></a>

To create a new product based on the new prototype, click “Products” from the Admin Interface, then click the “New Product” button. Select “Picture Frames” from the “Prototypes” drop-down menu.

![Product From Prototype](https://guides.spreecommerce.org/static/e5388425368959d48b6ef7641d9ddb99/03ffe/product_from_prototype.jpg)Product From Prototype

When you do so, the Spree system shows you values for both of the Option Types you entered, so that it can automatically create [Product Variants](https://guides.spreecommerce.org/user/products/creating_products.html#understanding-variants) for each of them.

Let’s create the Product and all Variants for the fictional “Hinkledink Picture Frame” product. Input the product’s Name, SKU, and Master Price \(remember, you can change this for each variant\). Make sure to set the Available On date to today so it will show up in your store. Check the boxes for the options this particular product has and click “Create”.

Clicking the box next to an Option Type title will automatically check all of its Option Values for you.

![Prototype Option Types](https://guides.spreecommerce.org/static/f786408fa0d2258b75fb4740dcc45bd2/03ffe/prototype_product_with_options.jpg)Prototype Option Types

Proceed with [creating the product](https://guides.spreecommerce.org/user/products/creating_products.html) as you would normally, adding any missing fields not supplied by the prototype.

Be sure to update each of the Variants with corresponding images, SKUs, and correct pricing, if applicable.[  
](https://github.com/spree/spree/edit/master/guides/src/content/user/products/product_prototypes.md)

