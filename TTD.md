

<!-- Start of embedded HTML -->
<div style="width:80%; margin: 0 auto">
    <p>
        MadConnect supports adding your data to first-party data segments in The Trade Desk. Enhance your The Trade
        Desk platform with real-time data directly from your data sources. Keeping your data current empowers your
        team to deliver exceptional advertising experiences. Leverage the full potential of The Trade Desk for
        audience activation through the First-Party Data API,
        ensuring your campaigns are always optimized and effectively targeted.
    </p>
</div>
<div style="width:80%; margin: 30px auto">
    <table style="width:100% ; border-collapse: collapse;">
        <tr>
            <td style="border-top: none; border-left: none;">CONNECTOR TYPE</td>
            <td style="border-top: none;">DATA TYPE </td>
            <td style="border-top: none;">CONNECTOR</td>
            <td style="border-top: none;">DESCRIPTION</td>
            <td style="border-top: none; border-right: none;">SUPPORTED ACTIONS</td>
        </tr>
        <tr>
            <td style="border-bottom: none; border-left: none;">Destination</td>
            <td style="border-bottom: none;">Audience</td>
            <td style="border-bottom: none;">First Party Data (UID2s)</td>
            <td style="border-bottom: none;">Sync your first-party IDs (UID2, RampID) from any source to The Trade Desk.</td>
            <td style="border-bottom: none;border-right: none;">Add</td>
        </tr>
    </table>
</div>
<div style="width:80%; margin: 0 auto">
    <p className="prerequisites" style="font-size: 16px; font-family: Sans-serif;letter-spacing: 0.8px; font-weight: 100; color:rgb(41, 41, 41)">
        Prerequisites:
    </p>
    <ul>
        <li>Connect with your TTD representative for any paperwork needed for audience activation.</li>
        <li>Ensure that the Segment IDs being used exist in your TTD account. If not, create the Segment and communicate the Segment ID to the data provider.</li>
    </ul>
    <p>To send data to your first-party data segments using MadConnect, you will need the following to authenticate:</p>
    <ul>
        <li>Advertiser ID</li>
        <li>Advertiser Secret Key</li>
    </ul>
</div>
<div style="width:80%; margin: 10px auto">
    <p>You can obtain your decoded advertiser secret key for uploading first-party data from your advertiser preferences page in The Trade Desk UI; Advertiser Preferences > Seat Identifiers & Keys. If you can't find your secret key, contact your Account Manager. When you send data, the included secret key is validated against the secret key the platform has on file for the Advertiser ID.</p>
    <p style="margin-bottom: 100px;">For more information on the First Party Data API, please review <a href="#">TTD documentation</a>.</p>
</div>
<!-- End of embedded HTML -->
