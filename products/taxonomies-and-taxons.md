# Taxonomies and Taxons

### [Introduction](taxonomies-and-taxons.md#introduction) <a id="introduction"></a>

Taxonomies are the Spree system’s approach to category trees. The heading of a tree is called a _Taxonomy_. Any child branches are called _Taxons_. Taxons themselves can have their own branches, meaning you could have something like the following categories structure:

![Taxonomy Tree](../.gitbook/assets/image%20%2881%29.png)

In this example, “Categories” is the name of the Taxonomy. It has three child branches: “Luggage”, “Housewares”, and “Clothing”. The last two branches each have three of their own child branches. Thus, “Clothing” is a child taxon to “Categories” and a parent taxon to “Men’s”.

To reach the Taxonomies list, first go to your Admin Interface, then click “Configurations” and “Taxonomies”.

### [Create a New Taxonomy](taxonomies-and-taxons.md#create-a-new-taxonomy) <a id="create-a-new-taxonomy"></a>

To create a new taxonomy, click the “New Taxonomy” button. Enter a name for the taxonomy and click “Create”.

![New Taxonomy](https://guides.spreecommerce.org/static/a5b1c69bb496723d612224ad72ded42d/03ffe/new_taxonomy.jpg)New Taxonomy

You can then [add child taxons](taxonomies-and-taxons.md#adding-a-taxon-to-a-taxonomy) to your new taxonomy.

### [Edit a Taxonomy](taxonomies-and-taxons.md#edit-a-taxonomy) <a id="edit-a-taxonomy"></a>

To edit an existing taxonomy, click the “Edit” icon next to the name in the Taxonomies list.

![Edit Taxonomy Icon](https://guides.spreecommerce.org/static/9cb03ea7b950c1e1e65692cc64ef86ce/e24e8/edit_taxonomy_icon.jpg)Edit Taxonomy Icon

Here, you can change the name of the Taxonomy. You can also [reorder the child taxons](taxonomies-and-taxons.md#reorder-a-taxon), [delete a taxon](taxonomies-and-taxons.md#delete-a-taxon), [add a new taxon](taxonomies-and-taxons.md#adding-a-taxon-to-a-taxonomy), or [edit a taxon](taxonomies-and-taxons.md#edit-a-taxon). Make your changes, then click the Update button.

![Edit Taxonomy](https://guides.spreecommerce.org/static/7e812849c6e36548be7a24fd40845a9c/33bac/edit_taxonomy.jpg)Edit Taxonomy

### [Delete a Taxonomy](taxonomies-and-taxons.md#delete-a-taxonomy) <a id="delete-a-taxonomy"></a>

![Delete Taxonomy Icon](https://guides.spreecommerce.org/static/bb2f9a0b92aeb6ad84c96d91b78091fa/e24e8/delete_taxonomy_icon.jpg)Delete Taxonomy Icon

To delete a taxonomy, click the “Delete” icon next to the name in the Taxonomies list. Click “OK” to confirm.

### [Adding a Taxon to a Taxonomy](taxonomies-and-taxons.md#adding-a-taxon-to-a-taxonomy) <a id="adding-a-taxon-to-a-taxonomy"></a>

Once you have created a taxonomy, you may want to add child taxons to it. To do this, right-click the name of the Taxonomy, and click “Add”.

![Add Taxon to Taxonomy](https://guides.spreecommerce.org/static/2da0c21126242316ab424d4235fcc47b/ea4c8/add_taxon_to_taxonomy.jpg)Add Taxon to Taxonomy

This will cause a new input field to open up, with “New node” in it. Replace this text with the name of your new taxon, and hit Enter. You’ll now see the child tax in the taxonomy tree.

![New Taxon](https://guides.spreecommerce.org/static/218ca6d55e9da5924a9473d38f047a9a/e53e1/new_taxon.jpg)New Taxon

Click “Update” to save your addition.

### [Adding a Taxon to Another Taxon](taxonomies-and-taxons.md#adding-a-taxon-to-another-taxon) <a id="adding-a-taxon-to-another-taxon"></a>

If your site needs sub-trees, just add taxons to other taxons. To do so, right-click the name of what will become the parent taxon and then click “Add”.

![Add Taxon to Another Taxon](https://guides.spreecommerce.org/static/56f86d0c2b1553f34445b6b80907364d/50fad/add_taxon_to_taxon.jpg)Add Taxon to Another Taxon

Enter the name of the child taxon and click enter. Repeat this process for any sub-trees you need.

![Complex Taxonomy Tree](https://guides.spreecommerce.org/static/112bb731a3351045dc2fb852027096ca/fb2e4/complex_taxonomy_tree.jpg)Complex Taxonomy Tree

Remember to save your changes by clicking the “Update” button after you have added any taxons.

When you navigate away from your taxonomy's page, then navigate back to it, sub-trees will be collapsed by default. To see child taxons, just click the arrow next to the parent taxon.

### [Reorder a Taxon](taxonomies-and-taxons.md#reorder-a-taxon) <a id="reorder-a-taxon"></a>

Taxons are displayed, by default, in the order in which you add them. To reorder them, just drag and drop them to their correct location in the tree.

Let’s assume, for example, that we want the “Children’s” taxon to be listed first, above “Women’s” and “Men’s”. Just drag and drop the taxon to its new location.

![Reordering Taxons](https://guides.spreecommerce.org/static/9e55789f93b675d6f1aef37ace61ad9f/94796/reorder_taxons.jpg)Reordering Taxons

You can even drag a parent taxon into the tree of a different parent taxon, merging it into the second taxon’s sub-tree.

![Parent-to-Parent Taxon Merge](https://guides.spreecommerce.org/static/d1543035f6712a8424bd3755b825b88b/3bbd9/parent_into_parent_taxon_merge.jpg)Parent-to-Parent Taxon Merge

### [Edit a Taxon](taxonomies-and-taxons.md#edit-a-taxon) <a id="edit-a-taxon"></a>

To edit a taxon’s name, just right-click it and select “Edit”.

![Edit Taxon Form](https://guides.spreecommerce.org/static/fbfdb052f8ad12e78aa7f7315dfa4653/03ffe/edit_taxon.jpg)Edit Taxon Form

Here, you can edit several aspects of the taxon:

* **Name** - A required field for all taxons. The name determines what the user will see when they look at this product in your store.
* **Permalink** - The end of the URL a user visits in order to see all products associated with this taxon. This field is also required, and a value is automatically generated for you when you create the taxon. Be careful with arbitrarily changing the permalink; if you have two taxons with the same permalink you will run into issues.
* **Description** - A short text describing the category that will be visible above the header banner.
* **Hide from subcategories navigation checkbox** - Checking this checkbox will make the category invisible in the Subcategories navigation in the Products listing page.![Hide From Subcategories](https://guides.spreecommerce.org/static/ef9cb1706bbc2c1aef504e69dccdf1e3/03ffe/hide_from_subcategories.jpg)Hide From Subcategories
* **Header Banner** - This option lets you upload a header image for the desired category
* **Meta Title** - Overrides the store’s setting for page title when a user visits the taxon’s page on the front end of the website.
* **Meta Description** - Overrides the store’s setting for meta description when a user visits the taxon’s page on the frontend of the website.
* **Meta Keywords** - Overrides the store’s setting for meta keywords when a user visits the taxon’s page on the frontend of the website.
* **Description** - This option is currently not functional.

Remember to click “Update” after you make your changes.

### [Delete a Taxon](taxonomies-and-taxons.md#delete-a-taxon) <a id="delete-a-taxon"></a>

To delete a taxon, right-click it in the taxonomy tree and click “Remove”.

![Remove a Taxon](https://guides.spreecommerce.org/static/c10fe86e984085517bb383f4789439c7/b10e1/remove_taxon.jpg)Remove a Taxon

Press “OK” to confirm.

### [Associating Products with Taxons](taxonomies-and-taxons.md#associating-products-with-taxons) <a id="associating-products-with-taxons"></a>

To associate a product with one or more taxons, go to the Admin Interface, and click the “Products” tab. Locate the product you want to edit and click its “Edit” icon. Select the taxons for the product in the Taxons field.

![Add Taxons to a Product](https://guides.spreecommerce.org/static/5fe199e6b4e26d94a2d86eb479bb30c9/f8495/add_taxons_to_product.jpg)Add Taxons to a Product

