#  Background

This repo contains the custom-made footers for cyclio's marketing efforts with Mailchimp.

With our previous marketing campaigns, we found that the built-in footers that Mailchimp provides lack customization abilities. The six different footers in this repo cover our three main marketing purposes in both Deutsch and English.

# Purposes

## 1. Standard Footer
### file names: footer_basic_EN.html, footer_basic_DE.html

These footers will be applied for all standard emails and marketing campaigns.

## 2. Newsletter Footer
### file names: footer_newsletter_EN.html, footer_newsletter_DE.html

These footers will be applied for all newsletters. Unlike the standard footer, these footers include two features:

- Links to the Google Play and Apple App Stores: _Please note that as our current app is in beta and only available with TestFlight, this feature has been disabled and left as comments._
- A link at the bottom to unsubscribe.

## 3. Service Footer
### file names: footer_service_EN.html, footer_newsletter_DE.html

These footers will be applied for all "service" emails. Like the newsletter footer, an unsubscribe button is included. However, there is no potential App Store/Google Play Store button in the HTML code.

# Configuration and Installation

To use these headers, you will need to either download the HTML files or copy the code and paste into Mailchimp. To do this, you will need to log into Mailchimp and create a new email template. Once you scroll to the bottom, you will see options to either upload external HTML code or paste it. Choose the option that works best for you.

# styles.css warning

There is a styles.css file in this repository. Please note that due to Mailchimp's limits with importing code, the file has no true functionality. However, please not that it is very useful for reference. If you wish to make individual editing efforts, please note that modifying the *styles.css* file will not make any changes to any of the footers 
