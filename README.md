# AdblockerForTwitch

How does it work?

The extension works by finding an ad-free stream source and replacing the ad with the ad-free version. The ad-free version will be limited to 480p, this is the best we can get. Once the ad is finished, the stream will automatically revert to the original video quality.

Ads will be blocked for pre-rolls and mid-rolls and also on VOD's. We also block third party trackers.

No personal information is needed or collected. 

Any donations are very much welcome, as we do pay server costs to make this work.
You can donate via Paypal at https://www.paypal.com/paypalme/ttvadblock

The code is licensed under the GPL-3.0 license and is based on https://github.com/cleanlock/VideoAdBlockForTwitch by cleanlock.

# FireFox
- Download `firefox` directory from github
- Open up Firefox and in your Web Browser URL, enter: `about:debugging#/runtime/this-firefox`
- Click `Load Temporary Add-on`
- Select the `firefox` directory then any file in that directory

# Chrome 
- Download `chrome` directory from github
- Open up Chrome and in your Web Browser URL, enter: `achrome://extensions`
- Enable the `Developer Mode` toggle, found in the top right of this view (typically) of the extensions page in your browser
- Click `Load unpacked Extension`
- Select the `chrome` directory

# Latest Changes:

- Made changes to playertypes and fallbacks, to get the code working again.
