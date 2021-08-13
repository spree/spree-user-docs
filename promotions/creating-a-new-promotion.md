# Creating a New Promotion

To create a new promotion, click the “New Promotion” button.

New Promotion

![New Promotion](https://guides.spreecommerce.org/static/e7df21ebc62f1705ddf9036d8b2339a1/03ffe/new_promotion.jpg)

The page that is shown allows you to set several standard options that apply to all promotions. Each is explained below.

| Option | Description |
| :--- | :--- |
| Name | The name you assign to the promotion. |
| Event Name | This is what must happen before the system will check to see if the promotion applies to the order. Options are: **Add to cart** \(any time an item is added to the cart\), **Order contents changed** \(an item is added to or removed from an order, or the quantity of an item in the order changes\), **User signup** \(a store visitor creates an account on the site\), **Coupon code added** \(a store visitor inputs a coupon code at checkout. The code has to match what you input for the code value if you select this option\), and **Visit static content page** \(a user visits a page or follows a certain path that you declare. This is often used to ensure that a customer has reviewed your store’s policies or has been exposed to content that is important to your business model.\) |
| Advertise | Checking this box will make the promotion visible to site visitors as they shop your store. |
| Description | A detailed explanation of the promotion. The customer will be able to see this description at the checkout. |
| Usage Limit | The maximum number of times the promotion can be used in your store across all users. If you don’t input a value for this setting, the promotion can be used an unlimited number of times. Beneath this input field is a “Current Usage” counter, which is useful later when you’re editing a promotion and need to know how many times the promotion has been redeemed. |
| Starts At | The date the promotion becomes valid. |
| Expires At | The date after which the promotion becomes invalid. |

When you enter values for these fields and click “Create”, a new screen is rendered, giving you access to even more options to fine-tune your promotion.

### [Rules](https://guides.spreecommerce.org/user/promotions/creating_promotions.html#rules) <a id="rules"></a>

Rules represent the conditions that must be met for a promotion to be applicable to an order. You can set one or more rules for a single promotion. When you set multiple rules, you have the option of either requiring all of the rules to be met for the promotion to apply, or allowing a promotion to apply to an order when only one of the rules is met.

There are five types of rules. You can only add one rule of each type to a single promotion. Each is explained in detail below.

![Rules Options](https://guides.spreecommerce.org/static/5960e472e08563296a3ecf9e5909956d/f89ac/rules_options.jpg)Rules Options

#### [Item Total](https://guides.spreecommerce.org/user/promotions/creating_promotions.html#item-total) <a id="item-total"></a>

When you select “Item total” from the “Add Rule of Type” drop-down menu and click “Add”, you are declaring an Item Total rule.

![Item Total Rule](https://guides.spreecommerce.org/static/728eee08419d6713bf8fd4cbaa81f7f4/074ac/item_total_rule.jpg)Item Total Rule

You can then set the parameters for this type of rule. Specifically, you can establish whether an order’s items must be **greater than** or **equal to or greater than** the amount you set. Click “Update”.

To remove a rule from a promotion, click the cross icon next to it.

![Delete Rule Icon](https://guides.spreecommerce.org/static/6ac00e7c3674cb25b0095cc790c9dabb/a2957/delete_rule_icon.jpg)Delete Rule Icon

#### [Products](https://guides.spreecommerce.org/user/promotions/creating_promotions.html#products) <a id="products"></a>

Using a rule of this type means the order must contain **at least one** or **all** of the products you declare.

![Products Rule](https://guides.spreecommerce.org/static/cd6e3d77bdc378237f728670265f970e/dcdd0/products_rule.jpg)Products Rule

To create this kind of rule, just select “Product\(s\)” from the “Add Rule of Type” drop-down menu and click “Add”. Start typing in the name of the product\(s\) you want to apply discounts to into the “Choose Products” box. Click on the correct variants. Choose either “at least one” or “all” from the selection box, and click “Update”.

#### [User](https://guides.spreecommerce.org/user/promotions/creating_promotions.html#user) <a id="user"></a>

You can apply the User rule type to restrict a promotion to only selected customers. To create this type of rule, select “User” from the “Add Rule of Type” drop-down menu and click “Add”. Start typing in the name or email address of the user\(s\) you want to offer this promotion to. As the correct users are displayed, click them to add them to the list. Once complete, click “Update”.

![User Rule](https://guides.spreecommerce.org/static/88ef53b6e9a481e65d32b57a00a9d4a1/282c4/user_rule.jpg)User Rule

#### [First Order](https://guides.spreecommerce.org/user/promotions/creating_promotions.html#first-order) <a id="first-order"></a>

Select “First order” from the “Add Rule of Type” drop-down menu and click “Add” then “Update” to add a rule of this type to your promotion. This rule will restrict the promotion to customers who are ordering from you for the first time.

![First Order Rule](https://guides.spreecommerce.org/static/a7c1283c1d1e0878837a8c6f45603ad4/40619/first_order_rule.jpg)First Order Rule

#### [User Logged In](https://guides.spreecommerce.org/user/promotions/creating_promotions.html#user-logged-in) <a id="user-logged-in"></a>

Add a rule of this type to restrict the promotion only to logged-in users. Select “User Logged In” from the “Add Rule of Type” drop-down list, click “Add”, then click “Update”.

![Logged In Rule](https://guides.spreecommerce.org/static/e728d5592db79070f64a2e40860a5e7d/eb520/logged_in_rule.jpg)Logged In Rule

### [Actions](https://guides.spreecommerce.org/user/promotions/creating_promotions.html#actions) <a id="actions"></a>

Whereas [Rules](https://guides.spreecommerce.org/user/promotions/creating_promotions.html#rules) establish whether a promotion applies or not, Actions determine what happens when a promotion does apply to an order. There are two types of actions: [create adjustments](https://guides.spreecommerce.org/user/promotions/creating_promotions.html#create-adjustments) and [create line items](https://guides.spreecommerce.org/user/promotions/creating_promotions.html#create-line-items).

#### [Create Adjustments](https://guides.spreecommerce.org/user/promotions/creating_promotions.html#create-adjustments) <a id="create-adjustments"></a>

When you select “Create adjustment” from the “Add Action of Type” drop-down menu and click “Add”, the system presents you with several calculator options. These are the same as the options you read about in the [calculators guide](https://guides.spreecommerce.org/user/shipments/calculators.html), except that instead of a [price sack calculator](https://guides.spreecommerce.org/user/shipments/calculators.html#price-sack), there are two additional calculators: percent per item and free shipping.

![Create Adjustments Action Calculators](https://guides.spreecommerce.org/static/4348c86f4dc2fd1c1f04908f9c6fb1ed/40619/create_adjustment.jpg)Create Adjustments Action Calculators

By default, when you add a new “Create adjustment” calculator, it is set to a “Flat percent” calculator. You can change this by selecting the new calculator type from the “Calculator” drop-down menu; however, you will need to click the “Update” button to get that calculator’s specific additional required fields to display.

Each calculator has its own set of required additional information fields.

| Calculator Type | Additional Data Required |
| :--- | :--- |
| Flat Percent | Percentage amount |
| Flat Rate | Amount of discount, and currency |
| Flexible Rate | The cost of the first item, the cost of each additional item, the maximum number of items included in the promotion, and the currency |
| Percent Per Item | Percentage amount |
| Free Shipping | No additional info required |

Enter all required information for your calculator type, then click “Update”.

#### [Create Line Items](https://guides.spreecommerce.org/user/promotions/creating_promotions.html#create-line-items) <a id="create-line-items"></a>

This action type is a way of automatically adding items to an order to which a promotion applies. To add this action to your promotion, select “Create line items” from the “Add Action of Type” drop-down menu and click “Add”.

![Create Line Item Action](https://guides.spreecommerce.org/static/c12123290535862112fa750414987b24/8144e/create_line_item.jpg)Create Line Item Action

Select the quantity and variant that you want automatically added to the customer’s order from the product drop-down menu. Click “Update”.

!!! Product variants added through Line Item Action Promotions will be priced as usual. If your intention is to add a free product, you should undertake both a Line Item action \(to add the product\) and an Adjustment action \(to discount the cost of that variant\). !!!

