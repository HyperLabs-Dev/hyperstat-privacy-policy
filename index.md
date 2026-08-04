# Privacy Policy for HyperStat & HyperGFX Engine

**Effective Date:** August 4, 2026  
**Last Updated:** August 4, 2026  

Thank you for choosing to be part of our gaming and diagnostics community at **HyperLabs-Dev** (**HyperStat** & **HyperGFX Engine**). We are deeply committed to maintaining trust, transparency, and safeguarding your personal information and right to privacy under global data safety standards (including Google Play Store terms, GDPR, and CCPA).

---

### 1. Information We Collect & Data Processing
Our applications are designed as independent local system performance monitors and zero-root hardware optimization consoles. **We do not personally collect, steal, sell, or transmit your private personal identifiable data, passwords, or game credentials to any external servers.**

All hardware diagnostics, system statistics (CPU, RAM, Battery, Network, Storage, Display Hz), and game configuration files are accessed and modified strictly locally on your device in real time:

* **Standard Hardware Telemetry:** Core metrics such as CPU usage, RAM allocation, Battery thermals, Network throughput, and Storage capacity are queried directly from open Android runtime APIs and Linux kernel sysfs nodes provided by the Android operating system.
* **Custom Hardware & GPU Estimations:** Due to manufacturer restrictions on direct GPU pipeline polling, our software utilizes custom statistical algorithms and refresh rate heuristics to derive accurate GPU Load and Frametime velocity without compromising system stability.

---

### 2. Permissions & Specialized Hardware Capabilities
To enable professional hardware monitoring and graphics modification, our software utilizes the following operating system permissions and technical frameworks:

* **Shizuku Hardware Engine (Root-Free IPC):** Our Advanced Overdrive console utilizes the independent **Shizuku framework** (connecting via Android Binder IPC and wireless ADB) to execute privileged display and GPU optimization shell commands without requiring device root. Shizuku is utilized exclusively to apply custom render scaling, AMD FSR/GSR spatial upscaling shaders, EGL Anti-Aliasing flags (MSAA, FXAA, TAA, TXAA), V-Sync unclamp protocols, and physical screen Max-Hz refresh rate locks. **All shell commands and binder interactions execute 100% locally on your smartphone CPU; zero privilege tokens or device logs are ever transmitted off your device.**
* **Scoped Storage & Game Config Editing (`UserCustom.ini`):** For Traditional (No-Shizuku) graphics unlocking, our app requests targeted folder storage access (via Android Storage Access Framework) to locate and update plain-text configuration files (such as Unreal Engine 4/5 `.ini` files in gaming sub-directories or user storage at `Documents/HyperGFX_Profiles/`). This access is used strictly to perform syntax string replacements (e.g., enabling 120 FPS CVars or removing rendering shadows). **We never read, harvest, modify, or transmit your private photographs, videos, personal documents, or game account authentication tokens.**
* **Display Over Other Apps (System Overlay):** Used exclusively to render our floating horizontal gamer HUD statistics meter on top of active 3D games or applications. The overlay functions solely as a passive read-only performance meter (displaying real-time FPS, CPU thermals, memory usage, and crosshairs) and does NOT capture, monitor, record, or screenshot the content of underlying games or screens.
* **Location (Fine - Legacy OS Only):** On legacy Android versions (Android 8-10), this system permission is strictly mandated by Android OS solely to display the current Wi-Fi network connection speed and SSID. We never track, GPS-locate, or save your physical real-world location.

---

### 3. Third-Party Services, Analytics & Advertising (Google AdMob)
To support continued independent developer maintenance and research, our application integrates official, Google-verified third-party software development kits (SDKs):

* **Google AdMob & Advertising Services:** We utilize **Google AdMob** to display non-intrusive banner and rewarded video advertisements. AdMob may process device identifiers (such as the Android Advertising ID / AAID), broad demographic inferred regions (city/country level), and general advertisement interaction metrics to deliver relevant, optimized advertising campaigns.
* **Firebase Analytics & Crashlytics:** We utilize **Google Firebase** to collect anonymized crash logs, fatal exception traces, and general session engagement statistics to assist our engineering team in identifying performance bugs across diverse Android hardware models.

For further details on how our certified advertising partners process data under international regulatory rules (GDPR, CCPA, and Google Play Data Safety), please review:
* [Google Privacy & Terms](https://policies.google.com/privacy)
* [How Google uses data when you use our partners' sites or apps](https://policies.google.com/technologies/partner-sites)

---

### 4. Children's Privacy (COPPA Compliance)
Our software utilities and performance monitoring applications do not target, address, or intentionally market to anyone under the age of 13. We do not knowingly collect or solicit personally identifiable information from children under 13 years of age.

---

### 5. Trademark & Affiliation Disclaimer
**"HyperStat" and "HyperGFX Engine" are proprietary, independent mobile system monitoring and game configuration optimization utilities created by HyperLabs-Dev. They are NOT affiliated, associated, authorized, endorsed by, or in any way officially connected with Google Inc., Tencent, Krafton, Epic Games, Activision, Qualcomm, AMD, or any other third-party trademark owners.** All game names, brand terms, and architectural benchmarks mentioned within the software serve purely descriptive and operational compatibility purposes.

---

### 6. Limitation of Liability & Overdrive Disclaimer
Our applications are provided strictly on an **"AS IS"** and available basis. While all hardware modifications (such as display refresh rate locks and EGL upscaling flags) utilize secure, manufacturer-provided system databases and root-free Shizuku APIs, the developers of HyperLabs-Dev assume no financial or legal liability for accidental battery drain, excessive device thermals, game account suspensions from third-party developers, or operating system resets resulting from aggressive hardware customization or incorrect software configuration.

---

### 7. Changes to This Privacy Policy
We reserve the right to update or revise this Privacy Policy periodically to reflect ongoing architectural upgrades or changing Play Store requirements. Any modifications will become effective immediately upon posting to this public web address with an updated effective date. You are advised to review this page periodically to stay informed of our data safety commitments.

---

### 8. Contact Our Engineering Team
If you have any questions, regulatory inquiries, or privacy suggestions regarding our software architecture, please reach out to the lead developer directly via our official Google Play Store application support listing or our official GitHub Developer Organization at [https://github.com/HyperLabs-Dev](https://github.com/HyperLabs-Dev).
