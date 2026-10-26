# HL Light Privacy Policy

**Last Updated**: October 26, 2026  
**Effective Date**: October 26, 2026

Welcome to HL Light! HL Light ("the Application") is a smart Bluetooth lighting control utility designed for automotive lights, car ambient lights, interior mood lamps, and LED strips. We are deeply committed to protecting your privacy. This Privacy Policy explains our data handling practices and how system permissions are utilized.

---

## 1. No Personal Data Collected

1. **No Account Required**: The Application operates entirely as a local hardware controller. All features can be used without creating an account or logging in.
2. **Zero Personally Identifiable Information**: We do not collect, request, or store your name, phone number, email address, physical location, facial data, or any other sensitive personal data.
3. **No User Tracking or Ads**: The Application contains no third-party advertising SDKs or tracking frameworks. We do not access Identifier for Advertisers (IDFA) or track you across other applications.

---

## 2. System Permissions and Usage

The Application only requests permissions that are strictly necessary to communicate with and control your lighting equipment:

1. **Bluetooth Permission (BLE)**
   - **Purpose**: Used to scan, discover, pair, and connect with your smart car lights, ambient lamps, or LED strips via Bluetooth Low Energy (BLE), and send commands (color adjustments, dynamic modes, brightness, and speed).
   - **Details**: All Bluetooth communication takes place strictly peer-to-peer between your mobile device and the physical lighting hardware. No data is ever transmitted over the Internet.

2. **Microphone Permission**
   - **Purpose**: Requested strictly when you choose to use the "Music Sync" or "Sound Reactive" modes to capture ambient sounds or music beats.
   - **Details**: Audio signals are processed in real-time strictly in volatile device memory using Fast Fourier Transform (FFT) analysis to generate light sync patterns. We never record, save, store, playback, or upload your audio files. Microphone listening stops immediately when you exit the feature.

3. **Local Storage Permission**
   - **Purpose**: Used solely to save your custom lighting profiles, LED chip counts, and RGB wiring configurations in your device's private sandbox storage.
   - **Details**: All settings remain solely on your device and are permanently deleted by the operating system if you uninstall the Application.

---

## 3. Third-Party Services and Data Sharing

The Application does not utilize any third-party analytics, marketing, or advertising services. We do not sell, rent, lease, or share any user data with any third party.

---

## 4. Children's Privacy

The Application does not target or provide specialized services to children under 13, and does not collect any information from children.

---

## 5. Changes to This Policy

We may update this Privacy Policy from time to time. Any changes will be published directly on this page or outlined in the release notes.

---

## 6. Contact Us

If you have any questions or feedback regarding this Privacy Policy, please contact us:

- **Developer**: zshl-iot
- **Support & Privacy Email**: support@zshl-iot.com
- **Official Repository**: https://github.com/kvmin/hl-light
