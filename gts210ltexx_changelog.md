May 11th, 2024

- Custom build release 2024-05-01
- Some kernel patches
- Mulch system webview 125.0.6422.35


April 21st, 2024
Initial build:

- Custom build release 2024-04-01
- AOSP tag 11.0.0_r46
- Pre-installed microG and compansion (aka FakeStore) 0.3.0.233515
- Pre-installed AuroraStore (4.4.1), AuroraDroid (1.0.8) and AuroraServices (1.1.1)
- Mulch System Webview 123.0.6312.99
- OTA Support
- eSpeakTTS engine
- Additional security hardening features listed below:
- Cloudflare as default DNS (instead of Google)
- Privacy-preferred default settings
- Optional blocking of Facebook- and Google-Tracking (Settings - Network & Internet)
- Optional disable captive portal detection or choose from various providers (default is GrapheneOS and not Google; Settings - Network & Internet)
- Firewall UI (under Trust)
- Increased max. password length of 64
- No submission of IMSI/phone number to Google when GPS is in use
- Default hosts file with many blocked ad/tracking sites
- Privacy-enhanced Bromite SystemWebView (93.0.4577.83)
- Extra control of sensor access for additionally installed user apps (Special access under app permissions)
- Option to only use fingerprint unlock for apps and not for the device
- Optional timeout for Bluetooth and WLAN connections
- Per connection WiFi randomization option
