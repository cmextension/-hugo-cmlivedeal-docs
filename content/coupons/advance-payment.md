---
title: Advance payment
weight: 30
---

When you enable advance payment in [configuration](/configuration/advance-payment/) and in [the deals you create in back-end](/create-new-deal-in-back-end/), users need to pay to get the coupons of these deals.

Amount to pay is visible in deal list

![/images/advance_payment_deal_list.png](/images/advance_payment_deal_list.png)

and deal detail page.

![/images/advance_payment_deal_detail.png](/images/advance_payment_deal_detail.png)

To receive payment, you need to [enable and configure payment plugins](/configuration/payment-plugins).

When checkout, user needs to complete the checkout form with billing info and payment method, then uuser is taken to the selected payment method's website to complete the payment.

![/images/advance_payment_checkout.png](/images/advance_payment_checkout.png)

After the payment is completed, user is redirected back to the site, the coupon is available immediately with Stripe payment or after a few seconds with PayPal payment method.