=== Twitter Counter ===
Tags: Twitter, TwitterCounter, Twitter Counter, Counter, Twitter Widget
Contributors: Ajay
Donate link: http://ajaydsouza.com/donate/
Stable Tag: trunk
Requires at least: 3.0
Tested up to: 4.0
License: GPLv2 or later

Integrate TwitterCounter.com badges on your blog to display the number of followers you have on Twitter

== Description ==

<a href="http://ajaydsouza.com/wordpress/plugins/twittercounter/">Twitter Counter plugin</a> is the fastest and best way to add <a href="http://twittercounter.com">TwitterCounter.com</a> badges on your blog. All you need is to enter your Twitter username and TwitterCounter User ID and you're good to go.

You can also add the Twitter Widget to your blog, which shows which twitter users recently visited your blog or website.

The plugin is very easy to use and comes with several options that allows you to easily configure the buttons or the Twitter widget.

= Features =
* Display Twitter Counter buttons. Multiple options are available
* Display Twitter Widget
* Sidebar widgets allow you to add one or more buttons and widgets
* Complete customization from within the comfort of WordPress Admin
* Clean uninstall if you choose to delete the plugin (but why would you!)


== Upgrade Notice ==

= 1.6.3 =
* Renamed main plugin file; New admin interface; code cleanup;
Check ChangeLog for other changes

== Changelog ==

= 1.6.3 =
* Modified: Renamed ald-twittercounter.php to twittercounter.php
* Modified: Changed *echo_twitter_remote* to *echo_twitter_widget*
* Modified: Twitter Widget code has been updated to the latest version
* Modified: Brand you admin interface
* Modified: Complete code cleanup
* Modified: Deleted obsolete buttons

= 1.6.2 =
* Fixed: Notices when WP_DEBUG is TRUE
* Added: Latvian translation (Thanks <a href="http://enyko.de/">Johannes</a>)

= 1.6.1 =
* Fixed: PHP Notices
* Fixed: Possible CSRF loophole in Settings page

= 1.6 =
* Modified: Plugin updated for new Twitter Counter buttons and widgets options
* Modified: Users now need to enter their Twitter IDs in the settings page for best results
* Modified: Updated WordPress widget for multiple instances

= 1.5 =
* New: Twitter Button with Photo
* Modified: Better compatibility with the latest versions of WordPress. If you are using the sidebar widgets, please re-add them to your theme under Appearance > Widgets
* Modified: Twitter Remote has been renamed to Twitter Widget

= 1.4.1 =
* Added Russian language
* Fixed PHP undefined constant warnings

= 1.4 =
* Support for the new button code from Twitter Counter. Now you can choose custom foreground and background color.

= 1.3.3 =
* Internationalization fix

= 1.3 =
* Incorporated the new javascript based code. Added the new Big Bird style for the twittercounter button

= 1.2 =
* Integrated Twitter Widget

= 1.1 =
* Twitter Widget added. All options can be customized from with WP-Admin

= 1.0 =
* Release


== Installation ==

1. Download Twitter Counter.

2. Extract the contents of twittercounter.zip to wp-content/plugins/ folder. You should get a folder called twittercounter.

3. Activate the Plugin in WP-Admin.

4. Goto Settings &raquo; Twitter Counter and enter your Twitter username. First time users will need to sign into <a href="http://twittercounter.com">TwitterCounter.com</a>

5. Add `<?php do_action('echo_tc'); ?>` to your theme file where you want to display the counter or use the WordPress widget

6. Add `<?php do_action('echo_twitter_widget'); ?>` to your theme file where you want to display the counter or use the WordPress widget


== Screenshots ==

1. Twitter Counter Button options in WP-Admin
2. Twitter Widget options in WP-Admin
3. Custom Styles options in WP-Admin
4. Twitter Counter Button Widget settings
5. Twitter Widget widget settings


== Frequently Asked Questions ==

If your question isn't listed here, please post a comment at the <a href="http://wordpress.org/support/plugin/twittercounter">WordPress.org support forum</a>. I monitor the forums on an ongoing basis. If you're looking for more advanced _paid_ support, please see <a href="http://ajaydsouza.com/support/">details here</a>.

= Can I customize what is displayed? =

Several customization options are available via the Settings page in WordPress Admin. You can access this via <strong>Settings &raquo; Twitter Counter</strong>

== Wishlist ==

Below are a few features that I plan on implementing in future versions of the plugin. However, there is no fixed time-frame for this and largely depends on how much time I can contribute to development.

* Display statistics from Twitter Counter
* Integration with Twitter

If you would like a feature to be added, or if you already have the code for the feature, you can let us know by <a href="http://wordpress.org/support/plugin/twittercounter">posting in this forum</a>.


