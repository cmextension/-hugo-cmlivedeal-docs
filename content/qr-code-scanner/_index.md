---
title: QR code scanner
weight: 220
---

CM Live Deal has 2 QR code readers, one for merchant and another one for customer. These QR code scanners are disabled by default, you can enable and configure them in [the configuration](/configuration/coupon/).

You can create the menu items for the QR code scanners by using the menu item types `Customer QR Code Scanner` and `Merchant QR Code Scanner`.

![/images/qr_code_scanner_menu_item.png](/images/qr_code_scanner_menu_item.png)

Joomla! is a web application and is accessed via web browser, when you access the QR code scanner your web browser asks you permission to access your device's camera, you need to give your browser this permission.

![/images/qr_code_scanner_permission.png](/images/qr_code_scanner_permission.png)

After merchant scans a coupon and the coupon is not found, a message modal appears to notify the merchant; if the coupon is found, a modal with coupon info is shown, merchant can redeems the coupon if it is not redeemed yet, or cancels its redemption if it is already redeemed.

![/images/qr_code_scanner_coupon_modal.png](/images/qr_code_scanner_coupon_modal.png)