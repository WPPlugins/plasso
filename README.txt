=== Plasso ===

Contributors: jschuller
Donate link: http://plasso.com
Tags: plasso, plasso product pages, plasso overlay, plasso embed, ecommerce, e-commerce, commerce, javascript, overlay, embed
Requires at least: 3.9.0
Tested up to: 4.7.2
Stable tag: 1.1.2
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Extend any WordPress website with simple commerce tools (sell products, memberships, etc.) powered by Plasso.

== Description ==

Extend any WordPress website with simple commerce tools powered by Plasso — together a complete solution to sell virtually anything and grow your audience. Create your website using any WordPress theme, then add Plasso product/cart buttons using simple shortcodes to begin selling products, memberships and more. Use our importer to convert existing customers into Plasso customers ensuring a seamless transition from any existing Stripe powered solution. Create a new Plasso account today, or if you’re already a Plasso user, install our free WordPress plugin to get started.

Basic example:
`[plasso id="abc123"]`

Advanced example:
`[plasso id="abc123" text="Buy This Awesome Thing" class="button"]`

See full documentation in Settings > Plasso after plugin has been activated.

== Installation ==

= 1. Admin Search =
1. In your Admin, go to menu Plugins > Add.
1. Search for `Plasso`.
1. Find the plugin that's labeled `Plasso`.
1. Click to install.
1. Activate the plugin.
1. A new menu item `Plasso` will appear under your Settings menu.

= 2. Download & Upload =
1. Download the plugin (a zip file) on the right column of this page.
1. In your Admin, go to menu Plugins > Add.
1. Select the tab "Upload".
1. Upload the .zip file you just downloaded.
1. Activate the plugin.
1. A new menu item `Plasso` will appear under your Settings menu.

= 3. FTP Upload =
1. Download the plugin (.zip file) on the right column of this page.
1. Unzip the zip file contents.
1. Upload the `plasso` folder to the `/wp-content/plugins/` directory of your site.
1. Activate the plugin through the 'Plugins' menu in WordPress.
1. A new menu item `Plasso` will appear under your Settings menu.

== Frequently Asked Questions ==

= I’ve activated the plugin, but it doesn’t work. =

Your theme must implement **wp_footer()** in the footer.php file, otherwise the Plasso JavaScript will not load correctly. You can test if this is the issue by switching to a WordPress stock theme such as twenty-twelve temporarily.

== Screenshots ==

1. Activate the Plasso plugin.
1. Add a simple shortcode anywhere.
1. Sell products, services, memberships through simple modal boxes.

== Changelog ==

= 1.1.2 =
* Improved activation experience.
* Clarified documentation.
* Product preselect options.
* Fixes home page redirect loop.
* Plasso protected page created and set on activation.
* Product preselect integration.

= 1.1.1 =
* Links to our WordPress themes.

= 1.1.0 =
* New, awesome options page design, plus misc. fixes.

= 1.0.2 =
* Fixing HTTP to HTTPS redirect on logout.

= 1.0.1 =
* Adding compatibility with the new Plasso Billing product.

= 1.0 =
* This is the first release... enjoy.
