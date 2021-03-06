=== Plugin Name ===
Contributors:  samueljesse, uditvirwani
Tags: maps, baidu, baidu maps
Requires at least: 3.0.1
Tested up to: 4.2
Stable tag: 1.2
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Custom Baidu Maps is a Wordpress plugin to easily create and integrate one or more Baidu maps with custom 
locations in to your site.

== Description ==

Easily create Custom Baidu Maps to add to any Wordpress ost or page. You can create one or multiple maps 
with our easy to use settings panel, then insert the map using a shortcode.

With Custom Baidu Maps you can customize each map with multiple locations with options to add/change location 
coordinates, add a description, choose background and font colors and upload your own custom marker image.


Basic Usage with shortcodes :

To provide a map with the width and height of 500 * 400,
centered at latitude : 39.900 , longitude : 116.403
with a zoom of '12'

[bmap width="500" height="400" lat="39.900" lng="116.403" zoom="12"]

Options :
- width 	: width of the map entered in pixels
- height 	: height of the map entered in pixels
- lat			: latitude of the map
- lng			: longitude of the map
- zoom		: zoom level of the map (1 - 19), lowest to highest


Advanced Usage Baidu Maps post-type :

1. Enter your Baidu Developers API Key (if you have not already).
1. Select the "Baidu Maps" post type from the wordpess menu.
1. Click on "Add New".
1. Enter the map settings (height, width, zoom and coordinates).
1. Upon publishing, add the new generated shortcode to the page content.


Adding a Marker on the map (optional) :

1. Click on "Add Marker" below to add a new marker to this map.
1. Enter the marker details (name, description, coordinates, background color, font color).
1. You may also change the default marker image with you own image, click on "Choose Image" to select an image.
1. Click on "Show Marker Details" if you wish to see the details visible at start.



== Installation ==

Follow the steps below for the plugin installation :


1. Upload `baidu-maps.zip` to the `/wp-content/plugins/` directory or add the plugin via wordpress plugin repository.
1. Activate the plugin through the 'Plugins' menu in WordPress.
1. Enter your Baidu Developer API key in the settings page.


== Frequently Asked Questions ==

= Why is the plugin showing an error "You have not entered your Baidu Developers API Key" =

To use Baidu Maps, you need to have a Baidu Developers API Key.
To obtain the API Key please visit : http://lbsyun.baidu.com/apiconsole/key

A Detailed guide on how to create the API Key is available in the Settings Page


== Screenshots ==


== Changelog ==

= 1.1 =

PHP warnings fixed and added instructions to create the Baidu Developers API Key

= 1.2 =

PHP warnings fixed and added instructions to create the Baidu Developers API Key


== Upgrade Notice ==
