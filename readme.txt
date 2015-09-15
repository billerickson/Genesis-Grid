=== Genesis Grid ===
Contributors: billerickson
Donate link: https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=MQKRBRFVRUV8C
Tags: genesis, genesiswp, grid, loop
Requires at least: 3.0
Tested up to: 4.3
Stable tag: 1.4.2

Customize your archive pages in Genesis to use a grid layout. Requires the Genesis theme.

== Description ==
The Genesis Grid plugin was design to allow users of the Genesis theme to easily display their posts in a grid format.

"Features" are full-width posts at the top of the listing. "Teasers" are the posts broken into columns. You can set the number of Features and Teasers for both the homepage and inner pages, and how many columns the teasers are broken into.

You can also specify the image sizes used for Features and Teasers. I recommend setting Features for Large, and Teasers for Medium. Then go to Settings > Reading and set the dimensions of those images as needed. If you have already uploaded images, use the Regenerate Thumbnails plugin to rebuild the thumbnails at these dimensions. If images aren't showing up, make sure you have "Include featured images" checked in Genesis > Theme Settings > Content Archives

Finally, you can specify where the grid loop is used by checking Home, Category Archives, Tag Archives, Taxonomy Archives, Author Archives, and/or Search Results. See the Developers section for more fine-grained control.

[Documentation](https://github.com/billerickson/Genesis-Grid/wiki)

**No support will be provided by the developer**


== Installation ==

1. Upload `genesis-grid` to the `/wp-content/plugins/` directory.
1. Activate the plugin through the *Plugins* menu in WordPress.
1. Go to Genesis > Grid Loop to customize


== Changelog ==

**Version 1.4.2**
* Fix notice of undefined constant

**Version 1.4.1**

* Fix pagination issue when you set posts_per_page to -1

**Version 1.4**
 
* Added support for custom post type archives

**Version 1.3**

* Fix compatibility issues with Featured Post/Page widgets

**Version 1.2**

* Added a date archive option
* Other minor improvements

**Version 1.1**

* Added an author archive option.
* Updated the option labels to make them easier to understand
* Improved Internationalization, props @deckerweb
* German translation files, props @deckerweb

**Version 1.0**

* Initial release