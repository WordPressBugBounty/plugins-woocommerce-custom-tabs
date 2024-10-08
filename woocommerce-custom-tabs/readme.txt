
=== Woocommerce Custom Tabs ===
Contributors: WebshopLogic
Donate link: http://webshoplogic.com/donation-woocommerce-custom-tabs/
Tags: Product tab, Woocommerce product tabs, Custom tab, WooCommerce
Requires at least: 3.7
Tested up to: 5.4
Stable tag: 1.0.29
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Custom product tab pages can be added to WooCommerce products using this plugin. 

== Description ==

As a good shop owner, you may want to publish more information about your products. This plugin will help you displaying product details in separate tab pages. Even shortcodes may be used to display galleries, product support forums (e. g. bbpress) and statistics. Some functions are available in Pro version only.

= Features =
* Easy tab content handling
* Native WordPress Wysiwyg editor for editing custom content
* Tab page positioning (priority)
* Hide empty tabs
* Includes .mo and .po files for localization
* Possibility of using shortcode
* Lite version can handle only one custom tab (so called Lite tab)

= Pro Version =
* Multiple tabs handling
* Pre-register tabs, this way you can make standardized tabs for a bunch of products 
* Product category dependent tab pages
* More Actions and Filters for customization
* Tab type default content, tab type content header, tab type content footer

= Available languages =
* English
* Chinese - translated by Janfeng Lee

= More information, documentation =
LITE: [Woocommerce Custom Tabs Lite Documentation](https://webshoplogic.com/products/wordpress_plugins/woocommerce-custom-tabs-lite-plugin/#tab-faq&noscroll)
PRO: [Woocommerce Custom Tabs Pro Documentation](https://webshoplogic.com/custom-tabs-for-woocommerce-plugin/)

== Installation ==

1. Upload the plugin to the '/wp-content/plugins/' directory.
2. Activate it through the 'Plugins' menu in WordPress.
3. Enable plugin

== Frequently Asked Questions ==

=You can find FAQ here:=
[Documentation / FAQ](https://webshoplogic.com/products/wordpress_plugins/woocommerce-custom-tabs-lite-plugin/#tab-faq&noscroll)

== Screenshots ==

1. Custom tab page

2. Plugin Options page

3. Product Edit page

4. Multiple custom tab page (Pro)

5. Multiple custom tab types admin list (Pro)

6. Custom tab type definition page (Pro)

7. Product Edit page, multiple tab content fields (Pro)


== Changelog ==

= 1.0.29 =
* fix: remove a wsl_log line, that could cause a 500 error

= 1.0.28 =
* fix: tab content header, footer and default content is not displayed

= 1.0.27 =
* upgrade: upgrade ACF to 5.8.9
* eliminate deprecated create_function from tab content generation callback

= 1.0.26 =
* fix: wrong result count on product category page

= 1.0.25 =
* new feature: possibility of using shortcodes in tab titles

= 1.0.24 =
* new feature: Show license activation technical information

= 1.0.23 =
* fix: New embedded ACF version

= 1.0.22 =
* modified: wct-single-product.js handle if .wc-tabs css class is missing

= 1.0.21 =
* fix: plugin version and name setting problem

= 1.0.20 =
* fix: Java Script conflict with WooCommerce 2.6

= 1.0.19 =
* new feature: Plugin activation and automatic update function using Woocommerce API Manager

= 1.0.18 =
* modified: update included WP WYSIWYG to Version: 1.0.2

= 1.0.17 =
* modified: use normal function instead of anonymous function in tab order usort function, because anominous function is available in PHP 5.3 or higher
  
= 1.0.16 =
* modified: new acf version

= 1.0.15 =
* fix: Only five category dependent tab appeard
* new feature: ordered tab fields on edit product admin page

= 1.0.14 =
* fix: Inside page anchor link to a tab problem

= 1.0.13 =
* new feature: direct link to a tab

= 1.0.12 =
* fix: save tab content problem

= 1.0.11 =
* fix: performance problem about category search

= 1.0.10 =
* New feature: Do not display tabs assigned to a sub category.


= 1.0.9 =
* New feature: Tab type default content, tab type content header, tab type content footer
* fix: delete unnecessary rows from sanitize function
* fix: empty $post->id problem in get_actual_product_related_tab_page_objects
* fix: wct_product_fields filter problem if no tabtype is defined at all

= 1.0.8 =
* add: load plugin textdomain
* Chinese language version
* Remove enable plugin checkbox in admin panel

= 1.0.7 =
* fix: other problem of disabling wordpress.org update for PRO version

= 1.0.6 =
* fix: unnecessary BR tags in tab contents
* fix: problem of disabling wordpress.org update for PRO version

= 1.0.5 =
* fix: get posts paging limit problem
* fix: space in tab code problem

= 1.0.4 =
* fix: disable wordpress.org update for PRO version
* Enable using of shortcodes in Lite version

= 1.0.2 - 1.0.3 =
* fix: sub-plugin header problem 

= 1.0.0 =
* First version

== Upgrade Notice ==

= 1.0.0 =
* First version
