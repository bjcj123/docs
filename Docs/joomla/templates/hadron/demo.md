---
title: Hadron: Recreating the Demo
description: Your Guide to Recreating Elements of the Hadron Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/hadron:Hadron

---

Introduction
-----

Recreating features of the demo site used to show off some of the more interesting aspects of Hadron can be done fairly easily. All you need is the right extensions and settings, and you should be able to reproduce most (if not all) of the elements found in our demo site. 

Below, we will break down some of these elements and give you the information you need to know to recreate them on your own site using the Hadron Template.

Keep in mind that a lot of the detail that makes our demos look so good is the result of many hours of hard work by our team, and some of them will require a moderate level of experience working with the Joomla back end. We have added most of these elements into the template's core files in order to make them easily accessible without having to edit any code.

>> NOTE: We recommend downloading a copy of the RocketLauncher whenever you are attempting to replicate demo content. This allows easy referencing, whether on your site in a subdirectory, development server, or on a localhost. This will allow you to see all of our demo content in context, making it easier to replicate.

Module Settings
-----


Below, you will find the module placement and settings for the various module positions as they appear on the front page of our demo. Not all of these position assignments are unique to the front page.

![][Hadron2]

:   1. **FP RokAjaxSearch**  [9%, 87%, sw]
    2. **FP RokSprocket Showcase**  [12%, 13%, se]
    3. **A contemporary and flat design**  [27%, 13%, se]
    4. **Latest Featured Works**  [36%, 13%, se]
    5. **FP RokSprocket Strips**  [40%, 13%, se]
    6. **FP RokSprocket Tabs**  [53%, 13%, se]
    7. **Gantry Extras**  [56%, 63%, se]
    8. **Get in Touch**  [77%, 40%, se]
    9. **FP Newsletter**  [83%, 35%, se]

We have detailed how to recreate the individual modules pictured above in the links below.

1. [FP RokAjaxSearch][module1]
2. [FP RokSprocket Showcase][module2]
3. [A contemporary and flat design][module3]
4. [Latest Featured Works][module5]
5. [FP RokSprocket Strips][module6]
6. [FP RokSprocket Tabs][module7]
7. [Gantry Extras][module8]
8. [Get in Touch][module9]
9. [FP Newsletter][module10]

Recommended Extensions
-----

Here is a list of RocketTheme extensions used to create the demo version of Hadron:

* [Gantry Template Framework][gantry]
* [RokAjaxSearch][rokajaxsearch]
* [RokBox][rokbox]
* RokCommon Library (Installed with RokSprocket)
* [RokSprocket][roksprocket]
* [RokCandy][rokcandy]
* [RokNavMenu][roknavmenu]
* [RokBooster][rokbooster]

Many of these extensions are included with the Hadron RocketLauncher, and can be downloaded and installed individually by going to the RocketTheme website.

Recreating the Front Page
-----

The front page of the Hadron demo sits apart from the rest of the page layouts in that it features the latest and greatest features of the template. It is because of this that several module and layout overrides were done. In this section, we will break down the settings you will need to recreate elements present in the front page of the Hadron demo.

Template Settings
-----

The first thing you will need to do in order to set your front page apart as it appears in the demo is to create a style override. This can be done by navigating to **Administrator -> Extensions -> Template Manager** and selecting the template you wish to change.  Once you have checked the box next to the template, you can click the **Duplicate** button to create a second copy of the template. This will become the Override while the primary copy of the template remains the designated Master.

Only options that are different from the Master copy will take hold on the menu items you have assigned to the override. In this case, you will be assigning the front page to the override as we have in the demo.

It would be a good idea for organization to name this override something like **Hadron - Home** as it would be used only for the front page of your site.

#### Assignments

The next step you will need to take in creating your Template Settings override is to assign the Front Page style to the site's home page. 

You will need to start by navigating to **Admin > Extensions > Template Manager > (Your Home Override)** and select the **Assignments** tab. Under the **Main Menu** list, you will want to select **Home**.

Doing this will assign the style to the home page. This will allow the style to cover all access scenarios that would lead a user to your site's main home page.

You can find more information about the entire override breakdown for both the front page and our default settings in the demo by visiting the [template style portion][demooverride] of this tutorial.

Menu Settings
-----

![][mainmenu]

In your site's main menu, you will want to make a couple of key changes in order for your home page to appear as it does in our demo.

You can find these settings by navigating to **Admin > Menus > Main Menu > Home**. Once there, you will want to select the **Page Display** tab.

You will need to change the **Page Class** setting under the Home menu item to ` jan14-home`.

The icons that appear at the top-level menu area are configured under the individual menu item's **Dropdown Menu Options**, and are set in the **Menu Icon** option.

For example, the **Pages** menu icon is set to `icon-file-text`. For a full list of icons you can choose from, check out [this list by Font Awesome][icons].

[gantry]: http://gantry-framework.org/download
[rokajaxsearch]: http://www.rockettheme.com/joomla/extensions/rokajaxsearch
[rokbox]: http://www.rockettheme.com/joomla/extensions/rokbox
[roksprocket]: http://www.rockettheme.com/joomla/extensions/roksprocket
[Hadron2]: assets/hadron2.jpeg
[demooverride]: demo_override.md
[roknavmenu]: http://www.rockettheme.com/joomla/extensions/roknavmenu
[rokbooster]: http://www.rockettheme.com/joomla/extensions/rokbooster
[rokcandy]: http://www.rockettheme.com/joomla/extensions/rokcandy
[module1]: demo_module_1.md
[module2]: demo_module_2.md
[module3]: demo_module_3.md
[module4]: demo_module_4.md
[module5]: demo_module_5.md
[module6]: demo_module_6.md
[module7]: demo_module_7.md
[module8]: demo_module_8.md
[module9]: demo_module_9.md
[module10]: demo_module_10.md
[module11]: demo_module_11.md
[module12]: demo_module_12.md
[module13]: demo_module_13.md
[mainmenu]: assets/menu_1.jpeg
[icons]: http://fortawesome.github.io/Font-Awesome/icons/
[article]: assets/article.jpg
[demo11]: assets/demo_10.jpeg
