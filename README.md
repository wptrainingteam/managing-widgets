# Managing Widgets

## Description

Widgets provide a convenient means of adding content and features to a website and require no coding experience. This lesson will provide an introduction to finding and including widgets in your website. We will demonstrate how to use the widgets included in the theme installed on a website, add widgets from plugins and customize a widget using simple HTML.

## Prerequisite Skills

*   Basic understanding of the [WordPress dashboard](https://make.wordpress.org/training/handbook/user-lessons/overview-of-the-dashboard/)
*   Basic understanding of a theme, [pages and posts](https://make.wordpress.org/training/handbook/user-lessons/pages-vs-posts/)
*   Basic understanding of the layout of a page including [the header, footer, sidebar and body](https://make.wordpress.org/training/handbook/theme-school/anatomy-of-a-theme/)
*   Understanding of [installing a plugin](https://make.wordpress.org/training/handbook/user-lessons/choosing-and-installing-plugins/) (helpful for last part of lesson)
*   Understanding of simple HTML formatting is helpful but not necessary

## Assets

*   [Twenty Fifteen theme](https://wordpress.org/themes/twentyfifteen/)
*   [Twenty Sixteen theme](https://wordpress.org/themes/twentysixteen/)
*   [WordPress Importer](https://wordpress.org/plugins/wordpress-importer/)
*   [Theme Unit Test Data](https://codex.wordpress.org/Theme_Unit_Test)
*   Example Plugin [Image Widget](https://wordpress.org/plugins/image-widget/)

## Screening Questions

*   Do you have admin access to your website? (Preferred answer: yes)
*   What theme are you currently using? (Preferred answer: anything but “I don’t know”)

## Teacher Notes

*   Ensure that the students' WordPress installations include both the Twenty Fifteen and Sixteen themes.
*   [Theme Unit Test Data](https://wpcom-themes.svn.automattic.com/demo/theme-unit-test-data.xml) and the [WordPress Importer plugin](https://wordpress.org/plugins/wordpress-importer/) are not critical but provide additional content to demonstrate the effects of changes to widget parameters.
*   We will start with the Twenty Sixteen theme activated and the Twenty Fifteen deactivated.
*   We will add the "[Image Widget](https://wordpress.org/plugins/image-widget/)" plugin. This can be installed beforehand but not activated.
*   Resources:
    *   [Codex](http://codex.wordpress.org/WordPress_Widgets "Codex - WordPress Widgets")
    *   [Plugin Directory](https://wordpress.org/plugins/tags/widget "WordPress Plugin Directory - Tag - Widgets")
    *   [Wordpress.com Widgets](https://wpcom-themes.svn.automattic.com/demo/theme-unit-test-data.xml "Dot Com Widget Examples")

## Hands-on Walkthrough

### Introduction

This lesson will walk you through managing widgets through **Dashboard>Appearance>Widgets**.

### What are widgets?

Widgets are tools that allow a user to add and control features or content to a sidebar, header or footer. In fact, they are cleverly disguised pieces of PHP, HTML, JavaScript or CSS that a user can manipulate without knowing any code by simply dragging and dropping a widget into a desired location on a page. If the widget offers this option, the author can further modify the content of the widget via a provided menu.

### Examples of Widgets

Widgets can add features to a page such as: a calendar, a map, an archive list, a list of profile photos for users that are currently logged in. [info]The current version of WordPress provide functionality to add widgets to posts. However, some creative authors have created plugins that provide users with the capability to add widgets to posts or within page content. We will not be covering this nuance in this tutorial[/info]. Review the homepage of the Twenty Sixteen theme and its predefined existing widgets in the footer . We'll discuss in a bit more detail where widgets come from, but suffice it to say that they either come bundled in a theme or can be added by installing and activating certain plugins. In today's tutorial we will be using the Twenty Sixteen and Twenty Fifteen themes. Let's have a look at how the theme authors are using widgets in a standard install of the Twenty Sixteen theme. [caption id="attachment_5560" align="aligncenter" width="281"][![twenty-sixteen-screen-shot](https://make.wordpress.org/training/files/2014/11/twenty-sixteen-screen-shot-281x300.jpeg)](https://make.wordpress.org/training/files/2014/11/twenty-sixteen-screen-shot.jpeg) image 1[/caption] Identify areas on the page where widgets can be included (e.g. footer, sidebars).

### Where do widgets come from?

*   Some widgets come from your WordPress install.
*   Other widgets may be included with your theme.
*   Many plugins provide widgets.

We'll work with the existing widgets in the Twenty Sixteen theme, then install a plugin from the repository that adds a widget.

### Where are your widgets?

*   Open your **Dashboard >Appearance>Widgets**.
*   **Available Widgets**: These are the widgets available for you to use.
*   **Sidebar Widget Area**: This region will be pre-populated with widgets at install.
*   **Content Bottom 1 Widget Area**: This area appears at the bottom of a post or page
*   **Content Bottom 2 Widget Area**: This area appears at the bottom of a post or page

Take a moment to find where these "widget areas" appear on your webpage.

### Modify, Add and Delete Widgets

You can drag and drop the widgets into these areas.  Let's start by deleting the "Recent Comments" widget from your sidebar. [![](https://make.wordpress.org/training/files/2014/11/Screenshot-2016-03-16-13.35.34-300x175.png)](https://make.wordpress.org/training/files/2014/11/Screenshot-2016-03-16-13.35.34.png)

When you click on the arrow to the right on the title line (see image 2), it will open your widgets options.

"Title", "Delete" and "Close" are the only options for the search widget.

Next, let's modify the "Category" widget to work as a dropdown. Save your work and view your site. Let's add a "Custom Menu" widget. You can drag and drop the widget into the widget area.  Now you can drag and drop your widget to place it where you like. [info]If you have not installed the "[test data](https://wpcom-themes.svn.automattic.com/demo/theme-unit-test-data.xml)" or created any menus, nothing will show up in the menu on your site.[/info] Last we will add a "Tag Cloud" to the "Content Bottom 1 Widget Area". Save your changes and view your site. [info]Note: The bottom 1 & 2 widget areas do not show up on blog front page of Twenty-Sixteen.[/info] [caption id="attachment_5866" align="alignright" width="269"][![widgets-select-add](https://make.wordpress.org/training/files/2014/11/widgets-select-add-269x300.png)](https://make.wordpress.org/training/files/2014/11/widgets-select-add.png) image 3[/caption] Another way to add a widget is to select the widget you want to use. A pull-down list of the widget areas will show up. Select the area in which you want to place your widget and click the "Add Widget" button. (see image 3) [caption id="attachment_5874" align="alignright" width="175"][![widget-google-embed](https://make.wordpress.org/training/files/2014/11/widget-google-embed-175x300.png)](https://make.wordpress.org/training/files/2014/11/widget-google-embed.png) image 4[/caption]

### The Text Widget

The text widget is very handy for adding simple HTML, images, or text into your widget area. Drag or place the "Text" widget into your "Sidebar".   Type your name and some text. Save your changes and view your site. You can add a Google map, also. Retrieve the Google map, and cut and paste the embed code into the text widget (see image 5).  Voilà ... your map appears in your sidebar!

### Inactive Widgets

[caption id="attachment_5865" align="alignright" width="300"][![widgets-inactive](https://make.wordpress.org/training/files/2014/11/widgets-inactive-300x197.png)](https://make.wordpress.org/training/files/2014/11/widgets-inactive.png) image 5[/caption] Often your widget will require some customization. If you have created a widget and want to save your settings, but need to remove it temporarily, you can save your widget and its settings in the "Inactive Widgets" area. Let's drag and drop the "Text" widget into the "Inactive Widgets" area. Now your widget is saved for future use. (see image 4)

### Widgets added with a plugins

*   Many WordPress plugins will give you a widget to use on your site.
*   Install (or activate) the plugin "[Image Widget](https://wordpress.org/plugins/image-widget/)"
*   [![Screen Shot 2016-03-06 at 11.42.26 AM](https://make.wordpress.org/training/files/2014/11/Screen-Shot-2016-03-06-at-11.42.26-AM-300x179.png)](https://make.wordpress.org/training/files/2014/11/Screen-Shot-2016-03-06-at-11.42.26-AM.png)A new widget will appear in your active widget area (image 6).
*   Drag the new widget into your sidebar.
*   Select an image you would like to place in your sidebar. After selection, many other options and fields will appear for including your image, title, alt-text, size, caption, link, etc... Configure accordingly.
*   Save your configuration and then view your site.

### Other Widget Areas

Let's change your theme to Twenty Fifteen. You can see you have the same widgets but have them show in a new and different widget area.  Twenty Fifteen comes with only one widget area labeled "Widget Area."  Other themes can have five, six, ten, or more widget areas. These are features of your theme and vary greatly. Let's change our theme back to Twenty Sixteen now. Widget visibility is theme dependent. Whether a widget appears to the left, right, or top of the page or on pages versus posts could all be unique to each theme.

### Wrap Up

*   Final result
*   Summary - You should be able to:
    *   Describe what a widget is
    *   Identify where to include widgets on a website
    *   Identify the widget areas built to a website theme
    *   Demonstrate how to add/delete/modify a widget
    *   Customize a simple widget using the "Text Widget"

## Exercises

**Exercise Name**

*   Add a search widget to your bottom footer 1 area.
*   Add a YouTube video.
*   Add a location map to the sidebar.
*   Save your map widget to the inactive widget area.
*   Add an image to your sidebar using the Image Widget

## Quiz

**Quiz Question**

1.  Describe how you change or include widgets on a freshly installed website.
2.  Name the locations of the widget areas on the Twenty Sixteen theme. (Answer: 3)
3.  On the Dashboard widget page, how can you remove a widget from widget area, but preserve the customizations made to the widget for a future use? (Answer: Drop it into the Inactive Widgets area at the bottom of the Widgets page.)

## Additional Resources

1.  [WordPress Widgets](https://codex.wordpress.org/WordPress_Widgets) @ Codex
2.  [Widget List](https://codex.wordpress.org/Widget_List) @ Codex
3.  [Widget Customizer](https://wordpress.org/plugins/widget-customizer/)
