# Privacy Policy for Screen Recorder 8K HD

**Effective Date:** July 15, 2026  
**Last Updated:** July 15, 2026

Screen Recorder 8K HD ("the Extension") is committed to protecting your privacy.  
This Privacy Policy explains how the Extension handles user information.

---

## 1. Overview

Screen Recorder 8K HD is a browser extension that allows users to record their screen in high resolution (up to 8K where supported by the device, operating system, and browser).

All recording and processing occur locally within the user's browser.  
The Extension does **not** operate any remote servers and does **not** transmit recordings externally.

---

## 2. Information We Collect

**We do not collect, store, transmit, or sell any personal information.**

Specifically, the Extension does NOT:

- Collect personally identifiable information (PII)
- Track browsing history
- Monitor website activity
- Use analytics or telemetry tools
- Use advertising SDKs
- Share data with third parties
- Upload screen recordings to external servers

---

## 3. Screen and Audio Recording

The Extension allows users to record:

- The current browser tab  
- A specific application window  
- The entire screen  

Recording is only possible after the user explicitly grants permission through the browser’s secure screen-sharing dialog.

All screen and audio streams are processed locally using standard browser APIs such as:

- `navigator.mediaDevices.getDisplayMedia`
- `MediaRecorder`

Recordings remain on the user's device unless the user chooses to download them locally.

The developer of this Extension does not have access to any recordings.

---

## 4. Local Storage of Preferences

The Extension may use the browser's `storage` API to save user preferences such as:

- Selected resolution (including 4K or 8K where supported)
- Frame rate (30fps or 60fps)
- Audio source selection
- Output format preference

These preferences are stored locally in the user's browser and are not transmitted externally.

No recorded video content is stored in extension storage.

---

## 5. Permissions Usage

The Extension requests only the permissions necessary to provide its core functionality:

- **desktopCapture / getDisplayMedia** – to enable screen recording after user consent  
- **activeTab** – to record the currently selected browser tab (when chosen)  
- **downloads** – to allow users to save recordings locally  
- **storage** – to store user preferences locally  

These permissions are used strictly to enable screen recording features.

---

## 6. No Remote Code or External Scripts

Screen Recorder 8K HD does not load remote JavaScript, external code libraries, or third-party scripts.

All functionality is bundled within the extension package in compliance with Manifest V3 requirements.

---

## 7. Data Security

Because the Extension does not collect or transmit data, there is no centralized storage of user information.

All recordings remain under the user’s control on their own device.

---

## 8. Children’s Privacy

The Extension does not knowingly collect personal information from anyone, including children under the age of 13.

---

## 9. Changes to This Privacy Policy

If this Privacy Policy is updated, the revised version will be posted with a new "Last Updated" date.

Continued use of the Extension after changes indicates acceptance of the updated policy.

---

## 10. Contact Information

If you have any questions about this Privacy Policy, you may contact:

**Email:** your-email@example.com

---

## 11. Compliance Statement

Screen Recorder 8K HD complies with the privacy requirements of:

- Chrome Web Store Developer Program Policies  
- Microsoft Edge Add-ons Developer Policies  

The Extension operates entirely client-side and does not engage in data collection or transmission.

---

**End of Privacy Policy**
