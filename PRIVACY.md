## Privacy Policy

_Last updated: April 25, 2025_

Device Info does **not** collect any personal information (e.g., name, email, phone number, or precise location) and operates in a read-only mode: all data is accessed locally, and the only information persisted is small key-value pairs via Android’s SharedPreferences (never stored off-device) :contentReference[oaicite:0]{index=0}. The app enforces HTTPS/TLS for all network communications, never acquires or abuses root privileges, and never transmits or stores identifiable user data externally :contentReference[oaicite:1]{index=1}.

---

## 1. Third-Party SDKs & Services

Device Info integrates these SDKs, which may collect device-level identifiers (e.g., Google Advertising ID, device model, OS version) in accordance with their policies—**no** personal user data is collected:

- **Google Firebase** (Analytics, Remote Config, Crashlytics, Firestore) :contentReference[oaicite:2]{index=2}  
- **Google AdMob** (in-app advertising) :contentReference[oaicite:3]{index=3}  
- **Google Play Services & Billing** :contentReference[oaicite:4]{index=4}  

For full details, see:  
- [Firebase Privacy & Security](https://firebase.google.com/support/privacy) :contentReference[oaicite:5]{index=5}  
- [Google Privacy Policy](https://policies.google.com/privacy) :contentReference[oaicite:6]{index=6}

---

## 2. Permissions

Device Info requests only the permissions necessary for its functionality:

- **INTERNET**  
- **ACCESS_NETWORK_STATE**  
- **ACCESS_WIFI_STATE**  
- **QUERY_ALL_PACKAGES**  
- **BLUETOOTH**  
- **ACCESS_FINE_LOCATION** (optional)

- **INTERNET** is used to query Firebase and download Android-version images from Wikimedia Commons (not essential for core functionality) :contentReference[oaicite:7]{index=7}.  
- **QUERY_ALL_PACKAGES** lets the “Apps” tab list all installed user/system apps; Device Info does **not** collect or share which apps you have installed :contentReference[oaicite:8]{index=8}.  
- **BLUETOOTH** enables scanning of Bluetooth adapters and paired devices for hardware reporting.  
- **ACCESS_FINE_LOCATION**, if granted, is used **locally only** to display approximate location and is **never** stored or transmitted.

---

## 3. Data Usage, Security & Root Access

- All data access is **read-only**, except for the local storage of preferences via SharedPreferences (no external storage) :contentReference[oaicite:9]{index=9}.  
- Device Info enforces HTTPS/TLS for all communications and follows industry-standard security practices :contentReference[oaicite:10]{index=10}.  
- The app **will never** acquire root privileges and does not abuse existing root access; any optional features are strictly limited to displaying system information.

---

## 4. Flutter Technology Stack

Built with **Flutter 3.29** and using these packages (no versions listed here for brevity):  
`cloud_firestore`, `cupertino_icons`, `fl_chart`, `flutter_svg`, `flutter_staggered_animations`, `firebase_core`, `firebase_remote_config`, `firebase_crashlytics`, `package_info_plus`, `get_it`, `equatable`, `flutter_bloc`, `url_launcher`, `shared_preferences`, `provider`, `device_info_plus`, `percent_indicator`, `flutter_localizations`, `path_provider`, `shimmer`, `rxdart`, `firebase_analytics`, `google_mobile_ads` :contentReference[oaicite:11]{index=11}.

---

## 5. Contact & Repository

This Privacy Policy is maintained in a dedicated GitHub repository. To file issues or ask questions, please open an issue on this repository’s **GitHub Issues** page.
