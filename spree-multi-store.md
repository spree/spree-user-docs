# Spree Multi Store

### Introduction <a id="introduction"></a>

Spree 3.5 was released with Multi Store support. This means that, in a single Spree Admin panel, you can control multiple shops based on Spree. You can assign domains and manage orders; there is also an option to personalize products for a certain shop described [here](https://guides.spreecommerce.org/user/configuration/configuring_multi_stores.html#product-and-shop-currency).

#### [Setup](https://guides.spreecommerce.org/user/configuration/configuring_multi_stores.html#setup) <a id="setup"></a>

Setup is simple. You just need at least two sites based on Spree with registered domains.

Open the Spree Admin panel and, under the Configurations tab, search for Stores.

![Multi store Admin panel setup](https://guides.spreecommerce.org/static/400f457e72b43750051f6a6f3fe441b8/03ffe/spree_multi_store_admin_page.jpg)Multi store Admin panel setup

To make it even easier, one site is already set up to your current default. All you need to do is press the [Edit](https://guides.spreecommerce.org/user/configuration/configuring_multi_stores.html#edit-store) button in order to personalize it to your needs.

#### Create New Store <a id="create-new-store"></a>

In the right upper corner, press the _New Store_ button \(as shown in the screenshot above\).

![New store](https://guides.spreecommerce.org/static/96dd870b6ee76500a8b562c1800e428f/9eded/new_store.jpg)New store![New store](https://guides.spreecommerce.org/static/67f3836152267429ba80b85985fe991f/f516f/new_store_2.jpg)New store![New store](https://guides.spreecommerce.org/static/c6618c1f7b83281b88a02b57c95811e6/0df74/new_store_3.jpg)New store

* **Name** - value for you to recognize it
* **URL** - a line separated list of fully qualified domain names used to associate a customers session with a particular store \(you can use localhost and/or IP addresses too\)
* **Meta Description** - to make it easier for a customer using Google search to click your link
* **Meta Keywords** - words to describe your page as clearly and attractively as possible
* **SEO title** - the title shown in the browser tab when a user visits your page; for example, on a Chrome tab
* **Mail from address** - mail which will send notifications such as order confirmation/shipping to the users
* **CODE** - which is an abbreviated version of the store’s name \(used as the layout directory name, and also helpful for separating partials by store\).

Once you have completed these fields, press **Create**, and your multi store is setup and ready to go. It’s that simple!

![Multi stores](https://guides.spreecommerce.org/static/94e81e96cc3c919501922d1e34f5ae28/5c8dc/spree_multi_stores.jpg)Multi stores

#### Edit Store <a id="edit-store"></a>

In order to Edit an existing Store, simply press **Edit** button next to the Default and Delete.

![Edit Store Button](https://guides.spreecommerce.org/static/a4e630a1f58088608b6a208a51143c15/03ffe/edit_store_btn.jpg)Edit Store Button

Inside, you will find the same values as described above in [Create New Store](https://guides.spreecommerce.org/user/configuration/configuring_multi_stores.html#create-new-store).

![Edit Store](https://guides.spreecommerce.org/static/61d83b4c18360d0ccfe37bc21891f296/03ffe/edit_store.jpg)Edit Store

Once you have finished editing, press the **Update** button.

#### Customization <a id="customization"></a>

Each store can have its own layout\(s\). These should be located in your site’s theme extension in the app/views/spree/layouts/store\#code/ directory. So, if you have a store with a code of “alpha”, you should store its default layout in app/views/spree/layouts/alpha/spree\_application.html.erb.

It is worth mentioning that [Analytics](https://guides.spreecommerce.org/user/configuration/configuring_analytics.html) can be associated with a store.

#### [Orders](https://guides.spreecommerce.org/user/configuration/configuring_multi_stores.html#orders) <a id="orders"></a>

If the user places an order on any of your sites, you can observe which store processed the Order. Simply enter the Orders tab \(you can learn more about it [here](https://guides.spreecommerce.org/user/orders/)\)and choose any order that you would like to check. Look for the “Store” option on the panel on the right side.

![Orders Stores](https://guides.spreecommerce.org/static/5c98c6b62b8a0a5419c7a127b764fbad/03ffe/order_stores.jpg)Orders Stores

#### Future development <a id="future-development"></a>

In versions of Spree later than approximately 4.0 or 4.1, two additional extensions should be included to the Spree Core in order to improve Multi Store management and possibilities.

[Spree Multi Domain](https://github.com/spree-contrib/spree-multi-domain)

[Spree Multi Currency](https://github.com/spree-contrib/spree_multi_currency)

