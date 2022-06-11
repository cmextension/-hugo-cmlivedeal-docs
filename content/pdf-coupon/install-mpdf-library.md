---
title: Install mPDF library
weight: 20
---
Because the package is about 47MB, so if your server allows to upload more than 47MB you can install this package via Extension Manager just like installing any other Joomla! extension. However if you can't install by using `Upload Package File` option, you can use `Install from Directory` option. The following instruction is for installing via `Install from Directory` option.

First you need to log into your hosting's control panel, access file manager tool, go the `tmp` folder in your Joomla! root folder, the below screenshots are the file manager of CPanel which is popular and is used by many hosting providers.

![/images/mpdf_tmp.jpg](/images/mpdf_tmp.jpg)

You upload the mPDF package into this `tmp` folder. In the below screenshots, the package is named `mpdf.zip`.

![/images/mpdf_uploaded.jpg](/images/mpdf_uploaded.jpg)

You can use any ZIP extracting tool available in the file manager to extract the filer. In CPanel, you select the file and click `Extract` button on the toolbar. The result is `mpdf` folder.

![/images/mpdf_extracted.jpg](/images/mpdf_extracted.jpg)

In Joomla!'s Extension Manager, you switch to `Install from Directory` tab and enter the path the `mpdf` folder. If your `tmp` folder is `/home/username/joomla/tmp` then the path to `mpdf` folder should be `/home/username/joomla/tmp/mpdf`.

![/images/mpdf_install.jpg](/images/mpdf_install.jpg)

Click `Install` button the library will be installed, you will get the successful message in the next page.

![/images/mpdf_success.jpg](/images/mpdf_success.jpg)

Now mPDF library is installed, you can delete `mpdf.zip` file and `mpdf` folder in your `tmp` folder.