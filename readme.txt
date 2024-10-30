=== Meerkat ===
Contributors: dartiss
Donate link: http://artiss.co.uk/donate
Tags: meerkat, video, stream, embed
Requires at least: 2.8
Tested up to: 4.6.1
Stable tag: 1.1.4
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Embed your Meerkat stream on your site so your followers, friends and fans can watch your stream anywhere.

== Description ==

**Version 1.1.4 will be the final release of this plugin and it will be completely removed from WordPress.org within the coming months. Meerkat (the app, rather than this plugin) have changed their strategy and are moving away from live video streaming - they are no longer spending time on their embedding and developer tools and, as a consequence, no longer work.**

The embedded player is smart. It will show your live stream if you're live. If you're not live, if will show your next upcoming stream. If you have no upcoming streams, it will display stats from your last stream. If you have not streamed yet, it will show your profile.

The embedded player enables you to decide exactly what appears on your site. You can toggle participation, load the player muted, set a predefined cover image and choose the shape of your player.

Technical specification...

* Designed for both single and multi-site installations
* PHP7 compatible
* Fully internationalized, ready for translations **If you would like to add a translation to his plugin then please head to our [Translating WordPress](https://translate.wordpress.org/projects/wp-plugins/meerkat "Translating WordPress") page**
* WCAG 2.0 Compliant at AA level

But, most importantly, there are no premium features and no adverts - this is 100% complete and free!

To add your stream to your site, simply use the following shortcode...

`[meerkat username="meerkatapi"]`

Replace the username of 'meerkatapi' with the stream username - yours or anybody elses. See the "Other Notes" tab for further parameters to personalise it further!

Alternatively, a widget is available for adding a video to your site's sidebar. Within Administration simply head to Appearance -> Widgets and drag the Meerket widget to any of your allocated widget areas. Complete the relevant details (for example, the user name) and the widget will display the Meerkat video.

== Additional Parameters ==

There are a number of other parameters available, to allow you to personalise the output further.

* **username** - The user to show the embed for. This must be specified.
* **type** - The embedded player is available in 3 sizes - "portrait" (437 x 246), "square" (246 x 246) and "bigsquare" (360 x 360). The default is "portrait".
* **participation** - Set to "true" to include comments, likes & restreams or set to "false" to show just the video. The default is "true".
* **cover** - Override the image for the embedded player in a non-live state. Point it at an image on the web.
* **muted** - Set to "false" and the player will load with audio playing if there is a current live stream or set to "true" and the player will load with audio muted by default. The default is "false".
* **debug** - By default, debug information is output to the page as hidden comments. These are useful when reporting any issues but can be switched off by setting this to "false".

For example...

`[meerkat username="meerkatapi" type="bigsquare" participation="false" muted="true"]`

This would display the stream for the username of "meerkatapi", in a big square format, with social options switched off and the video audio muted.

== Licence ==

This WordPress plugin is licensed under the [GPLv2 (or later)](http://wordpress.org/about/gpl/ "GNU General Public License").

== Installation ==

Meerkat can be found and installed via the Plugin menu within WordPress administration (Plugins -> Add New). Alternatively, it can be downloaded from WordPress.org and installed manually...

1. Upload the entire `meerkat` folder to your `wp-content/plugins/` directory.
2. Activate the plugin through the 'Plugins' menu in WordPress administration.

Voila! It's ready to go.

== Changelog ==

= 1.1.4 =
* Enhancement: After WordPress 4.6 the translations for the text domain don't need to be unloaded - so now I don't!

= 1.1.3 =
* Maintenance: Updated branding, inc. adding donation links

= 1.1.2 =
* Maintenance: Updated the branding

= 1.1.1 =
* Maintenance: Added a text domain and path

= 1.1 =
* Enhancement: Added a widget
* Enhancement: Added internationalisation

= 1.0 =
* Initial release

== Upgrade Notice ==

= 1.1.4 =
* Minor update for those running WP 4.6+

= 1.1.3 =
* Minor update to change branding. Again. Sorry.

= 1.1.2 =
* Minor update to change the branding

= 1.1.1 =
* Minor update to add a text domain and path

= 1.1 =
* Upgrade to add a widget as well as internationalisation

= 1.0 =
* Initial release
