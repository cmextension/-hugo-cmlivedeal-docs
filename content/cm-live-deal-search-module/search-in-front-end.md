---
title:  Search in front-end
weight: 50
---
Go to your front-end where the search module is displayed. Now if you select “Your location” in the city list and search, you will get the deals near you in the result.

![/images/search_dropdown.png](/images/search_dropdown.png)

If the database file doesn't exist, this function doesn't work.

If your location can not be detected (not in MaxMind's database), you will see the error message “We can't detect your current location.”.

Please remember to choose a Geolocation Service to detect user's location. You can choose it in CMLiveDeals's configuration, under 'General' tab.