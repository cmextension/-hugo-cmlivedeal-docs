---
title: Get GeoLite2 City database
weight: 20
---
GeoLite2 City is required to detect user’s location. Because the database file’s size is big, we don’t include it in CM Live Deal’s package, you need to download it from MaxMind website then upload it to your server manually.

Go to [http://dev.maxmind.com/geoip/geoip2/geolite2/](http://dev.maxmind.com/geoip/geoip2/geolite2/), download the gzipped binary file of GeoLite2 City.

![/images/maxmind.jpg](/images/maxmind.jpg)

Use your favorite file compression software to uncompress the downloaded file, then you get the file GeoLite2-City.mmdb, upload this file to <Joomla! root folder>/administrator/components/com\_cmlivedeal/helpers/geoip/database/ folder.