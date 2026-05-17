A simple and clean weather widget that displays real-time weather data using the OpenWeatherMap API. Includes shortcode support, API key settings page, caching, and automatic icons.

== Description ==

Weather API Widget allows you to display current weather information anywhere on your WordPress site using a shortcode.  
It connects to the OpenWeatherMap API and shows temperature, conditions, humidity, wind speed, and weather icons.

Features:
* Shortcode: [weather city="Bucharest"]
* Supports metric and imperial units
* API key settings page in WordPress admin
* Built-in caching (30 minutes)
* Automatic weather icons
* Clean inline styling (no external CSS files)
* Error handling for missing API key or API failures

== Installation ==

1. Upload the plugin folder to `/wp-content/plugins/`
2. Activate the plugin from **Plugins → Installed Plugins**
3. Go to **Settings → Weather API**
4. Enter your OpenWeatherMap API key
5. Use the shortcode anywhere on your site

== Shortcode Usage ==

Basic example:
Parameters:
* `city` — City name (default: Bucharest)
* `units` — metric or imperial (default: metric)

== Frequently Asked Questions ==

= Where do I get an API key? =
You can create a free API key at https://openweathermap.org/api

= How often is the weather updated? =
The plugin caches results for 30 minutes to improve performance.

= Does it support widgets or Gutenberg blocks? =
Currently shortcode-only, but widget/block support may be added in future versions.

== Screenshots ==

1. Example of the weather widget displayed on the site.

== Changelog ==

= 1.1.0 =
* Added caching
* Added weather icons
* Improved error handling
* Cleaned up shortcode logic

= 1.0.0 =
* Initial release

== License ==

This plugin is licensed under the GPLv2 or later.
