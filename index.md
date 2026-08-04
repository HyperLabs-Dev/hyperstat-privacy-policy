# Privacy Policy for HyperStat

**Effective Date:** August 4, 2026  
**Last Updated:** August 4, 2026  

Thank you for choosing to be part of our community at **HyperStat: FPS Overlay Monitor**. We are deeply committed to protecting your personal information, maintaining transparency, and safeguarding your right to privacy under international standards (including Google Play Store terms, GDPR, and CCPA).

---

### 1. Information We Collect
HyperStat is designed to be an independent local system performance and FPS monitor. **We do not collect, store, or share any personal data.** 

All hardware diagnostics, system statistics (CPU, RAM, Battery, Network, Storage), and display frametime information are accessed strictly locally on your device in real-time:

* **Standard Hardware Metrics:** Core system metrics such as CPU usage, RAM allocation, Battery levels, Network speed, and Storage capacity are queried directly from standard open Android APIs and Linux system files provided by the operating system. If a device manufacturer restricts access to any of these standard data points, HyperStat will either display the metric as unavailable or utilize safe fallback logic to approximate the value based on remaining available system data.
* **Note on Custom Hardware Estimations:** Due to standard Android API restrictions, many device manufacturers block direct access to GPU hardware sensors (which normally results in an empty or 0% reading). To overcome this, HyperStat utilizes an independent, custom software algorithm to approximate **GPU Load** based on other available system heuristics and memory bandwidth. Additionally, metrics like **Frametime and FPS** are derived from the system's display refresh rate and precision telemetry rather than direct graphics pipeline intrusion. This ensures you receive accurate performance insights without compromising system stability.

---

### 2. Permissions & Usage
To function properly and deliver seamless on-screen statistics, HyperStat requests the following system permissions:

* **Display Over Other Apps (System Overlay):** Used exclusively to render our floating performance HUD overlay widget on top of active 3D games or applications. The sole function of this overlay is to provide real-time, on-screen hardware statistics to the user (specifically displaying: Network speed, Frametime, FPS, CPU Load/Temperature, RAM Usage, GPU Load, and Battery Level). It functions as a passive read-only meter and does **not** interact with, record, screen-capture, or monitor the content of underlying apps or games.
* **Optional Shizuku Permission (Precision Telemetry):** Users may optionally connect HyperStat to the independent **Shizuku framework** to unlock advanced, root-free precision reading of display frametimes and real-time FPS frequencies. Shizuku queries execute 100% locally on your processor; zero system commands, device logs, or personal identifiers are ever collected or transferred off your smartphone.
* **Location (Fine - Legacy OS Only):** On older versions of Android (Android 8-10), this permission is strictly required by the Android operating system solely to read the name of the currently connected Wi-Fi SSID network and wireless speed. We **never** track, GPS-locate, store, or send your physical real-world location data.
* **Storage / Media:** Used strictly to calculate and display the total and available free storage capacity on your device dashboard. We do not scan, read, copy, or access your personal files, photographs, or media.

---

### 3. Third-Party Services, Advertising & Analytics
To support continuous software updates and developer maintenance, HyperStat integrates official, verified Google software development kits (SDKs):

* **Google AdMob Advertising:** We utilize **Google AdMob** to serve non-intrusive advertisements (including App Open, banner, and interstitial ads during menu screen transitions). AdMob may collect and process device advertising identifiers (such as the Android Advertising ID / AAID) and broad anonymous regional metrics to serve relevant, optimized advertising campaigns.
* **Firebase Analytics & Crashlytics:** We utilize **Google Firebase** strictly to collect anonymous crash telemetry and basic diagnostic usage statistics to assist our engineering team in identifying bugs and improving software stability across different Android hardware models. This data is completely anonymized and contains no personal user identifiers.

For further details on how our certified advertising partners manage data in compliance with international privacy rules (including European GDPR, California CCPA, and Google Play Data Safety guidelines), please review:
* [Google Privacy & Terms](https://policies.google.com/privacy)
* [How Google uses data when you use our partners' sites or apps](https://policies.google.com/technologies/partner-sites)

---

### 4. Children's Privacy (COPPA Compliance)
Our application does not target or address anyone under the age of 13. We do not knowingly solicit, process, or collect personally identifiable information from children under 13 years of age.

---

### 5. Trademark & Affiliation Disclaimer
**"HyperStat: FPS Overlay Monitor" is an independent system monitoring and diagnostics tool created by HyperLabs-Dev. It is NOT affiliated, associated, authorized, endorsed by, or in any way officially connected with any other companies, products, services, or registered trademarks.** This application is a standalone diagnostic utility developed solely for Android devices.

---

### 6. Limitation of Liability
The App is provided strictly on an **"AS IS"** and available basis. The developers of HyperLabs-Dev are not liable for any direct or indirect damages, battery consumption impact, or data loss resulting from software usage or customization.

---

### 7. Changes to This Privacy Policy
We may update our Privacy Policy from time to time to align with developer policy enhancements or new system capabilities. Any changes will become effective immediately upon posting to this public web page with an updated effective date. You are advised to review this page periodically for any changes.

---

### 8. Contact Us
If you have any questions, compliance feedback, or privacy suggestions regarding our software architecture, please reach out to our team directly via our official Google Play Store app support listing or via our GitHub Developer account at [https://github.com/HyperLabs-Dev](https://github.com/HyperLabs-Dev).
