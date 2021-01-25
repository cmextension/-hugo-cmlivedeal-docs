---
title: Deal detail
weight: 50
---
There are 2 styles of deal detail which you can configure in [Deal](/configuration/deal/) section in Configuration:

*   Popup:

![/images/deal_detail_popup.png](/images/deal_detail_popup.png)

*   Separate detail page:

![/images/deal_detail_page.png](/images/deal_detail_page.png)

There is a menu item for deal detail page but it is optional. If you create this menu item (as a hidden menu item), its alias will be used for deal detail page. But if this menu item doesn’t exist, your deal list’s alias will be used instead.

For example, if your deal list’s URL is www.yoursite.com/deal-list and you don’t create menu item for deal detail page, your deal URL could look like:

www.yoursite.com/deal-list/1-50-off-cocktails-and-2-tacos-at-rocks-lakeview-s-tuesday-specials

But if you create menu item for deal detail page with alias “deal”, your deal URL would be

www.yoursite.com/deal/1-50-off-cocktails-and-2-tacos-at-rocks-lakeview-s-tuesday-specials

The benefit of creating a separate menu item for deal detail page is you can assign different modules to detail page or not showing specific modules in deal detail page. By using deal list’s menu item, all modules in deal list page will be displayed in deal detail page.