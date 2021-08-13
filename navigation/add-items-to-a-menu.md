# Add Items To A Menu

## Introduction <a id="introduction"></a>

This part of the guide assumes you have created a menu and are now ready to add some items to the menu items area pictured below; if this is not the case, [click here](https://app.gitbook.com/@spark-solutions/s/spree-user-documentation/creating_a_new_menu) to view the guide to creating a new menu.



![Menu Items Area](../.gitbook/assets/image%20%284%29%20%281%29.png)

To get start adding items to your menu click the Add New Menu Item button found in the top right of the Menu Item Area; once clicked, you will be taken to the New Menu Item page shown in the image below.

You will be presented with three panels, **Settings**, **Public Details** and **Link Settings**.



![New Menu Item Page](../.gitbook/assets/image%20%285%29.png)

## Settings Panel <a id="settings-panel"></a>

The Settings panel contains Menu Item specific settings, such as **Item Type**, **Code** and **Nest Under**.

### Item Type <a id="item-type"></a>

The Item Type selector allows you to set if this menu item is a **Link** or a **Container** type. Links are used for linking to Products, Taxons and other parts of your website. In contrast, containers are used to group links together, creating organized sections of a menu.

### Code <a id="code"></a>

A menu item code is an optional setting that allows you to identify your link or container for specific uses; for example, if a container has the code of `promo`, links that are nested inside that container will appear as promotion links with large image and the name and subtitle displayed prominently, while links placed within a container with the code `category` will be displayed as standard menu text links.

The image below shows how the Spree Main Menu uses two containers, one outlined in green and the second outlined in red, each container has a code that identifies the links nested inside are to be displayed in different formats.

For more information on using the Spree Main Menu visit the [Building The Main Menu](https://app.gitbook.com/@spark-solutions/s/spree-user-documentation/building_the_main_menu) page.

![Contianers With Code](https://guides.spreecommerce.org/static/78b1518ea7d098c5abd37c5af62ea07f/03ffe/container_code.jpg)Contianers With Code

### Nest Under <a id="nest-under"></a>

The Nest Under option allows you to quickly nest your new item within other menu items, don’t worry; if you forget to nest your new menu item, you can re-arrange the items on the main menu items area,

Using the combination of **Item Type** and **Code** allows you as a designer to create menus of any kind imaginable. An example this would be to set the menu code in the footer view file to look for a container with the code of social; any links nested inside this container would be displayed as SVG icons to your company social media pages.

## Public Settings <a id="public-settings"></a>

Public setting is where your public-facing information is set.

### Name <a id="name"></a>

This is the name used for the link or container displayed in the view.

### Subtitle <a id="subtitle"></a>

The Subtitle used for standard links as the title attribute text, or on promotional items, the subtitle is displayed in the banner.

### Image <a id="image"></a>

You have the option to add a photo or SVG icon to your links or containers as you please. Once an image is added, you also have the opportunity to add image alt text for SEO.

## Link Settings <a id="link-settings"></a>

The link settings panel is where you set the link destination, by default, you are offered the URL field.

### URL <a id="url"></a>

You can enter a URL to an external website such as `https://example.com`. Link to a path in your store by simply setting the path `/some/page`. Or you could set the link to launch an email client or trigger a phone call by entering `mailto:sales@example.com` or `tel:123456789`.

To change the **Link To** option, you will need to select the link you desire, then click **Update** as prompted to load the appropriate link credentials.![Change Link To Type](https://guides.spreecommerce.org/static/22465455ad62880f66e77565f1881e8f/03ffe/link_to.jpg)Change Link To Type

### Taxon / Product <a id="taxon-product"></a>

To link to a Taxon or Product, select the desired item from the _Link To_ selector and click **Update** when prompted, as shown in the image above.

You will then be presented with a search box that allows you to search for the Taxon or Product you wish to link to. Once set, click **Update**, and the path to item will be displayed under the search field.

![Link To Sportsware Taxon Set](https://guides.spreecommerce.org/static/ebb547251d476956d5f8de18c95152e0/03ffe/link_to_taxon_set.jpg)Link To Sportsware Taxon Set

### Home Page <a id="home-page"></a>

Select **Home** from the **Link To** selector and click **Update**. Your link will now be set to the home page of your store.

