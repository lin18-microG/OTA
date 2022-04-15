April 15th, 2022

- Security string 2022-04-05
- Some kernel patches
- Bromite Browser and Webview on 100.0.4896.57


March 15th, 2022

- Bromite Browser and Webview on 99.0.4844.58 (bugfix build)


March 12th, 2022

- Security string 2022-03-05
- Some kernel patches
- Bromite Browser and Webview on 99.0.4844.55
- microG 0.2.24.214816-2
- AuroraStore 4.1.1

Janaury 20th, 2020

- Security string 2022-01-05
- Some kernel patches
- A couple of patches and fixes from LineageOS


December 19th, 2021

- Security String 2021-12-05
- Bromite System Webview and Browser on 96.0.4664.54
- microG 0.22.214516-21


November 13th, 2021

- Security string 2021-11-05
- Bromite Webview and Browser on 94.0.4606.109


October 15th, 2021
Initial build:

-  Security string 2021-10-01
-  AOSP tag 11.0.0_r46
-  Pre-installed microG (0.2.22.212658-2) like LineageOS for microG project (own fork)
-  Pre-installed AuroraStore (4.0.7), AuroraDroid (1.0.8) and AuroraServices (1.1.1)
-  OTA Support
-  eSpeakTTS engine
-  Bromite (93.0.4577.83) as default browser
-  Additional security hardening features listed below:
-  Cloudflare as default DNS (instead of Google)
-  Privacy-preferred default settings
-  Optional blocking of Facebook- and Google-Tracking (Settings - Network & Internet)
-  Optional disable captive portal detection or choose from various providers (default is GrapheneOS and not Google; Settings - Network & Internet)
-  Firewall UI (under Trust)
-  Increased max. password length of 64
-  No submission of IMSI/phone number to Google when GPS is in use
-  Default hosts file with many blocked ad/tracking sites
-  Privacy-enhanced Bromite SystemWebView (93.0.4577.83)
-  Extra control of sensor access for additionally installed user apps (Special access under app permissions)
-  Debloated from Oneplus blobs for Soter and IFAA
-  Hardened bionic lib and constified JNI method tables
-  Option to only use fingerprint unlock for apps and not for the device
-  Optional timeout for Bluetooth and WLAN connections
-  Per connection WiFi randomization option
