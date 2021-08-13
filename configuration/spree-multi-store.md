# Spree Multi Store

### [Introduction](spree-multi-store.md#introduction) <a id="introduction"></a>

Spree 3.5 was released with Multi Store support. This means that, in a single Spree Admin panel, you can control multiple shops based on Spree. You can assign domains and manage orders; there is also an option to personalize products for a certain shop described [here](spree-multi-store.md#edit-store).

#### [Setup](spree-multi-store.md#setup) <a id="setup"></a>

Setup is simple. You just need at least two sites based on Spree with registered domains.

Open the Spree Admin panel and, under the Configurations tab, search for Stores.

![Multi store Admin panel setup](../.gitbook/assets/image%20%2842%29.png)

To make it even easier, one site is already set up to your current default. All you need to do is press the [Edit](spree-multi-store.md#edit-store) button in order to personalize it to your needs.

#### [Create New Store](spree-multi-store.md#create-new-store) <a id="create-new-store"></a>

In the right upper corner, press the _New Store_ button \(as shown in the screenshot above\).

![New store](../.gitbook/assets/image%20%2839%29.png)

![New store](../.gitbook/assets/image%20%2843%29.png)

![New store](../.gitbook/assets/image%20%2831%29.png)

* **Name** - value for you to recognize it
* **URL** - a line separated list of fully qualified domain names used to associate a customers session with a particular store \(you can use localhost and/or IP addresses too\)
* **Meta Description** - to make it easier for a customer using Google search to click your link
* **Meta Keywords** - words to describe your page as clearly and attractively as possible
* **SEO title** - the title shown in the browser tab when a user visits your page; for example, on a Chrome tab
* **Mail from address** - mail which will send notifications such as order confirmation/shipping to the users
* **CODE** - which is an abbreviated version of the store’s name \(used as the layout directory name, and also helpful for separating partials by store\).

Once you have completed these fields, press **Create**, and your multi store is setup and ready to go. It’s that simple!

![Multi stores](../.gitbook/assets/image%20%2823%29.png)

#### [Edit Store](spree-multi-store.md#edit-store) <a id="edit-store"></a>

In order to Edit an existing Store, simply press **Edit** button next to the Default and Delete.

![Edit Store Button](../.gitbook/assets/image%20%2846%29.png)

Inside, you will find the same values as described above in [Create New Store](spree-multi-store.md#create-new-store).

![Edit Store](../.gitbook/assets/image%20%2838%29.png)

Once you have finished editing, press the **Update** button.

#### [Customization](spree-multi-store.md#customization) <a id="customization"></a>

Each store can have its own layout\(s\). These should be located in your site’s theme extension in the app/views/spree/layouts/store\#code/ directory. So, if you have a store with a code of “alpha”, you should store its default layout in app/views/spree/layouts/alpha/spree\_application.html.erb.

It is worth mentioning that [Analytics](analytics-tracker.md#introduction) can be associated with a store.

#### [Orders](spree-multi-store.md#orders) <a id="orders"></a>

If the user places an order on any of your sites, you can observe which store processed the Order. Simply enter the Orders tab \(you can learn more about it [here](../orders/orders-description.md)\)and choose any order that you would like to check. Look for the “Store” option on the panel on the right side.

![Orders Stores](../.gitbook/assets/image%20%2829%29.png)

#### [Future development](spree-multi-store.md#future-development) <a id="future-development"></a>

In versions of Spree later than approximately 4.0 or 4.1, two additional extensions should be included to the Spree Core in order to improve Multi Store management and possibilities.

[Spree Multi Domain](https://github.com/spree-contrib/spree-multi-domain)

[Spree Multi Currency](https://github.com/spree-contrib/spree_multi_currency)

