---
title: Payment plugins
weight: 180
---

Payment plugins are used in advance payment feature, you can enable advance payment in [the component's configuration](/configuration/advance-payment/) and in [back-end's deal form](/create-new-deal-in-back-end/).

There are 2 payment plugins available: PayPal and Stripe. These plugins are installed automatically by default. To find these plugins in Joomla!'s plugin list, you filter for `cmlivedeal` type.

![/images/payment_plugins.png](/images/payment_plugins.png)

## PayPal

![/images/payment_plugin_paypal.png](/images/payment_plugin_paypal.png)

* **Display Name**: Payment method name shown in checkout, default is `PayPal`.
* **PayPal Email**: Email which you want to receive payment.
* **Current**: Currency used in payment.
* **Environment**: Select `Sandbox` if you want to test with PayPal Sandbox, select `Live` if your site is live and receives real payment.
* **Seconds To Wait**: Seconds before user is redirected to PayPal website to complete payment.

## Stripe

![/images/payment_plugin_stripe.png](/images/payment_plugin_stripe.png)

* **Display Name**: Payment method name shown in checkout, default is `Stripe`.
* **Currency ISO Code**: The ISO code of the currency you use in payment. For example: USD, EUR...
* **Mode**: `Live` for receiving real payment, `Test` for testing with Stripes Test mode.
* **Live Mode's Secret Key**: Your Stripe's secret key for `Live` mode.
* **Test Mode's Secret Key**: Your Stripe's secret key for `Test` mode.