# Prototypes

### [Introduction](prototypes.md#introduction) <a id="introduction"></a>

A Prototype is like a Product blueprint; it’s useful for helping you add a group of similar new products to your store more quickly. The general procedure is that you create a Prototype which is associated with certain [Option Types](product-options.md) and [Properties](product-properties.md); you then create products based on that Prototype, and only need to fill in the values for those Option Types and Properties.

Imagine that you’ve just received a new shipment of picture frames from your supplier. Your new stock encompasses a variety of brands, sizes, colors, and materials, but they are all basically the same type of product. This is a prime use case for prototypes.

This guide presumes you have already created the [Option Types](product-options.md) and [Properties](product-properties.md) you need for your new prototype. If you haven’t, you should do that first before proceeding.

#### [Creating a Prototype](prototypes.md#creating-a-prototype) <a id="creating-a-prototype"></a>

To create a prototype, go to the Admin Interface and click “Products”, then “Prototypes”. Click the “New Prototype” button.

![New Prototype Form](../.gitbook/assets/image%20%28100%29.png)

Input a value for the “Name” field \(such as “Picture Frames”\), and choose the properties and options you want to associate with this type of product.

![Filled-In Prototype Form](../.gitbook/assets/image%20%2880%29.png)

Click the “Create” button. You should now see your new prototype in the “Prototypes” list.

![Prototypes List](../.gitbook/assets/image%20%2884%29.png)

## [Using a Prototype to Create Products](prototypes.md#using-a-prototype-to-create-products) <a id="using-a-prototype-to-create-products"></a>

To create a new product based on the new prototype, click “Products” from the Admin Interface, then click the “New Product” button. Select “Picture Frames” from the “Prototypes” drop-down menu.

![Product From Prototype](../.gitbook/assets/image%20%28105%29.png)

When you do so, the Spree system shows you values for both of the Option Types you entered, so that it can automatically create [Product Variants](creating-a-new-product.md#understanding-variants) for each of them.

Let’s create the Product and all Variants for the fictional “Hinkledink Picture Frame” product. Input the product’s Name, SKU, and Master Price \(remember, you can change this for each variant\). Make sure to set the Available On date to today so it will show up in your store. Check the boxes for the options this particular product has and click “Create”.

Clicking the box next to an Option Type title will automatically check all of its Option Values for you.

![Prototype Option Types](../.gitbook/assets/image2%20%281%29.png)

Proceed with [creating the product](creating-a-new-product.md) as you would normally, adding any missing fields not supplied by the prototype.

Be sure to update each of the Variants with corresponding images, SKUs, and correct pricing, if applicable.[  
](https://github.com/spree/spree/edit/master/guides/src/content/user/products/product_prototypes.md)

