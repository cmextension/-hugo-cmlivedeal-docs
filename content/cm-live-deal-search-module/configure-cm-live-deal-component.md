---
title: Configure CM Live Deal component
weight: 30
---
In your Joomla! back-end you go to Components -> CM Live Deal.

![/images/com_cmlivedeal_menu.jpg](/images/com_cmlivedeal_menu.jpg)

On the toolbar, you click “Options” button.

![/images/com_cmlivedeal_dashboard.jpg](/images/com_cmlivedeal_dashboard.jpg)

Go to “Deal” tab, you select the Geolocatin service, set the radius (in kilometer) to search for nearby deals from user’s location and set the cookie lifetime.

![/images/com_cmlivedeal_deal.jpg](/images/com_cmlivedeal_deal.jpg)

*   **Geolocation service**: The service you use to detect user’s location.
*   **Search radius from user’s location**: The radius in kilometer to search for nearby deals of user. Default is 5 kilometers. This value is used when user searches for deals in his/her location by using the search module.
*   **Location cookie’s lifetime**: Detect user’s location requires reading the database file and make the server slow. User’s location can be stored in cookie and reused later to reduce file reads from server. With this option you can set how many days this cookie is available. Default value is 7 (days). You can disable storing cookie by using 0 value.