=== Plugin Name ===
Contributors: Ramoonus
Donate link: http://www.ramoonus.nl/donate/
Tags: css3, css, javascript, media, internet explorer, media queries, responsive
Requires at least: 3.9
Tested up to: 4.6
Stable tag: 1.4.2

Respond.js is a fast & lightweight polyfill for min/max-width CSS3 Media Queries (for IE 6-8, and more).

== Description ==
A fast & lightweight polyfill for min/max-width CSS3 Media Queries (for IE 6-8, and more)

Javascript by Scott Jehl, [scottjehl.com](http://scottjehl.com)
icensed under the MIT or GPL Version 2 licenses.


The goal of this script is to provide a fast and lightweight (3kb minified / 1kb gzipped) script to enable [responsive web designs](http://www.alistapart.com/articles/responsive-web-design/) in browsers that don't support CSS3 Media Queries - in particular, Internet Explorer 8 and under. It's written in such a way that it will probably patch support for other non-supporting browsers as well (more information on that soon).

If you're unfamiliar with the concepts surrounding Responsive Web Design, you can read up [here](http://www.alistapart.com/articles/responsive-web-design/) and also [here](http://filamentgroup.com/examples/responsive-images/)

= How to get it working =
<pre>
    @media screen and (min-width: 480px){
        ...styles for 480px and up go here
    }/*/mediaquery*/
</pre>

From 1 October 2016 on, this plugin is no longer supported. Please use [Powerpack](http://www.ramoonus.nl/wordpress/powerpack/) instead.

== Installation ==
1. Upload `respondjs/` to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress

Its recommended to flush the cache after upgrading.

== Changelog ==
= 1.4.2 =
* Based on Respond.js 1.4.2
* Readme updates

= 1.2.0 =
* Based on Respond.js 1.2.0
* Readme updated

= 1.1 =
* Based on Respond.js 1.1

= 1.0.0.1 =
* Based on Respond.js 1.0.0

= 1.0.0 =
* First version (8-5-2011)