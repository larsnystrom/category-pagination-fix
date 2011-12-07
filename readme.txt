=== Category pagination fix ===
Contributors: rahnas
Donate link: http://www.htmlremix.com/projects
Tags: category, pagination, 404 error, bugfixing, navigation
Requires at least: 2.0.2
Tested up to: 3.2.2
Stable tag: 3

Fixes 404 error bug in wp category page while using custom permalink structure. Now added support for custom post types by using snippets from jdantzer plugin

== Description ==

Fixes the bug in Wordpress 2.7 ( may be in lower version also) in category listing page pagination. When you are using permalink structure as %category%/%postname% , second page URL of category listing page will be category-name/page/2 which Wordpress identify "page" as post name. And will return 404 error page. This plug-in will fix the issue. This also fix the next and previous buttons bug in while using custom permalink structure. Bug is still there in Wordpress 3 too. So I'm updated this one.

== Installation ==

1. Upload `category-pagefix.php` to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. You are done

== Frequently Asked Questions ==

= Do I need to do some settings change ? =

No, this is just a bug fixing. You have nothing to do with it

= Do you have any question ? =
Just report your bug and comments on http://www.htmlremix.com/projects/category-pagination-wordpress-plugin

== Screenshots ==

1. No images yet
