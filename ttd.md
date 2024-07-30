# TTD

MadConnect supports adding your data to first-party data segments in The Trade Desk. Enhance your The Trade Desk platform with real-time data directly from your data sources. Keeping your data&#x20;

| CONNECTOR TYPE | DATA TYPE | CONNECTOR                | DESCRIPTION                                                                 | SUPPORTED ACTIONS |
| -------------- | --------- | ------------------------ | --------------------------------------------------------------------------- | ----------------- |
| Destination    | Audience  | First Party Data (UID2s) | Sync your first-party IDs (UID2, RampID) from any source to The Trade Desk. | Add               |

Prerequisites:

* Connect with your TTD representative for any paperwork needed for audience activation.
* Ensure that the Segment IDs being used exist in your TTD account. If not, create the Segment and communicate the Segment ID to the data provider.

To send data to your first-party data segments using MadConnect, you will need the following to authenticate:

* Advertiser ID
* Advertiser Secret Key

You can obtain your decoded advertiser secret key for uploading first-party data from your advertiser preferences page in The Trade Desk UI; Advertiser Preferences > Seat Identifiers & Keys. If you can't find your secret key, contact your Account Manager. When you send data, the included secret key is validated against the secret key the platform has on file for the Advertiser ID.

For more information on the First Party Data API, please review [TTD documentation](broken-reference).
