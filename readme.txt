=== WP TypeIt ===

Contributors: alexmacarthur
Donate link: paypal.me/alexmacarthur
Tags: typewriter effect, text effect, text animation
Requires at least: 4.0
Tested up to: 4.9.6
Stable tag: 1.0.0
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

== Description ==
This is the official free WordPress plugin for TypeIt, the most versatile animated typing utility on the planet. WP TypeIt allows you to easily generate typewriter effects for your website by use of a single easy-to-configure shortcode. Place this shortcode on any post or page, and the effect will be live.

== Installation ==

1. Download the plugin and upload to your plugins directory, or install the plugin through the WordPress plugins page.
2. Activate the plugin through the 'Plugins' page.

== Using the Plugin ==

= Make an Effect Using Shortcode Attributes =
You can generate a typewriter effect by using a variation of the following shortcode in a post or page, passing each setting as a shortcode attribute. 

At bare minimum, you need to pass a `strings` attribute:

`
[typeit strings="Look, I'm typing a string!"]
`

There also exists a wide set of attributes you may use to customize the typing effects. For example, setting speed (in milliseconds): 

`
<h2>[typeit strings="Look, I'm typing a string!" speed="500"]</h2>
`

Or, making an effect continuously loop:

`
<h2>[typeit strings="This is a string that will loop!" speed="100" loop="true"]</h2>
`

For the full list of options you may pass, refer to the documentation at [typeitjs.com/docs#options](https://typeitjs.com/docs#options).

== Frequently Asked Questions ==

= The TypeIt JS library requires a paid license to use commercially. Do I need one with this plugin? =
Nope! Using this free plugin doesn't require a paid license to use, regardless of the project. However, if you wish to take advantage of the full feature set TypeIt offers, you'll need to purchase a license and implement the JS library on your own. Or, you may [hire me to help](https://macarthur.me/contact).

= Do I need to worry about other JavaScript dependencies (like jQuery) for this to work? = 
Nope! TypeIt uses vanilla JavaScript with no external dependencies, so you're good to go.

== Screenshots ==

== Changelog ==

= 1.0.0 =
* Initial release.

== Feedback ==

You like it? [Email](mailto:alex@macarthur.me) or [tweet](http://www.twitter.com/amacarthur) me. You hate it? [Email](mailto:alex@macarthur.me) or [tweet](http://www.twitter.com/amacarthur) me.

Regardless of how you feel, your review would be greatly appreciated!
