=== Media Sync ===
Contributors: erolsk8
Donate link: https://www.paypal.me/erolsk8
Tags: media, sync, import, uploads, database
Requires at least: 3.0.1
Tested up to: 5.1.1
Requires PHP: 5.4
Stable tag: 1.0.0
License: GPLv2+
License URI: https://www.gnu.org/licenses/gpl-2.0.html

Simple plugin to scan "uploads" directory and bring those files into Media Library.

== Description ==

You can scan all files that are in "uploads" directory and see which ones are actually in Media Library and which ones are just sitting there. Then you can select those that you want to import to database and therefore make them available in Media Library.

You can also use FTP to upload your files to "uploads" directory and use this plugin to bring those files into Media Library. There are other plugins that can be used for that, but with this one you can easily select all and import all at once.

This plugin is still in early development so it has basic functionality, but more features will be added if there is some interest for that.

= Why I created this plugin =
I once copied WordPress site to a different server and Media Library ended up being empty, even tho all files were in "uploads" directory and database was copied. So I had to use some other plugin which required me to manually enter each directory and import files in batches per each director. But I needed something to just import everything at once, so I created this plugin.

Files that are ignored:
- index.php,
- various hidden files,
- WP generated thumbnails - anything ending with for example -100x100.jpg.


== Installation ==

1. Upload `media-sync` directory to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress

== Screenshots ==

1. Initial Page
2. Example of selecting files for import
3. Import to Media Library in progress
4. Import completed

== Changelog ==

= 1.0.0 =
* New option to clean up Media Library from items that are missing actual files (using custom Media Library filter)
* New filter when scanning uploads directory which can help to show only files missing from Media Library

= 0.1.6 =
* Fix PHP short array syntax
* Update required PHP version to 5.4

= 0.1.5 =
* Date of imported Media Library item is now set based on file modification timestamp

= 0.1.4 =
* Add plugin localization
* Add Serbian translation

= 0.1.3 =
* Various improvements and fixes

= 0.1.2 =
* Fix sorting of directories and files
* Minor wording changes and code cleanup

= 0.1.1 =
* Fix error on activation

= 0.1.0 =
* Initial plugin features

== Upgrade Notice ==

= 0.1.0 =
Initial plugin features