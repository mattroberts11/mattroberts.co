=== Theme Blvd Widget Pack ===
Author URI: http://www.themeblvd.com
Contributors: themeblvd
Tags: widgets, Theme Blvd, themeblvd, Jason Bobich
Stable Tag: 1.0.6
Tested up to: 4.9

When using a Theme Blvd theme, this plugin adds a few widgets to extend some of the functionality already built into the framework.

== Description ==

After activating this plugin, six new widgets will be added under *Appearance > Widgets* of your WordPress admin panel.

= Mini Post Grid =

This widget utilizes the theme framework's post grid system to display a grid of featured images from posts. Standard framework featured image link settings will be utilized here and the posts used for the grid can queried in different ways. You can also choose to substitute in gallery of images belong to a page or post.

= Mini Post List =

This widget utilizes the theme framework's post list system to display a simple list of post titles and their associated featured images. Standard framework featured image link settings will be utilized here and the posts used for the list can queried in different ways.

= Simple Contact =

This widget provides you with some standard contact information you can fill out. Additionally you can setup a 1-6 icons linking to your relevant social networks; the 30 standard social network icons are included as possible selections for each.

= Horizontal Menu =

This widget allows you to select from any menus you've created under *Appearance > Menus* and display it horizontally in the design format setup by the framework's inclusion of Twitter Bootstrap. Utilize this widget within the theme's various collapsible, horizontal widget areas.

**NOTE: For this plugin to do anything, you must have a theme with Theme Blvd framework v2.2+ activated.**

== Installation ==

1. Upload `theme-blvd-widget-pack` folder to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. Go to *Appearance > Widgets* to use included widgets.

== Screenshots ==

1. Simple Contact Widget used with [Alyeska WordPress Theme](http://themeforest.net/item/alyeska-responsive-wordpress-theme/164366?ref=ThemeBlvd)
2. Mini Post Grid Widget used with [Swagger WordPress Theme](http://themeforest.net/item/swagger-responsive-wordpress-theme/930581?ref=ThemeBlvd)
2. Mini Post List Widget used with [Akita WordPress Theme](http://themeforest.net/item/akita-responsive-wordpress-theme/1530025?ref=ThemeBlvd)
3. Video Widget used with [Swagger WordPress Theme](http://themeforest.net/item/swagger-responsive-wordpress-theme/930581?ref=ThemeBlvd)

== Changelog ==

= 1.0.6 - 12/19/2017 =

* Removed video widget; use WordPress's core widget instead.

= 1.0.5 - 08/15/2015 =

* Fixed: WordPress 4.3 deprecated PHP4 style constructors.

= 1.0.4 - 12/10/2014 =

* GlotPress compatibility (for 2015 wordpress.org release).
* Minor security fix.

= 1.0.3 - 08/01/2013 =

* Removed Twitter widget; use [Tweeple](http://wordpress.org/plugins/tweeple/) instead.
* Mini Post Grid widget now accepts `[gallery]` shortcode usage for the Gallery Override feature. -- i.e. `[gallery link="file" ids="1,2,3"]`

= 1.0.2 - 05/31/2013 =

* Added better compatibility for WPML with Mini Post List and Mini Post Grid widgets.
* Fixed wording in warning when Theme Blvd framework isn't installed, and added "Dismiss" link.

= 1.0.1 - 03/22/2013 =

* Fixed TB_SIDEBARS_PLUGIN_DIR notice from localization.

= 1.0.0 - 09/03/2012 =

* This is the first release.
