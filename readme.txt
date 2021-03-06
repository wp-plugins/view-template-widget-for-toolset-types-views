=== Content Template Widget for Toolset Views ===
Contributors: khromov
Tags: views, toolset, types, view-templates, widget, wp-compatibility
Requires at least: 3.5
Tested up to: 4.2
Stable tag: 1.2.1
License: GPL2

Allows you to add a Widget that displays a Content Template from Toolset Views

== Description ==
Content Template Widget (previously View Template Widget) is useful for inserting information boxes about the current post being displayed in the widget area of your theme. It is possible to configure which content types each widget will be shown on.

This plugin requires Toolset Views. Click the link below for more information on this plugin:  
http://wp-types.com/home/views-create-elegant-displays-for-your-content/

**Usage**

*Basic usage*

* Activate Views for Wordpress
* Create a Content Template
* Add a WP Views Content Template widget to your site

The title field supports shortcodes, so you can easily use a wpv- shortcode in the widget title.

Although it is possible to expose the widget on all pages by selecting "Show widget everywhere", it is most useful on predefined post types, as 
archives, listings and tag pages will only return one result. (Most often the first item in the archive.)

To display a listing in the widget area, use a View Widget instead. (Included in Views.)

== Requirements ==
* PHP 5.2 or higher

== Translations ==
* None. Translations welcome.

== Installation ==
1. Upload the `view-template-widget-for-toolset-types-views` folder to `/wp-content/plugins/`
2. Activate the plugin (View Template Widget for Toolset Views) through the 'Plugins' menu in WordPress
3. Add a Views Template widget to your site.

== Frequently Asked Questions ==
- No questions available.

== Screenshots ==

1. Workflow example. Adding a sidebar widget to display information about the currently viewed post.

== Changelog ==

= 1.2.1 =
* Fixed edge case in conditional logic, see: http://wordpress.org/support/topic/widget-shows-on-search-page

= 1.2 =
* If the content template you use in a widget does not print anything, the widget will not be displayed. More info [here](http://wordpress.org/support/topic/empty-results-1).

= 1.1 =
* Updated name to reflect the name change introduced in Views 1.3 (View Template -> Content Template)
* Fixed a bug where all templates would not be available on certain configurations. (Thanks peter8810)

= 1.0 =
* Initial release

== Upgrade Notice ==
= 1.1 =
* Updated name to reflect the name change introduced in Views 1.3 (View Template -> Content Template)
* Fixed a bug where all templates would not be available on certain configurations. (Thanks peter8810)

= 1.0 =
Initial release