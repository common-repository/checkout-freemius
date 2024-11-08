=== Freemius Checkout ===
Contributors: ramiy, freemius
Tags: freemius, checkout, buy button
Requires at least: 4.0
Tested up to: 4.9
Stable tag: 1.2
Requires PHP: 5.3
License: GPLv3
License URI: https://opensource.org/licenses/GPL-3.0

Sell WordPress Plugins & Themes. Anywhere. Using Freemius Checkout "Buy Now" button.

== Description ==

[Freemius](https://freemius.com/) empowers WordPress plugin/theme developers to sell in minutes, helping them create prosperous subscription based businesses.

With [Freemius Checkout](https://freemius.com/wordpress/checkout/) you can sell your digital WordPress products from anywhere.

This plugin allows anyone selling WordPress plugins or themes to embed a "Buy Now" button anywhere in your site using a simple WordPress shortcode.

When embedded, the user will see a simple "Buy Now" button on the front-end. Clicking the button will open the checkout popup.

= Usage =

The plugin uses **[freemius_checkout]** shortcode to embed the "Buy Now" button.

The shortcode is very customizable, to setup a custom product you can use the following attributes:

* **name** - Your plugin/theme name.
* **plugin_id** - Your plugin/theme ID on freemius.
* **plan_id** - The plan you want to promote using the button.
* **pricing_id** - The plan pricing level.
* **public_key** - Plugin/theme public key.
* **image** - The plugin/theme logo URL. Will be displayed in the popup.
* **button** - The text to display on the button. Default is 'Buy Now'.
* **button_id** - The button tag 'ID' attribute. Default is 'purchase'.
* **button_class** - The button tag 'Class' attribute, to add your own styling.

Example:

`[freemius_checkout name="Press Elements" plugin_id="761" plan_id="1078" pricing_id="928" public_key="pk_fe2850d57f7d4f206aefaa106b91f" button_id="purchase" button="Buy Now"]`

== Screenshots ==
1. Freemius Checkout

== Frequently Asked Questions ==

= Why is the checkout button not working? =

The theme needs to use jQuery to display the checkout popup. If it doesn't enqueue jQuery, the button won't open the checkout popup.

= What are the plugin requirements? =

**Minimum Requirements**

* WordPress version 4.0 or greater.
* PHP version 5.3 or greater.
* MySQL version 5.0 or greater.

**Recommended Requirements**

* The latest WordPress version.
* The latest PHP version.
* MySQL version 5.7 or greater.

== Changelog ==

= 1.2 =
* Hide empty parameters.

= 1.1 =
* Add `pricing_id` parameter to set custom pricing level for a plan.
* Use unique JS variables in case of multiple uses.
* Escape the attributes in the HTML.

= 1.0 =

* Initial release.
* Freemius checkout shortcode.
