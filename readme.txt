=== HTML Classified Recent Posts & Comments Widgets ===
Contributors: zaantar
Donate link: http://zaantar.eu/financni-prispevek
Tags: recent, posts, comments, widget, widgets, html, class, 
Requires at least: 3.3
Tested up to: 3.4.1
Stable tag: trunk
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Default WordPress widgets with "class" attributes identifying posts added to links.

== Description ==

This plugins adds two widgets: Classified Recent Posts and Classified Recent Comments. They differ from the default widgets only in one thing - each listed link contains HTML `class` attribute describing which post it is related to. For recent comments the whole `li` tag also contains this attribute.

Listed classes are similar to the output from `get_post_class` (see [WordPress Codex](http://codex.wordpress.org/Function_Reference/get_post_class)), each class has a prefix to prevent problems with CSS styling

* `crpw-` for Custom Recent Posts Widget
* `crcw-` for Custom Recent Comments Widgets

You can use this for example to highlight links to posts from chosen categories or witch chosen tags (or a particular post) via CSS.

== Frequently Asked Questions ==

No questions asked yet.

[Ask.](mailto:zaantar@zaantar.eu?subject=[html-classified-recent-posts-comments-widgets])

== Changelog ==

= 1.0 =
* First version
