---
title: CM Live Deal Search module
weight: 140
---
To configure your Search module, you go to System -> Site Modules (under Manage section)

![/images/module_menu.png](/images/module_menu.png)

Joomla! creates a new module for you automatically after you install the package of CM Live Deal. You can see CM Live Deal - Search module in your module list.

![/images/module_list_search.png](/images/module_list_search.png)

Click on the module name to edit its settings. You can give the module a new name by modifying “Title” field. In the “Module” tab, you set “Status” to “Published” and select the position you want to put this module in “Position” option.

![/images/mod_cmlivedeal_search_tab_module.png](/images/mod_cmlivedeal_search_tab_module.png)

In “Options” tab, you can configure the main settings of the module.

![/images/mod_cmlivedeal_search_tab_options.png](/images/mod_cmlivedeal_search_tab_options.png)

*   **Display**: How search form is displayed, there are 3 styles, “Inline”, “Horizontal”, “Vertical”. You can see how search form looks like in these styles in the screenshot below.
*   **Keyword field's CSS**: Custom CSS classes for keyword input field.
*   **Category list's CSS**: Custom CSS classes for category dropdown list.
*   **City list's CSS**: Custom CSS classes for city dropdown list.
*   **Search button's CSS**: Custom CSS classes for search button.
*   **Clear button's CSS**: Custom CSS classes for clear button.
*   **Display Clear button**: Display or hide clear button.
*   **Button's label**:
    *   _Use icon_: Use only icons for search and clear buttons.
    *   _Use text_: Use only text for search and clear buttons.
    *   _Use icon and text_: Use both icon and text for search and clear buttons.

CSS fields are useful if you want to customize the element of search form to match your template's style. This requires your skills in HTML and CSS.

In “Menu Assignment” tab, you configure what pages the module is displayed on.

![/images/mod_cmlivedeal_search_menu_assignment.png](/images/mod_cmlivedeal_search_menu_assignment.png)

After adjusting the settings, you can save the module and then you will receive “Module saved” message. If you change the module's name, you can see its name is updated in the module list.

![/images/mod_cmlivedeal_search_saved.png](/images/mod_cmlivedeal_search_saved.png)

You can check on your front-end to see if the module is displayed properly. The below screenshot is how the inline search form is displayed in "sidebar-right" positon of Joomla!'s‘ default Cassiopeia template.

![/images/mod_cmlivedeal_search_frontend.png](/images/mod_cmlivedeal_search_frontend.png)

**Examples** (the settings on the left side, the result on the right side)

Example of how inline search form is displayed. The Clear button is displayed and the buttons have only icons. The keyword field is customized by using “form-control-sm” class of Bootstrap 5.

![/images/mod_cmlivedeal_search_inline.png](/images/mod_cmlivedeal_search_inline.png)

Example of how vertical search form is displayed. The Clear button is displayed and is customized by “btn-light class of Boostrap 5. The Search button is customized by “btn-success” class of Bootstrap 5. Icon and text are both used in the buttons. The keyword field is customized by using “form-control-sm" class of Bootstrap 5.

![/images/mod_cmlivedeal_search_vertical.png](/images/mod_cmlivedeal_search_vertical.png)