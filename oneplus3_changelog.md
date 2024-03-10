March 2024

- Custom build release 2024-03-01
- Some kernel patches
- Mulch System Webview 122.0.6261.105


February 2024

- ASB Security string 2024-02-05
- Some kernel patches
- AuroraStore 4.4.1
- Mulch System Webview 121.0.6167.164


January 2024

- ASB Security string 2024-01-05
- Some kernel patches
- Mulch System Webview 120.0.6099.193


December 2023

- ASB Security string 2023-12-05
- Some kernel patches
- Mulch System Webview 120.0.6099.115


November 2023

- ASB Security string 2023-11-05
- Some kernel patches
- AuroraStore 4.3.5
- microG and companion (aka Fakestore) 0.3.0.233515
- Mulch System Webview 119.0.6045.134


October 2023

- ASB Security string 2023-10-05
- Some kernel patches
- AuroraStore 4.3.2
- Fixes for CVE-2023-4863 and CVE-2023-5217
- microG 0.2.29.233013
- Mulch System Webview 118.0.5993.65


September 13th, 2023

- ASB Security string 2023-09-05
- Some kernel patches
- Slightly hardened GPS config
- Updated CA certificates
- AuroraStore 4.3.1
- Mulch Webview 117.0.5938.60


August 10th, 2023

- ASB Security string 2023-08-05
- Some kernel patches
- Mulch Webview 115.0.5790.136


July 9th, 2023 

- ASB Security string 2023-07-05
- Some kernel patches
- Mulch Webview 114.0.5735.196
- microG 0.2.28.231657 - "Original" included now


June 8th, 2023

- ASB Security string 2023-06-05
- Some kernel patches
- Mulch Webview 114.0.5735.61
- microG on 0.2.28.231657-5
- FakeStore 0.2.0
- AuroraStore 4.2.3


May 09th, 2023

- Security string 2023-05-05
- Some kernel patches
- Mulch Webview 113.0.5672.77


April 15th, 2023

-  Security string 2023-04-05
-  Some kernel patches
-  Removed Bromite browser and shipped LineageOS' Jelly instead
-  Mulch Webview 112.0.5615.48


March 19th, 2023

- Security string 2023-03-05
- Some kernel patches
- Bromite Webview replaced by Mulch Webview 111.0.5563.58


February 13th, 2023

- Security string 2023-01-05
- Some kernel patches
- microG 0.2.27.223616-3
- Spoof apps installed by G*PlayStore


January 06th, 2023

- Security string 2023-01-05
- Bromite Browser and Webview updated to 108.0.5359.156
- Some kernel patches
- microG 0.2.26.223616-16


December 11th, 2022

- Security string 2022-12-05
- Bromite Browser and Webview updated to 108.0.5359.106
- Some kernel patches
- microG 0.2.26.223616-2


November 12th, 2022

- Security string 2022-11-05
- Bromite Browser and Webview updated to 106.0.5249.163
- Some kernel patches
- microG 0.2.25.223616-10


October 6th, 2022

- Security string 2022-10-05
- Bromite Browser and Webview updated to 105.0.5195.147
- Some kernel patches
- microG 0.2.24.223616-61


September 9th, 2022

- Security string 2022-09-05
- Bromite Browser and Webview updated to 104.0.5112.91
- Kernel: Some patches and also hardening (GrpaheneOS patches)
- microG 0.2.24.214816-30
- Contacts app slightly 'de-Googled'


August 6th, 2022

- Security string 2022-08-05
- Bromite Browser and Webview updated to 103.0.5060.140
- Some kernel patches


July 14th, 2022

- Security string 2022-06-05
- Some kernel patches


June 15th, 2022

- Security string 2022-06-05
- Some kernel patches
- Bromite Browser and Webview on 102.0.5005.96
- microG updated to 0.2.24.214816-11


May 9th, 2022

- Security string 2022-05-05
- Some kernel patches
- Bromite Browser and Webview on 101.0.4951.53
- microG updated to 0.2.24.214816-10
- Mozilla Location provider on 1.15


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
