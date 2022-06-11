---
title: Coupon
weight: 100
---

![/images/com_cmlivedeal_coupon.png](/images/com_cmlivedeal_coupon.png)

*   **Coupon code's length**: The number of characters in a coupon code. Default value is 5.
*   **Coupon's characters**: The character's types in coupon code. Default is alphanumeric. Coupon code's characters are always uppercase.
    *   _Latin alphabetic characters only (from A to Z)_: for example, `GWLCA`.
    *   _Latin numeric characters only (from 0 to 9)_: for example, `83061`.
    *   _Latin alphabetic and numeric_: for example, `F52H2`.
*   **Coupon format**:
    *   _HTML_: Coupon in HTML format (a web page).
    *   _PDF_: Coupon in PDF format. You need to install mPDF library package. Please view [PDF coupon](pdfcoupon.html#ref-pdfcoupon) section for more information.
*   **QR code's size**: The size of coupon's QR code in pixel.
*   **Guest can get coupon**: Allow guests can capture coupons without registering accounts.
*   **Limit coupon quantity**: Enable this option to give administrators and merchants ability to set and change coupon quantity for every deal. If this option is disabled, coupon quantity is unlimited.
*   **Limit 1 coupon per registered user**: Enable this option if you only allow a registered user to get 1 coupon for 1 deal. Disable this option if you want to allow registered users to get unlimited coupon for every deal.
*   **Merchant's QR code scanner**: This QR code scanner helps merchants find and redeem coupon code quickly by scanning customer's QR code.
*   **Quantity of recent scanned coupon**: Recent scanned coupons are kept in session and shown next to the QR code scanner, this option lets you configure how many coupons are shown.
*   **Customer's QR code scanner**: The QR code scanner for customer lets customers redeem their coupons by themselves, as soon as coupon is scanned and found, it is marked as redeemed.
*   **Prefix for customer's QR code scanner**: Custom HTML shown above customer's QR code scanner. You can use to show title and instruction.
*   **Postfix for customer's QR code scanner**: Custom HTML shown below customer's QR code scanner. You can use to show instruction, privacy info, etc...
*   **Component view for customer's QR code scanner**: When component view is enabled, only CM Live Deal's content is shown on the page, other elements outside of CM Live Deal like menus, modules,... are hidden.
*   **Auto close customer QR code's modal (in seconds)**: After scanning QR code, a modal appears to let customer know that the coupon code is valid or not, this option lets you set up how long the modal is shown.
