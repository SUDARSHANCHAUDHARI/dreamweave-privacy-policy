# Privacy Policy — DreamWeave

**Last updated:** 2026-03-21
**Effective date:** 2026-03-21

This Privacy Policy describes how **Sudarshan Tech Labs** ("we", "us", or "our") handles information in connection with the **DreamWeave** Android application ("the App").

---

## 1. About This App

DreamWeave is a private dream journal. It allows you to write dream entries, record voice memos, and optionally analyse dream content using the Google Gemini API. The App is designed to keep your personal journal data on your device.

---

## 2. Data We Do Not Collect

Sudarshan Tech Labs does not collect, store, or process any personal data on its own servers. We have no backend database or account system. Your dream journal entries and audio recordings remain on your device.

---

## 3. Data Stored Locally on Your Device

The following data is created and stored exclusively on your device:

| Data | Purpose | Storage |
|---|---|---|
| Dream journal entries (text, mood, date) | Core app functionality | Room database (local) |
| Audio recordings (voice memos) | Voice dream recording | Device local storage |
| App preferences and settings | Personalisation | SharedPreferences (local) |

This data never leaves your device unless you explicitly export or share it using Android's sharing system.

---

## 4. Third-Party Services

### 4.1 Google Gemini API

When you use the AI dream analysis feature, the text of your dream entry is sent to the Google Gemini API for processing. This transmission occurs only when you explicitly request an analysis.

- **Data sent:** Dream entry text only
- **Purpose:** Generate AI-powered insights about dream content
- **Stored by us:** No — we do not receive or store the response on any server
- **Google's privacy policy:** https://policies.google.com/privacy

If you do not use the AI analysis feature, no data is sent to Gemini.

### 4.2 Google Play Billing

In-app purchases are processed by Google Play. We do not receive or store payment information.

- **Google Play terms:** https://play.google.com/about/play-terms/

---

## 5. Permissions Explained

| Permission | Reason |
|---|---|
| `RECORD_AUDIO` | Required to record voice memos of your dreams |
| `INTERNET` | Required to call the Gemini API for AI analysis (optional feature) |
| `ACCESS_NETWORK_STATE` | Required to check connectivity before making API calls |
| `WRITE_EXTERNAL_STORAGE` (Android 9 and below) | Required to export files on legacy Android versions |
| `READ_EXTERNAL_STORAGE` (Android 9 and below) | Required to access files on legacy Android versions |
| `VIBRATE` | Provides haptic feedback in the UI |
| `WAKE_LOCK` | Keeps the screen active during audio recording |

---

## 6. Data Retention and Deletion

All App data is stored locally on your device. You control it entirely:

- **Delete individual entries:** Use the delete function within the App
- **Delete all data:** Clear app data via Android Settings, or uninstall the App

When you uninstall the App, all locally stored data is permanently removed.

---

## 7. Children's Privacy

DreamWeave is not directed at children under 13. We do not knowingly collect personal information from children. If you believe a child under 13 is using the App, please contact us.

---

## 8. Data Security

- All journal data is stored in a local Room database on your device
- Android's application sandboxing ensures no other app can access this data without your permission
- Audio files are stored in the App's private directory
- No data is transmitted to Sudarshan Tech Labs servers

---

## 9. Changes to This Policy

We may update this Privacy Policy from time to time. We will notify you of significant changes by updating the "Last updated" date. Continued use of the App after changes become effective constitutes acceptance of the updated policy.

---

## 10. Contact

**Sudarshan Tech Labs**
Official website: https://sudarshantechlabs.com
Company email: sudarshantechlabs@gmail.com
Developer contact: sunny.sudarshan@gmail.com

---

## Play Store Data Safety Summary

- **Data collected by the App:** None
- **Data shared with third parties:** Dream text (Gemini API, user-initiated only)
- **Data encrypted in transit:** Yes (HTTPS)
- **User can request deletion:** Yes (uninstall or clear app data)

---

*This policy applies to the DreamWeave Android application published by Sudarshan Tech Labs.*
