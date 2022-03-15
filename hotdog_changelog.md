March 15th, 2022

- Bromite Browser and Webview on 99.0.4844.58 (bugfix build)


March 11th, 2022

- Security string 2022-03-05
- Some kernel patches
- Bromite Browser and Webview on 99.0.4844.55
- microG 0.2.24.214816-2
- AuroraStore 4.1.1


January 20th, 2022

- Security string 2022-01-05
- Some kernel patches
- A couple of patches and fixes from LineageOS


December 19th, 2021

- Security String 2021-12-05
- Bromite System Webview and Browser on 96.0.4664.54
- microG 0.22.214516-21


November 16th, 2021

- Security string 2021-11-05
- Bromite System Webview and Browser updated to 94.0.4606.109
- Recovery will not be overwritten any more when flashing


October 11th, 2021

- Security string 2021-10-01
- AOSP tag 11.0.0_r46
- Bromite System Webview and Browser updated to 93.0.4577.83


September 17th, 2021
 Initial build:

- Security string 2021-09-05
- AOSP tag 11.0.0_r43
- Vendor blobs based on OOS 11.0.3.1
- Pre-installed microG (0.2.22.212658-2) like LineageOS for microG project (own fork)
- Pre-installed AuroraStore (4.0.7), AuroraDroid (1.0.8) and AuroraServices (1.1.1)
- OTA Support
- eSpeakTTS engine
- Bromite (92.0.4515.134) as default browser
- Additional security hardening features listed below:
  o Cloudflare as default DNS (instead of Google)
  o Privacy-preferred default settings
  o Optional blocking of Facebook- and Google-Tracking (Settings - Network & Internet)
  o Optional disable captive portal detection or choose from various providers (default is GrapheneOS and not Google; Settings - Network & Internet)
  o Firewall UI (under Trust)
  o Increased max. password length of 64
  o No submission of IMSI/phone number to Google when GPS is in use
  o Default hosts file with many blocked ad/tracking sites
  o Privacy-enhanced Bromite SystemWebView (92.0.4515.134)
  o Extra control of sensor access for additionally installed user apps (Special access under app permissions)
  o Kernel kept up to date with ASB patches of Google kernel/common 'android-4.14-q-release' branch
  o Debloated from Oneplus blobs for Soter and IFAA
  o Hardened bionic lib and constified JNI method tables
  o Option to only use fingerprint unlock for apps and not for the device
  o Optional timeout for Bluetooth and WLAN connections
  o Per connection WiFi randomization option

 
