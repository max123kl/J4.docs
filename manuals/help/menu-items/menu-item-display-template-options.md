---
sidebar_position: 11
id: menu-item-display-template-options
title: "Help4.x:Menu Item: Display Template Options"
---
## Description

The **Display Template Options** menu item type allows a Joomla!
super-user to easily change some template options from the front-end.
After a change, the super-user will see the results immediately. This
menu item is intended to help new super-users with site development.

## How To Access

To create a new **Display Template Options** menu item:

- Select **Menus **→** \[name of the menu\]** from the Administrator
  menu (for example, **Menus **→** Main Menu**).
  - Select the **New** button in the Toolbar.
  - Select the Menu Item Type Select button. <img
    src="https://docs.joomla.org/images/thumb/0/0a/Help-4x-Menu-Item-Type-Select-Button-en.png/54px-Help-4x-Menu-Item-Type-Select-Button-en.png"
    decoding="async"
    srcset="https://docs.joomla.org/images/thumb/0/0a/Help-4x-Menu-Item-Type-Select-Button-en.png/82px-Help-4x-Menu-Item-Type-Select-Button-en.png 1.5x, https://docs.joomla.org/images/0/0a/Help-4x-Menu-Item-Type-Select-Button-en.png 2x"
    data-file-width="96" data-file-height="45" width="54" height="25"
    alt="Help-4x-Menu-Item-Type-Select-Button-en.png" />
  - In the modal dialog select the Configuration Manager item to open a
    list and then select the **Display Template Options** item.

To edit an existing Display Template Options menu item:

- Select its Title in the Menus: Items list.

## Screenshot

<img
src="https://docs.joomla.org/images/0/09/Help-4x-Menus-Menu-Display_Template_Options-screen-en.png"
decoding="async" data-file-width="800" data-file-height="812"
width="800" height="812"
alt="Help-4x-Menus-Menu-Display Template Options-screen-en.png" />

## Form Fields

- **Menu Title:** The title that will display for this menu item.

<!-- -->

- **Alias**. The internal name of the item. Normally, you can leave this
  blank and Joomla will fill in a default value Title in lower case and
  with dashes instead of spaces. [Learn
  more.](https://docs.joomla.org/Alias/en "Special:MyLanguage/Alias/en")

### Details Tab

**Left Panel**

- **Menu Item Type**. The Menu Item Type selected when this menu item
  was created. This can be one of the core menu item types or a menu
  item type provided by an installed extension.

<!-- -->

- **Link**. The system-generated link for this menu item. This field
  cannot be changed and is for information only.

<!-- -->

- **Target Window.** Select from the drop-down list.

<!-- -->

- **Template Style.** Select from the drop-down list.

**Right Panel**

- **Menu**. Shows which menu the link will appear in.

<!-- -->

- **Parent Item.** The parent menu item for this menu item. Used to
  determine whether a Menu Item is a top-level item or a submenu item.
  Select 'Menu Item Root' (the default value) if this is a top-level
  Menu Item. Otherwise, select the Menu Item that is this item's parent.

<!-- -->

- **Ordering.** You can change the order of an item within a list as
  follows:
  - If the list Filter Options include a Position filter select the
    desired Position. This will limit the list to items that are
    assigned to that Position.
  - Select the Ordering icon <img
    src="https://docs.joomla.org/images/e/ee/Help30-Ordering-colheader-icon.png"
    decoding="async" data-file-width="12" data-file-height="23" width="12"
    height="23" alt="Help30-Ordering-colheader-icon.png" /> in the Table
    heading to make it the active ordering item. The ordering icons in
    each row will change from light grey to dark grey and the pointer
    will change to a drag arrow on hover.
  - Select one of the Ordering icons <img
    src="https://docs.joomla.org/images/8/87/Help30-Ordering-colheader-grab-bar-icon.png"
    decoding="async" data-file-width="10" data-file-height="21" width="10"
    height="21" alt="Help30-Ordering-colheader-grab-bar-icon.png" /> and
    drag it up or down to change the position of that row in the list.
    The items will display in the new order within the Position.

<!-- -->

- **Status**. The published status of the item.

<!-- -->

- **Start Publishing**. Date and time to start publishing. Use this
  field if you want to enter content ahead of time and then have it
  published automatically at a future time.

<!-- -->

- **Finish Publishing**. Date and time to finish publishing. Use this
  field if you want to have content automatically changed to Unpublished
  state at a future time (for example, when it is no longer applicable).

<!-- -->

- **Default Page**. If Yes, this menu item is the default or home page
  for the site. There must be exactly one menu item set as the default
  page. You can change the default page in two ways:
  1.  Click on the Home column of the desired menu item in the [Menus:
      Items](https://docs.joomla.org/Help4.x:Menus:_Items/en "Special:MyLanguage/Help4.x:Menus: Items/en")
      screen.
  2.  Open the menu item for the new default page and change the Default
      Page setting to Yes.

<!-- -->

- **Access**. The [viewing Access
  Level](https://docs.joomla.org/Help4.x:Users:_Viewing_Access_Levels/en "Special:MyLanguage/Help4.x:Users: Viewing Access Levels/en")
  for this item.

<!-- -->

- **Language**. Item language.

<!-- -->

- **Note**. This is normally for the site administrator's use (for
  example, to document information about this item) and does not show in
  the Frontend of the site.

### Common Options

See [Menus: Edit/New
Item](https://docs.joomla.org/Help4.x:Menu_Item:_New_Item/en "Help4.x:Menu Item: New Item/en")
for help on fields common to all Menu Item types located in the
following Tabs:

- **Link Type**
- **Page Display**
- **Metadata**
- **Associations**
- **Module Assignment**

## Toolbar

At the top of the page you will see the toolbar shown in the Screenshot
above. The functions are:

- **Save.** Saves the menu item and stays in the current screen.

<!-- -->

- **Save & Close**. Saves the menu item and closes the current screen.

<!-- -->

- **Save & New**. Saves the menu item and keeps the editing screen open
  and ready to create another menu item.

<!-- -->

- **Save as Copy**. Saves your changes to a copy of the current menu
  item. Does not affect the current menu item. This toolbar icon is not
  shown if you are creating a new menu item.

<!-- -->

- **Cancel**. Closes the current screen and returns to the previous
  screen without saving any modifications you may have made. Or

<!-- -->

- **Close**. Closes the current screen and returns to the previous
  screen without saving any modifications you may have made.

<!-- -->

- **Help**. Opens this help screen.

## Front End Screenshot

<img
src="https://docs.joomla.org/images/8/8b/Help-4x-Menus-Menu-Display_Template_Options-front-end-screenshot-en.png"
decoding="async" data-file-width="600" data-file-height="646"
width="600" height="646"
alt="Help-4x-Menus-Menu-Display Template Options-front-end-screenshot-en.png" />

## Related Items

|                                                                                                                      |                                                                                                                                                                                                                                                                                                                                                                                          |
|----------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Related Help Screens                                                                                                 | Description                                                                                                                                                                                                                                                                                                                                                                              |
| [Templates: Styles](https://docs.joomla.org/Help4.x:Templates:_Styles/en "Help4.x:Templates: Styles/en")             |                                                                                                                                                                                                                                                                                                                                                                                          |
| [Templates: Edit Style](https://docs.joomla.org/Help4.x:Templates:_Edit_Style/en "Help4.x:Templates: Edit Style/en") | This is where you edit template styles. When a template is first installed, a default style is created for it. The default style for the template will have the same name as the template with a - Default suffix. To make a different variation of the default template style, check the default style's checkbox and press the Duplicate icon in the toolbar. Then edit the duplicate. |
| [Templates: Templates](https://docs.joomla.org/Help4.x:Templates:_Templates/en "Help4.x:Templates: Templates/en")    | The Template Manager: Templates screen allows you to preview and edit templates which are installed in your Joomla! installation.                                                                                                                                                                                                                                                        |
| [Templates: Customise](https://docs.joomla.org/Help4.x:Templates:_Customise/en "Help4.x:Templates: Customise/en")    | This is where you edit a template's source code. You can edit the template's master files and stylesheets from this screen.                                                                                                                                                                                                                                                              |
| <a                                                                                                                   
 href="https://docs.joomla.org/index.php?title=Help4.x:Templates:_Customise_Source/en&amp;action=edit&amp;redlink=1"   
 class="new"                                                                                                           
 title="Help4.x:Templates: Customise Source/en (page does not exist)">Templates:                                       
 Customise Source</a>                                                                                                  | This screen is where the source code of template files is edited. It provides a plain text interface to edit the template files. HTML and PHP programming syntax is highlighted to make the source code files easier to read.                                                                                                                                                            |
