---
title: Submit new deal
weight: 20
---
To submit new deal in front end, you need to have permission to do this. Please read [HERE](/configuration/permissions/)

In deal list, merchant can click “New deal” button to submit a new deal.

The form has the following fields:

*   **Title**: The deal’s name.
*   **Category**: The category which the deal is in.
*   **Image**: Merchant can click “Select” button to open a popup and select an uploaded image, merchant can also upload a new image.
*   **Discount info**: Similar to the deal submission form in back-end, this option provides 3 types of discount, if the deal has a different discount info you can select “None” option. This field only appear if “Prices and discount input” option is enabled in the component’s configuration
    *   Original price and discounted price. For example: original price was $50 but now discounted price is $30.
    *   Fixed discount value. For example: $10 discount for orders over $50.
    *   Fixed discount percent. For example: 10% discount for orders over $50.
*   **Description**: The deal’s description.
*   **Fine print**: The deal’s terms and conditions.
*   **Coupon quantity**: This field is only visible if “Limit coupon quantity” in the component’s configuration is enabled. You can enter the quantity of how many coupon you want customers to get, if you want unlimited quantity you can enter “0”.
*   **Starting time**: When the deal starts public to users.
*   **Ending time**: When the deal expires and is not visible to users any more.
*   **Published**: Deal’s published status.

![/images/deal_frontend_form.png](/images/deal_frontend_form.png)

You will receive message “Item successfully submitted.” if deal is saved successfully.

![/images/deal_frontend_merchant_list_saved.png](/images/deal_frontend_merchant_list_saved.png)
