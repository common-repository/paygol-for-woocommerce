=== Paygol for WooCommerce ===
Contributors: Paygol
Tags: paygol, woocommerce, payment, gateway, credit, card, credit card, webpay, tarjeta, paysafecard, oxxo, boleto, bitcoin, sms, shortcode, keyword, sms premium, sms billing, paygol, worldwide payments, e-commerce, ecommerce, mobile payments, pay by phone, pay by sms, pay per call
Requires at least: 3.7
Tested up to: 4.9.4
Requires PHP: 5.6
Stable tag: 1.3.3
License: GPLv2
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Paygol is an online payment service provider offering a wide variety of both worldwide and local payment methods.

== Description ==
This module allows you to integrate Paygol easily on your platform. Paygol is an online payment gateway that offers a wide array of both worldwide and local payment methods such as credit card, debit card, paysafecard, bank transfers, cash payments, SMS/call and more. More payment options and wider coverage makes the payment process more simple for your customers, at the same time it means more sales and higher revenue for you.

Additional information can be found at:
[https://www.paygol.com/en/](https://www.paygol.com/en/)
[https://www.paygol.com/en/pricing/](https://www.paygol.com/en/pricing)

== Testing ==
To test the newly installed module you can enable your service's test mode at the upper right screen of your dashboard, at Paygol's website. Be sure to change it back before going live.

== Important notes ==
- While in test mode, an IPN request (payment notification to your platform) will be issued immediately after each test.
- Payments are usually notified immediately; however, certain payment methods may take longer to confirm the payment (e.g. methods that take a few minutes to notify the transaction, or voucher-based transactions that require the payer to print it in order to pay by cash at a given place). In these cases the product is shown as "Pending payment", and only once it's confirmed by the provider will it show as "Processing" (Wich it means that order is paid and waiting to be shipped). We strongly recommend that you inform your customers about this beforehand in order to avoid confusions.

== Installation ==
- You'll need a working WordPress installation using the WooCommerce plugin (tested on versions 2.3.0 up to 3.3.2).
- Log into your WooCommerce admin dashboard.
- There's 3 ways to install our plugin:
* Go to "Plugins -> Add new", type on "paygol for woocommerce" in the "Search plugin" field and press "Install Now". (RECOMMENDED)
* Download the plugin from the [Official WordPress Plugins page](https://wordpress.org/plugins/paygol-for-woocommerce/), click "Upload plugin", select the file from your computer and press "Install Now".
* Download the plugin from the [Official WordPress Plugins page](https://wordpress.org/plugins/paygol-for-woocommerce/), open your FTP and extract the plugin's folder into wp-content/plugins/.
- Go to "Plugins -> Installed Plugins" look for "Paygol plugin for Woocommerce" and press "Activate".
- Go to "WooCommerce->Settings->Checkout->Paygol" then log into your Paygol Dashboard and go to "Notifications" section, copy the Service ID and Secret Key from your account and paste them into the corresponding fields at the module's setup page on your WooCommerce.
- Copy the "Payments notification URL (IPN)" from your Paygol's module setup and paste it into the "IPN URL" field at the "Notifications" section of your Paygol dashboard, then save the changes.
- Click on "Save Changes" in your WooCommerce site.

== Changelog ==
= 1.3.3 =
* New release, tested with WordPress 3.7.0 up to 4.9.4 and WooCommerce 2.3.0 up to 3.2.3
* Security and Bug fixes.

= 1.3.2 =
* New release, tested with WordPress 3.7.0 up to 4.8.3, and WooCommerce 2.3.0 up to 3.2.3
* Security and Bug fixes.

= 1.3.1 =
* Bug fixes.

= 1.3 =
* New release, tested with WordPress 3.7.0 up to 4.7.5, and WooCommerce 2.3.0 up to 3.0.7
* Added validation for payment notifications.

= 1.2 =
* New release, tested with WordPress 3.7.0 up to 4.7.3, and WooCommerce 2.3.0 up to 2.6.14.
* Updated with new logo.
                                                                
= 1.1 =
* New release, tested with WordPress 3.7.0 up to 4.6.1, and WooCommerce 2.3.0 up to 2.6.7.

= 1.0 =
* Initial release.