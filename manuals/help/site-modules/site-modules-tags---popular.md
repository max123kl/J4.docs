---
sidebar_position: 21
id: site-modules-tags---popular
title: "Help4.x:Site Modules: Tags - Popular"
---
## Description

The **Tags - Popular** module type displays tags used on the site in a
list or a cloud layout. Tags can be ordered by title or by the number of
tagged items and limited to a specific time period.

## How to Access

- Select **System **→** Manage Panel **→** Site Modules** from the
  Administrator menu. Then...
  - To create a new module: select the **New** button from the Toolbar.
    Then...
    - Select the required module type.
  - To edit an existing module:
    - Find the module in the list of installed modules and select the
      title link in the **Title** column.

## Screenshot

<img
src="https://docs.joomla.org/images/e/ef/Help-4x-modules-site-module-manager-module-popular-tags-en.png"
decoding="async" data-file-width="800" data-file-height="677"
width="800" height="677"
alt="Help-4x-modules-site-module-manager-module-popular-tags-en.png" />

## Form Fields

- **Title.** The title of the module. This is also the title displayed
  for the module depending on the *Show Title* Form Field

### Module Tab

**Left Panel**

- **Parent Tag.** Limit tags shown to the children of this Parent Tag.
- **Maximum tags.** (*1*/*2*/*3*/*4*/*5*/*6*/*7*/...). Sets the maximum
  number of tags to display in the module.
- **Time Period.** (*All time*/*Last hour*/*Last day*/*Last week*/*Last
  month*/*Last year*). Sets the time period for which to calculate
  popularity.
- **Order.** (*Title*/*Number of Items*/*Random*). The order that tags
  will show in.
- **Direction.** (*Ascending*/*Descending*). Sort order. Descending is
  highest to lowest. Ascending is lowest to highest.
- **Display number of items.** (*Yes*/*No*). Choose if the number of
  tagged items should be displayed next to each tag.
- **Show "No results" text.** (*Yes*/*No*). Will show a message if no
  matching tags are found instead of hiding the module.

**Right Panel**

- **Show Title.** (Show/Hide) Choose whether to show or hide the modules
  title in the front end. The title will be the one in the Form Field
  above.

<!-- -->

- **Position.** Choose the [module
  position](https://docs.joomla.org/Module_Position/en "Module Position/en")
  you wish this module to be displayed in. A custom module position can
  be entered for use with the [load position
  plugin](https://docs.joomla.org/How_do_you_put_a_module_inside_an_article%3F/en "How do you put a module inside an article?/en")
  or the position button can be pressed to select a module position from
  the template.

<!-- -->

- **Status**. The published status of the item.

<!-- -->

- **Access**. The [viewing Access
  Level](https://docs.joomla.org/Help4.x:Users:_Viewing_Access_Levels/en "Special:MyLanguage/Help4.x:Users: Viewing Access Levels/en")
  for this item.

<!-- -->

- **Module Ordering.** This shows a drop down of every module in the
  position that the current module is in. This is the order that the
  modules will display in when displayed on in the front end as well as
  in the
  [Modules](https://docs.joomla.org/Help4.x:Modules/en "Help4.x:Modules/en")
  page.

<!-- -->

- **Start Publishing**. Date and time to start publishing. Use this
  field if you want to enter content ahead of time and then have it
  published automatically at a future time.

<!-- -->

- **Finish Publishing**. Date and time to finish publishing. Use this
  field if you want to have content automatically changed to Unpublished
  state at a future time (for example, when it is no longer applicable).

<!-- -->

- **Language**. Item language.

<!-- -->

- **Note**. This is normally for the site administrator's use (for
  example, to document information about this item) and does not show in
  the Frontend of the site.

### Menu Assignment Tab

<img
src="https://docs.joomla.org/images/0/05/Help-4x-modules-manager-site-module-menu-assignment-tab-en.png"
decoding="async" data-file-width="600" data-file-height="595"
width="600" height="595"
alt="Help-4x-modules-manager-site-module-menu-assignment-tab-en.png" />

- **Module Assignment.** Select **On All Pages**, **No Pages**, **Only
  on the pages selected** or **On all pages except those selected** from
  the List.

<!-- -->

- **Menu Selection.** If the latter two options are selected a list will
  show all of the menu items. This allows you to assign modules to some
  but not all pages, and by selecting the menu links that you want the
  module associated with you can customize on what pages modules
  appear/don't appear. See [How do you assign a module to specific
  pages?](https://docs.joomla.org/How_do_you_assign_a_module_to_specific_pages%3F/en "How do you assign a module to specific pages?/en")
  for more information.

### Cloud Layout Tab

<img
src="https://docs.joomla.org/images/5/5e/Help-4x-modules-site-module-manager-module-popular-tags-cloud-layout-en.png"
decoding="async" data-file-width="600" data-file-height="185"
width="600" height="185"
alt="Help-4x-modules-site-module-manager-module-popular-tags-cloud-layout-en.png" />

- **Minimum font size:** The minimum font size used for the tags,
  proportional to the site's default font size (e.g. "2" means 200% of
  the default size).
- **Maximum font size:** The maximum font size used for the tags,
  proportional to the site's default font size (e.g. "2" means 200% of
  the default size).

### Advanced Tab

<img
src="https://docs.joomla.org/images/4/4b/Help-4x-modules-manager-admin-module-site-advanced-options-en.png"
decoding="async" data-file-width="600" data-file-height="422"
width="600" height="422"
alt="Help-4x-modules-manager-admin-module-site-advanced-options-en.png" />

- **Layout.** If you have defined one or more alternative layouts for a
  module either in the template or Joomla! Core, you can select the
  layout to use for this module.
- **Module Class.** A suffix applied to the CSS class of the Module.
  This allows you to create customized CSS styles that will apply just
  to this module. You would then modify the "user.css" file of your
  template to apply styling to this new class. Enter this parameter with
  a leading space to create a new CSS class for this module. Enter the
  parameter without a leading space to change the CSS class name for
  this module.
- **Caching.** Use Global/No Caching. Whether or not to cache the
  content of this Module. A setting of "Use Global" will use the Cache
  Settings from the Global Configuration screen.
- **Cache Time.** The number of seconds for which to cache the item
  locally. It can safely be left at the default.
- **Module Style.** You can use this option to override the templates
  style for its position.
- **Module Tag.** The HTML tag for the module to be placed in. By
  default this is a div tag but other HTML5 elements can also be used.
- **Bootstrap Size.** (Values 0 to 12) This allows you to choose the
  width of the module via the span element built into bootstrap.
- **Header Tag.** The HTML tag to use for the modules header or title.
  This can be an h1, h2, h3, h4, h5, h6 or a p tag. Note that you must
  use a module style (chrome) of html5 or add your custom module styles
  in \<mytemplate\>/html/modules.php.
- **Header Class.** Here you can add optional CSS classes to add to the
  modules header or title element.

### Permissions Tab

<img
src="https://docs.joomla.org/images/d/d8/Help-4x-modules-manager-admin-module-administrator-permissions-en.png"
decoding="async" data-file-width="600" data-file-height="374"
width="600" height="374"
alt="Help-4x-modules-manager-admin-module-administrator-permissions-en.png" />

To change the permissions, do the following.

- Select the **Group** by clicking its title located on right.
- Find the desired **Action**. Possible Actions are:
  - **Delete**. Users can delete the module.
  - **Edit**. Users can edit the module.
  - **Edit State**. User can change the published state and related
    information for the module.
- Select the desired permission for the action you wish to change.
  Possible settings are:
  - ***Inherited.*** Inherited for users in this Group from the Global
    Configuration, Article Manager Options, or Category permissions.
  - ***Allowed.*** Allowed for users in this Group. Note that, if this
    action is Denied at one of the higher levels, the Allowed permission
    here will not take effect. A Denied setting cannot be overridden.
  - ***Denied.*** Denied for users in this Group.
- Select **Save** in the **Toolbar**. When the screen refreshes, the
  Calculated Setting column will show the effective permission for this
  Group and Action.

## Toolbar

At the top of the page you will see the toolbar shown in the Screenshot
above. The functions are:

- **Save.** Saves the item and stays in the current screen.

<!-- -->

- **Save & Close**. Saves the item and closes the current screen.

<!-- -->

- **Save & New**. Saves the item and keeps the editing screen open and
  ready to create another item.

<!-- -->

- **Save as Copy**. Saves your changes to a copy of the current item.
  Does not affect the current item. This toolbar icon is not shown if
  you are creating a new item.

<!-- -->

- **Close**. Closes the current screen and returns to the previous
  screen without saving any modifications you may have made.

<!-- -->

- **Help**. Opens this help screen.
