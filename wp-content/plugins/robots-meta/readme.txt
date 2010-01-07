=== Plugin Name ===
Contributors: joostdevalk
Donate link: http://yoast.com/donate/
Tags: meta,search engines,seo
Requires at least: 2.5
Tested up to: 2.8.2
stable tag: 3.2.2

This plugin makes it easy to add the appropriate meta robots tags to your pages, disable unused archives, nofollow unnecessary links as well as do some other SEO related actions.

== Description ==

There's no easy way to add meta robots tags to WordPress pages, unless of course, when you install this plugin.

This plugin makes it possible (and very easy) to:

* Prevent indexing of your search result pages, while still allowing the search engines to follow the links on them, by adding noindex,follow robots meta tags.
* Disallow indexing of subpages to your homepage, category pages, author pages and tag pages, to prevent duplicate content.
* Prevent indexing of your login, register and admin pages by adding noindex robots meta tags.
* Add noodp an noydir meta robots tags, allowing you to opt out of DMOZ and Yahoo! Directory descriptions.
* Prevent Yahoo! and Google from indexing your feeds by adding a meta tag to their head-section.
* Prevent indexing of just your comment feeds.
* Disable author and date-based archives.
* Prevent attachment pages from ranking in the search results over your articles.
* Enforce a trailing slash on archives.
* Edit your .htaccess and your robots.txt from within WordPress.
* Assign robots meta tags to individual posts & pages.
* Verify your site with Google Webmaster Tools, Yahoo! Site Explorer and Bing Webmaster Tools.
* Add noarchive tags to your blog (Thanks to [Henryk Gerlach](http://blog.littleimpact.de/index.php/2008/07/03/noarchive-tag-for-robots-meta/)). 

More info:

* [Robots Meta plugin](http://yoast.com/wordpress/meta-robots-wordpress-plugin/).
* Read more about [WordPress SEO](http://yoast.com/articles/wordpress-seo/) so you can get the most out of this plugin.
* Check out the other [Wordpress plugins](http://yoast.com/wordpress/) by the same author.

== Screenshots ==

1. Screenshot of the configuration panel for this plugin.
2. Screenshot of the right column block this plugin adds to the edit post and edit page admin areas.

== Changelog ==

= 3.2.2 =
* Upgraded backend class.

= 3.2.1 =
* Added localization for all texts.
* Added .POT file.
* Made .htaccess saving work again.
* Added possibility to edit wp-content/cache/.htaccess when wp-super-cache is active.
* Changed link from joostdevalk.nl to yoast.com (ouch, that move was almost a year ago).

= 3.2 =
* Switched to new backend class.
* Updated backend with new look and feel and added some scripting to make explanation showing and hiding easier.
* Added option to redirect attachment pages to their pagent posts / pages.
* Switched to new changelog.

== Installation ==

Installation is easy:

* Download and unzip the plugin.
* Copy the `robots-meta` folder to the plugins directory of your blog.
* Enable the plugin in your admin panel.
* An options panel will appear under Plugins.
* Choose the settings you want.
