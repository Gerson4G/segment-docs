---
title: Using Segment with Google integrations
hidden: true
published: false
---

<!-- LR: 03/03/2021 - this page can serve as the home for the "everything about Google" doc we'd like to have someday -->

### Google ID prefixes

Your Measurement IDs might begin with one of several different prefixes which indicates the type of ID and what Google property you're running.

#### UA- prefix

Your global site tag is controlled by Google Analytics. The ID is your Google Analytics Measurement ID. To find the property associated with this ID, use the [account search feature](https://support.google.com/analytics/answer/6100731) in Google Analytics. If the property does not appear, you probably do not have access to it.

To add this number in Segment, go to the Google Analytics destination, then to **Settings > Configure ID > Measurement ID**.

#### G- prefix

Your global site tag is controlled by Google Analytics 4 (GA4). The ID is your Google Analytics Measurement ID.

To add this number to your Segment destination, go to the Google Analytics destination, then to **Settings > Configure ID >  App + Web Measurement ID.**


#### AW- prefix

Your global site tag is controlled by Google Ads. The numeric string following the AW prefix is your Google Ads Conversion ID.

To add this number to your Segment destination, go to the Google Ads destination, then to **Settings > Configure ID > Conversion ID**.

#### DC- prefix

Your global site tag is controlled by a Floodlight tag. The numeric string following DC is your Advertiser ID.

To add this number to your Segment destination, go to the Floodlight destination, then to **Settings> Configure ID > App + Web Measurement ID**.

#### Other prefix not listed

Your global site tag is controlled by a different Google product or may be implemented incorrectly. Use the [Tag Assistant extension](https://support.google.com/tagassistant/answer/2947093) for Google Chrome to verify.

