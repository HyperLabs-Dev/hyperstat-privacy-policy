# Privacy Policy for HyperG

**Application:** HyperG: Game Booster & FPS HUD  
**Developer:** HyperLabs-Dev  
**Effective Date:** October 21, 2026  
**Last Updated:** October 21, 2026  

Thank you for choosing **HyperG: Game Booster & FPS HUD** ("HyperG", "we", "our", or "the app"). We are deeply committed to protecting your privacy and ensuring complete transparency regarding how our software operates on your device under international privacy standards (including Google Play Store Developer Policies, GDPR, and CCPA).

---

### 1. Information We Collect
HyperG is designed as an independent, local-first system gaming optimization and hardware telemetry tool. **We do not collect, transmit, store, sell, or share any personal data.** 

All performance statistics and hardware diagnostics (CPU workload, GPU utilization, RAM allocation, battery temperature, storage capacity) are computed strictly locally on your device in real-time volatile memory:
* **Hardware Metrics:** Core system metrics such as CPU usage, RAM allocation, battery temperature, and storage capacity are queried directly from standard open Android APIs and Linux system files provided by the operating system.
* **100% On-Device:** Zero hardware telemetry, gameplay records, or device identifiers are ever transmitted off your smartphone.

---

### 2. Permissions & Usage Disclosures
To function properly and deliver seamless on-screen gaming enhancement, HyperG requests the following system permissions:
* **Display Over Other Apps (`android.permission.SYSTEM_ALERT_WINDOW`):** Used exclusively to render our floating performance HUD overlay widget on top of active games. The sole function of this overlay is to provide real-time, on-screen hardware statistics (FPS counter, CPU/GPU load, clock, and battery stats). It functions as a passive read-only meter and does not record or intercept screen contents.
* **Foreground Service (`android.permission.FOREGROUND_SERVICE`):** Required to maintain the floating telemetry monitor while games are running in the foreground.
* **Kill Background Processes (`android.permission.KILL_BACKGROUND_PROCESSES`):** Used by the RAM Booster engine to terminate cached third-party background tasks to free physical memory for gaming.
* **Optional Shizuku Framework:** Users may optionally connect HyperG to the independent Shizuku system service (`uid=2000`) to execute privileged system cache compaction and lock the display refresh rate (120Hz/90Hz/60Hz). Shizuku commands run 100% locally on your smartphone; zero system logs or personal identifiers are ever collected.

---

### 3. Third-Party Services, Advertising & Analytics
To support continuous software updates and independent developer maintenance, HyperG integrates official, verified Google software development kits (SDKs):
* **Google AdMob Advertising:** We utilize Google AdMob to serve non-intrusive advertisements (such as banner ads and occasional launch interstitials). AdMob may collect and process device advertising identifiers (such as the Android Advertising ID / AAID) in strict accordance with [Google Privacy & Terms](https://policies.google.com/privacy).

---

### 4. Children's Privacy (COPPA Compliance)
HyperG does not address anyone under the age of 13. We do not knowingly solicit, process, or collect personally identifiable information from children under 13 years of age.

---

### 5. Trademark & Affiliation Disclaimer
**"HyperG: Game Booster & FPS HUD"** is an independent diagnostic and system utility developed by HyperLabs-Dev. It is not affiliated with, authorized, endorsed by, or in any way officially connected with any other games, hardware manufacturers, or registered trademarks.

---

### 6. Developer Contact
If you have any questions or suggestions regarding this Privacy Policy, please contact our development team via GitHub:  
[https://github.com/HyperLabs-Dev](https://github.com/HyperLabs-Dev)
