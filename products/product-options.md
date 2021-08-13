# Product Options

### [Option Types and Option Values](product-options.md#option-types-and-option-values) <a id="option-types-and-option-values"></a>

Option Types are a way to help distinguish products in your store from one another. They are particularly useful when you have many products that are basically of the same general category \(t-shirts or mugs, for example\) but with varying characteristics, such as color, size or logo.

For each Option Type, you will need to create one or more corresponding Option Values. If you create a “Size” Option Type, then you would need Option Values like “Small”, “Medium”, and “Large”.

#### [Creating Option Types and Option Values](product-options.md#creating-option-types-and-option-values) <a id="creating-option-types-and-option-values"></a>

Option Types and Option Values are created at the store level, not the product level. This means that you only have to create each Option Type and Option Value once. Once an Option Type and Option Value is created it can be associated with any product in your store. To create an Option Type, click “Products”, then “Option Types”, then “New Option Type”.

![New Option Type](../.gitbook/assets/image%20%2886%29.png)

You are required to fill in two fields: “Name” and “Presentation”. You will see this same pattern in several places on the Admin Interface. “Name” is generally the short term \(usually one or two words\) for the option you want to store. “Presentation” is the wordier, more descriptive term that gives your site’s visitors a little more detail.

NOTE: Sometimes the term “Display” is used instead of “Presentation” to indicate what is shown to the user on the Product Variant’s page.

For our first Option Type - Size - enter “Size” for the Name and “Size of the Tumbler” as the Presentation. Click “Update”.

When the screen refreshes, you can see that Spree has helpfully provided you with a blank row in which you can enter your first Option Value for the new Option Type.

![New Option Value](../.gitbook/assets/image%20%2887%29.png)

We’re going to need two Option Values \(Large and Small\) for the Size Option Value. Click the “Add Option Value” button which will give you two blank rows to work with.

“Name” is easy; write “Large” for the first and “Small” for the second. Let’s input “24-ounce cup” in the “Display” field for the Large Option Value and “16-ounce cup” for the Small Option Value.

![Completed Option Values](../.gitbook/assets/image%20%28102%29.png)

When you click “Update”, Spree saves the two new Option Values, associates them with the Size Option Type, and takes you to the list of all Option Types.

#### [Associating Option Values with a Product](product-options.md#associating-option-values-with-a-product) <a id="associating-option-values-with-a-product"></a>

Our Spree application now knows that we have an Option Type with corresponding Option Values,but it doesn’t know which of our products should have those Option Types. We have to explicitly tell it about those associations. We can do so either when we create a new Product \(if the options have already been created\), or when we edit an existing product.

At the bottom of the Product edit form is a text box labeled “Option Types”. When you click in this box, a drop-down appears with all of the Option Types you have defined for your store. All you have to do is click one or more of them to associate them with your Product.

![Option Types Dropdown List](../.gitbook/assets/image%20%2898%29.png)

Don’t forget to click “Update” to save your changes.

