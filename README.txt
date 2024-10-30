=== Insert This! Content Inserts ===
Contributors: karlazz
Donate link: none!
Tags: inserts, content management, shortcode, widget
Requires at least: 3.0.1
Tested up to: 3.61
Stable tag: 4.3
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Use Inserts to manage sidebar content instead of text widgets.  Identify inserts in widgets with titles; organize with taxonomies.

== Description ==

Replace your text widgets with Inserts that are made of a custom post type.

You can classify them, tag them, restore revisions, check the author, and find the modification history.  They are easy to edit with the WordPress editor (well, as good as that gets) and you won’t be editing them in a tiny narrow column on your widgets screen.

Once you create your insert, you can use the Insert This! Widget to display it in the sidebars or choose to use a shortcode instead and display your insert any where.  

Intelligent Content Inserts are theme independent.  Inspired by Justin Tadlock’s QueryPosts widget and the Featured Posts/Pages widgets from StudioPress, this is an easy to use and theme independent way to manage text you want to have appear in sidebars.  In addition, I have provided a shortcode so you can display these inserts in any page or post.

For improved administration of your sidebar content, the widget lets you set a widget title, so all your text type widgets won’t look alike, then you can choose not to display the title on your web page!  You have three choices for title display: no title, widget title, or insert title.  

The widget also allows you to set a css class for your insert.

Why use Insert This! Intelligent Content Inserts?

Here is a perfect use case: you have an address that you have to show in the header on the home page, on a sidebar inside, and in the text on a landing page.  Your client moves!  If you use an insert then you only have to change the address once.

Here is another:  you have the board of directors displayed in a sidebar.  Your client wants to edit the list.  If you used a text widget then you have to explain all the html, and apologize for how difficult it is to edit.  Maybe you provided the Black Mountain Tinymce editor for them, to improve the experience, but it is still not the best user experience from WordPress.  Or perhaps you used Queryposts or something similar and you have to explain to them that the board of directors is on a page (or a post) but it doesn’t show up in the blog or the menu.   

With Inserts your client can just go and look up the insert named Board of Directors and edit that, no confusion about a page or a post.  

Here is another use case:  you have several advertisers and several styles of advertisement.  In your sidebar, they all are titled “Text” because you don’t want to display a title.

Instead, use Insert This! Intelligent Content Inserts and create your ad code snippets, with relevant titles.  Then you can classify them as Ads, tag them etc in your Inserts edit panels for future management.  Now just add the ads to your sidebars via the widget.  Choose a helpful title on the widget, so you can differentiate your ads in your sidebar, and select “no title” for display!  


== Installation ==

This section describes how to install the plugin and get it working.

e.g.

1. Upload `insert-this` to the `/wp-content/plugins/` directory
1. Activate the plugin through the 'Plugins' menu in WordPress
1. Use the widget or use the shortcodes [insert id=...] or [Insertthis id=...]

== Frequently Asked Questions ==
= How do I get the id for the shortcode? =
The id of the insert is displayed in the index page for all inserts.

= How do I select an insert from a widget? =
There is a dropdown list.

= Are there any other attributes for the shortcode? =
Yes, you can choose to display the title of the insert, hide it, or add a title specific to the location of your insert.
By default, no title is displayed.
You can also set an html id for the insert, and a class.

[insert css= id= use_title= title= before_title= after_title= ]

[InsertThis css= id= use_title= title= before_title= after_title= ]

Attributes:

	css = This is the attribute for the html class.
	
	id  = This is the post id. This option is required.
	
	use_title = Default is n for no.  Other options: b to use the title of the insert, w to use title defined in shortcode (or widget) .
	
	title = This is the title you would use if you set use_title=w.
	
	before_title = Defaults to `<h4>`
	
	after_title = Defaults to `</h4>` .  You are responsible for matching the tags if you change these.
	

= What about internationalization? =
Coming soon.

== Screenshots ==

1. none :-(

== Changelog ==

= 1.3.3 =
* This is the first published version.
