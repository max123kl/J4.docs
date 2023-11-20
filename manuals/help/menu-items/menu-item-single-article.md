---
sidebar_position: 31
id: menu-item-single-article
title: "Help4.x:Menu Item: Single Article"
---
## Description

The Single Article menu item type is used to show one article in the
Frontend of the site.

## How To Access

**Menus **→** \[name of the menu\]**

To add a Menu Item:

1.  click the **New** toolbar button.
2.  click the Menu Item Type **Select** button.
3.  select the **Articles** item.
4.  select the **Single Article** item.

To edit a Menu Item:

- select a **Title** from the list

## Screenshot

<img
src="https://docs.joomla.org/images/thumb/d/df/Help-4x-Menus-Item-Articles-Single-Article-screen-en.png/800px-Help-4x-Menus-Item-Articles-Single-Article-screen-en.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/d/df/Help-4x-Menus-Item-Articles-Single-Article-screen-en.png/1200px-Help-4x-Menus-Item-Articles-Single-Article-screen-en.png 1.5x, https://docs.joomla.org/images/thumb/d/df/Help-4x-Menus-Item-Articles-Single-Article-screen-en.png/1600px-Help-4x-Menus-Item-Articles-Single-Article-screen-en.png 2x"
data-file-width="2880" data-file-height="1260" width="800" height="350"
alt="Help-4x-Menus-Item-Articles-Single-Article-screen-en.png" />

## Form Fields

- **Title**. The title that will display for this menu item.
- **Alias**. The internal name of the menu item. Normally, you can leave
  this blank and Joomla will fill in a default value Title in lower case
  and with dashes instead of spaces. [Learn
  more.](https://docs.joomla.org/Alias/en "Alias/en")

### Details

**Left Panel**

- **Menu Item Type**. The Menu Item Type selected when this menu item
  was created. This can be one of the core menu item types or a menu
  item type provided by an installed extension.
- **Select Article**. This field holds the article to be shown in the
  menu item. Press the **Select/Change** button to open the article
  selection window.This screen is similar to the
  [Articles](https://docs.joomla.org/Help4.x:Articles/en "Help4.x:Articles/en")
  page. You can use the Filter fields to find the desired article and
  then click on the article's Title to select it. At that point, the
  modal window will close and the title will show in the Select Article
  field.
- **Link**. The system-generated link for this menu item. This field
  cannot be changed and is for information only.
- **Target Window**. Select from the dropdown list.
- **Template Style**. Select from the dropdown list.

**Right Panel**

- **Menu**. Shows which menu the link will appear in.

### Options

The Options determine how the article will show on the Frontend Site
layout.

<img
src="https://docs.joomla.org/images/thumb/c/c4/Help-4x-Menus-Item-Articles-Single-Article-options-subscreen-en.png/600px-Help-4x-Menus-Item-Articles-Single-Article-options-subscreen-en.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/c/c4/Help-4x-Menus-Item-Articles-Single-Article-options-subscreen-en.png/900px-Help-4x-Menus-Item-Articles-Single-Article-options-subscreen-en.png 1.5x, https://docs.joomla.org/images/thumb/c/c4/Help-4x-Menus-Item-Articles-Single-Article-options-subscreen-en.png/1200px-Help-4x-Menus-Item-Articles-Single-Article-options-subscreen-en.png 2x"
data-file-width="2880" data-file-height="1340" width="600" height="279"
alt="Help-4x-Menus-Item-Articles-Single-Article-options-subscreen-en.png" />

Note: Options include "**Use Global**". If this is selected, the setting
from the [Articles:
Options](https://docs.joomla.org/Help4.x:Articles:_Options/en "Help4.x:Articles: Options/en")
will be used.

**Layout**

- **Title**. Show the Article's Title.
- **Linked Titles**. Show the title as a link to the article.
- **Intro Text**.
  - Show: The Intro Text of the article will show when you drill down to
    the article.
  - Hide: Only the part of the article after the Read More break will
    show.
- **Position of Article Info**.
  - Above: Puts the article information block above the text.
  - Below: Puts the article information block below the text.
  - Split: Splits the article information block into 2 separate blocks.
    One block is above and the other is below the text.
- **Article Info Title**. Displays 'Details' on top of the article
  information block.

**Category**

- **Category**. Show the Article's Category Title.
- **Link Category**. Show the title as a link to that Category.Note: You
  can set this to be either a blog or list layout with the [Choose a
  Layout](https://docs.joomla.org/Help4.x:Articles:_Options/en#choosealayout "Help4.x:Articles: Options/en")
  option in the Category Tab.
- **Parent Category**. Show the Article's Parent Category Title.
- **Link Parent Category**. Show the title as a link to that
  Category.Note: You can set this to be either a blog or list layout
  with the [Choose a
  Layout](https://docs.joomla.org/Help4.x:Articles:_Options/en#choosealayout "Help4.x:Articles: Options/en")
  option in the Category Tab.

**Associations**

- **Associations**. Show the associated flags or Language Code.
  [Multilingual
  only.](https://docs.joomla.org/Help4.x:Multilingual_Associations/en "Help4.x:Multilingual Associations/en")

**Author**

- **Author**. Show the author of the Article.
- **Link to Author's Contact Page**. Show it as a link to a Contact
  layout for that author.Note: The author must be set up as a
  [Contact](https://docs.joomla.org/Help4.x:Contacts:_Edit/en "Help4.x:Contacts: Edit/en").
  Also, a link will not show if there is an [Author
  Alias](https://docs.joomla.org/Help4.x:Articles:_Edit/en#createdbyalias "Help4.x:Articles: Edit/en")
  value for the article.

**Date**

- **Create Date**. Show the Article's create date.
- **Modify Date**. Show the Article's modify date.
- **Publish Date**. Show the Article's start publishing date.

**Options**

- **Navigation**. Show a navigation link 'Prev' or 'Next' when you drill
  down to the article.
- **Hits**. Show the number of times the article has been displayed by a
  user.
- **Tags**. Show the tags for each article.
- **Unauthorised Links**.
  - Yes: The Intro Text for restricted articles will show. Clicking on
    the Read more link will require users to log in to view the full
    article content.
  - No: Articles that the user is not authorised to view (based on the
    viewing access level for the article) will not show.
- **Positioning of the Links**.
  - Above: Links are shown above the content.
  - Below: Links are shown below the content.

### Common Options

See [Menus: New
Item](https://docs.joomla.org/Help4.x:Menu_Item:_New_Item/en "Help4.x:Menu Item: New Item/en")
for help on fields common to all Menu Item types, including:

- [Right
  Panel](https://docs.joomla.org/Help4.x:Menu_Item:_New_Item/en#rightpanel "Help4.x:Menu Item: New Item/en")
- [Link
  Type](https://docs.joomla.org/Help4.x:Menu_Item:_New_Item/en#linktype "Help4.x:Menu Item: New Item/en")
- [Page
  Display](https://docs.joomla.org/Help4.x:Menu_Item:_New_Item/en#pagedisplay "Help4.x:Menu Item: New Item/en")
- [Metadata](https://docs.joomla.org/Help4.x:Menu_Item:_New_Item/en#metadata "Help4.x:Menu Item: New Item/en")
- [Associations](https://docs.joomla.org/Help4.x:Menu_Item:_New_Item/en#associations "Help4.x:Menu Item: New Item/en")
- [Module
  Assignment](https://docs.joomla.org/Help4.x:Menu_Item:_New_Item/en#moduleassignment "Help4.x:Menu Item: New Item/en")

## Toolbar

At the top of the page you will see the toolbar shown in the
[Screenshot](#screenshot) above.

- **Save**. Saves the menu item and stays in the current screen.
- **Save & Close**. Saves the menu item and closes the current screen.
  - **Save & New**. Saves the menu item and keeps the editing screen
    open and ready to create another menu item.
- **Cancel**. Closes the current screen and returns to the previous
  screen without saving any modifications you may have made.
- **Help**. Opens this help screen.

## Quick Tips

- If you have a Single Article Layout defined for an article, that
  layout will show any time a user drills down to that article. For
  example, if an article is shown on another menu item type (for
  example, in a Category Blog or List Layout or a Featured Articles
  Layout), the user will be taken to the Single Article Layout for that
  article (if defined).
- Archived articles are no longer published but are still stored on the
  site. Articles are Archived using the Articles screen. Note that
  Articles assigned to the 'Uncategorised' Section will not show on the
  Archived Article List layout.

## Related Information

- This
  [Portal](https://docs.joomla.org/Portal:Joomla_4/en "Portal:Joomla 4/en")
  brings together information related specifically to Joomla 4.

|                                                                                                                                                                         |                                                                                                                                                                                             |
|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Related Help Screens                                                                                                                                                    | Description                                                                                                                                                                                 |
| [Articles: Options](https://docs.joomla.org/Help4.x:Articles:_Options/en "Help4.x:Articles: Options/en")                                                                | Used to set global defaults for menu items that display articles. These default values will be used when 'Use Global' is selected for an option in an Articles menu item.                   |
| [Articles](https://docs.joomla.org/Help4.x:Articles/en "Help4.x:Articles/en")                                                                                           | The Article list is used to find, mark featured, add and edit articles.                                                                                                                     |
| [Articles: Edit](https://docs.joomla.org/Help4.x:Articles:_Edit/en "Help4.x:Articles: Edit/en")                                                                         | This is where you can add and edit Articles. You can also select the Category for an Article and indicate whether or not it is Published and if it is selected to appear on the Front Page. |
| [Articles: Featured](https://docs.joomla.org/Help4.x:Articles:_Featured/en "Help4.x:Articles: Featured/en")                                                             | Used to control which 'Featured Articles' are displayed on the Front Page and in what order they are displayed.                                                                             |
| [Articles: Categories](https://docs.joomla.org/Help4.x:Articles:_Categories/en "Help4.x:Articles: Categories/en")                                                       | The Articles Categories list is used to find, add, and edit articles categories.                                                                                                            |
| [Menus: Archived Articles](https://docs.joomla.org/Help4.x:Menu_Item:_Article_Archived/en "Help4.x:Menu Item: Article Archived/en")                                     | Shows a customised list of articles ordered by date or title. Archived articles are no longer published but are still stored on the site.                                                   |
| [Menus: Category Blog](https://docs.joomla.org/Help4.x:Menu_Item:_Category_Blog/en "Help4.x:Menu Item: Category Blog/en")                                               | Used to show articles belonging to a specific Category in a blog layout. Controls the Leading Articles, Intro Articles and additional links to more Articles.                               |
| [Menus: Category List](https://docs.joomla.org/Help4.x:Menu_Item:_Category_List/en "Help4.x:Menu Item: Category List/en")                                               | Used to show articles belonging to a specific Category in a list layout.                                                                                                                    |
| [Menus: Create Article](https://docs.joomla.org/Help4.x:Menu_Item:_Create_Article/en "Help4.x:Menu Item: Create Article/en")                                            | Allows users to submit an article. Normally this is available only to users who have logged in to the Frontend of the site. Users must have permission to create articles.                  |
| [Menus: Featured Articles](https://docs.joomla.org/Help4.x:Menu_Item:_Featured_Articles/en "Help4.x:Menu Item: Featured Articles/en")                                   | Used to show all Articles that have been tagged as Featured. Articles are shown in a Blog Layout.                                                                                           |
| [Menus: List All Categories in an Article Category Tree](https://docs.joomla.org/Help4.x:Menu_Item:_List_All_Categories/en "Help4.x:Menu Item: List All Categories/en") | Used to show a hierarchical list of Categories. Depending on the selected options for this layout, you can click on a category Title to show the articles in that category.                 |
| <span class="mw-selflink selflink">Menus: Single Article</span>                                                                                                         | Used to show one article.                                                                                                                                                                   |
