# Maintaining Your WordPress Site with [SiteOrigin Page Builder](https://siteorigin.com/page-builder/)
## The WordPress necessities, for everyone

[WordPress](https://wordpress.org/) is an [open source](https://en.wikipedia.org/wiki/Open-source_model) [content management system (CMS)](https://en.wikipedia.org/wiki/Content_management_system) and online publishing platform.

While WordPress is certainly simpler and more intuitive than building sites from scratch using html/css/php, it still has its fair share of whizzbangs, doodads, and mumbojumbo to stymie your creative process.

This tutorial will help you navigate the WordPress user interface so that you can harness its core functionality.

[Here are some examples of what you can do with WordPress](https://wordpress.org/showcase/)

## Table of Contents

* [About](#about)
* [Getting Started](#getting-started)
* [The Administrator View](#the-admin-view)
* [SiteOrigin Page Builder](#siteorigin-page-builder)

## About

Last Updated June 2017
Created by [Paul Vieth](http://paulkelleyvieth.org)
University of Oklahoma Libraries :: Digital Scholarship Lab

## Getting Started

This tutorial assumes you have already registered with WordPress and generated a site, or had someone help you generate your first site, and now the reins are in your hands. If you haven't done so, there are lots of [great tutorials](https://www.siteground.com/tutorials/wordpress/wordpress-installation.htm) to help you with this process.

## The Admin View

Once you have a WordPress account and site, you can access the administive view by appending "/admin" to the end of your site's url.
* For example: "[yourwebsite.wordpress.com]/admin"

For this tutorial I'll be using the [Capra/Bailey Project](http://caprabaileyproject.oucreate.com) created by [Ben Keppel](http://history.ou.edu/ben-keppel) and [Tara Carlisle](https://libraries.ou.edu/users/tara-carlisle) at the University of Oklahoma. 

If you are not automatically logged-in, you will be asked to do so at this point.

After you log in, you will see your site, with the administrative interface laid on top, like this:

![wordpress tutorial administrative view interface menu dashboard](/images/wordpress01.png)

**For ease of navigation, Wordpress has several redunancies built in. There are multiple ways to perform many of the operations, multiple buttons to get to the same place. Don't be confused by these reduncancies. For example the site theme, widgets, and menus can be adjusted through the "Customize" interface, or they can be accessed from the dropdown menu labeled with your site's title, or they can be managed from the appearance section of the dashboard -- all perform the same functions, it's just a matter of personal preference and accessibility.**

* The WordPress icon will take you to the WordPress current version homepage where you can learn about the WordPress capabilities now at your disposal. If you hover over it, you can:
  * Learn "About WordPress"
  * Visit WordPress.org
  * Access tutorials, the API, and plugins through the "Documentation" tab
  * Visit the "Support Forums" to connect with users like yourself with questions like yours
  * Give "Feedback" to WordPress
  
* The next tab (with the speedometer icon and your website's title) allows you to access:
  * the "Dashboard"
  * the "Themes" manager
  * the "Widgets" manager
  * the "Menus" manager
(More on each of these later)

* The "Customize" tab (with the paintbrush icon) allows you to manage:
  * "Site Identity"
    * where you can change the site title, tagline, and icon
  * "Colors"
    * background and accent colors
  * "Logo"
  * "Header Image"
  * "Background Image"
  * "Menus"
  * "Widgets"
  * Front Page Settings
  * "Additional CSS"
    * for customizing your site using [cascading style sheets](https://en.wikipedia.org/wiki/Cascading_Style_Sheets) commands

** The great thing about the "Customize" interface is that it allows you to preview the changes you're making in real time, so you can tweak your site with precision and awareness.

![wordpress tutorial customize interface](/images/wordpress02.PNG)

* The comments tab (speech bubble icon) allows you to view and manage comments to your site
  * the number beside the speech bubble icon is an alert for new icons
  * you can approve, delete, search for, or mark icons as spam

![wordpress tutorial comments interface manager](/images/wordpress03.PNG)

* The "New" tab (+ icon) allows you to quickly and conveniently add a new:
  * post
  * media file
  * link
    * including its advanced metadata relationships
  * page
  * or site user
* The "Edit Page" tab (pencil icon) allows you to edit the page you're currently on
  * You can edit pages by navigating to them using menus and then clicking this "Edit Page" button, or by going to the "Pages" tab in the Dashboard
* The right-most button in the Admin interface is the "Live Editor"
  * It is a condensed form of the page editor (the tab to the left of it) that, like the "Customize" interface, allows you to see the changes you're making in real time
  
![wordpress tutorial live-editor live editor interface view dashboard](/images/wordpress04.PNG)

## SiteOrigin Page Builder

### Installing SiteOrigin Plugins

This tutorial is concerned with the SiteOrigin "Page Builder" and "Widget Bundle" plugins. If you do not have these plugins installed, do so by:

* going to your WordPress Dashboard
* click "Plugins" from the menu on the left of the screen
* click "Add New" under the "Plugins" menu item, or the "Add New" button next to the "Plugins" page header

![wordpress tutorial plugin menu add new](/images/wordpress05.PNG)

In the top-right corner of the screen, in the "search plugins..." bar, search "siteorigin."

The first two results will be "Page Builder by SiteOrigin" and "SiteOrigin Widgets Bundle."

Install both of them with the "Install Now" button in the top-right corner of each plugin tile.

![wordpress tutorial install plugin](/images/wordpress06.PNG)

### Page Layouts with SiteOrigin 

Navigate to the editor of an existing page, or create a new page to play with your new SiteOrigin plugins.

You'll see the basic "New Page" editor where you can add media or text. At the top right of the editor box, you will see three tabs: "Visual," "Text," and "Page Builder."

* Click the "Page Builder" tab

![wordpress siteorigin tutorial page builder](/images/wordpress07.PNG)

There are three main things you can do with the SiteOrigin plugins:
* Use a prebuilt layout
* Design your own layout with the "Row" or "Add Row" (three horizontal bars icon) buttons.
* Add widgets to your layout

The prebuilt layouts handle themselves. All you have to do is browse for one you like and populate it with widget-based content.

We want to make our own custom layouts, though, so we can have the capacity to mould our sites to our imaginations.

* Click either of the "Add Row" buttons

![wordpress siteorigin page builder tutorial add row](/images/wordpress08.PNG)

This will open the "New Row" window

![wordpress siteorigin page builder tutorial new row](/images/wordpress09.PNG)

SiteOrigin Page Builder allows you to arrange your content using a grid system. That is, you will build your page one row at a time; for each row, you will be allowed to determine the number of columns in that row, as well as that row's stylistic properties within the parameters allowed by SiteOrigin Page Builder.

The "New Row" window allows you to:
* set the number of columns (1-12)
* set the relative widths of the columns
  * either from a dropdown menu of preset ratios (including "the golden"!)
  * or manually by hovering between the column previews (in the light blue) and clicking and dragging to the desired ratios
* **[ADVANCED]** Change the style properties of the row
  * Attributes
    * assign the row/a cell an id/class to be referenced other places in code
    * to manipulate the css properties for the row
  * Layout
    * margins
    * padding
    * screen-size response properties (how the layout changes when the page is viewed on a mobile device)
  * Design
    * background color/image and its properties
    
For example, the [Capra/Bailey Project homepage](http://caprabaileyproject.oucreate.com/) uses the SiteOrigin Page Builder (pay attention to the content pane below the menu).
  
The Capra/Bailey Project homepage is composed of one row of one column containing the site introduction text, then three rows of three columns each -- creating a gallery of images representing and linking to the various sections of the site.

![wordpress siteorigin page builder tutorial caprabailey capra bailey project homepage](/images/wordpress10.PNG)

This is what that same layout looks like in the SiteOrigin Page Builder editor:

![wordpress siteorigin page builder tutorial caprabailey capra bailey project homepage editor](/images/wordpress11.PNG)
  
  
  
  
  
  
