# DreamWeave — Privacy Policy

**Effective Date:** 2026-03-21
**Last Updated:** 2026-03-21
**Version:** 1.0.0

Published by **Sudarshan Tech Labs** | https://sudarshantechlabs.com | sudarshantechlabs@gmail.com

---

DreamWeave is a private dream journal for Android. It allows you to write dream entries, record voice memos, and optionally request AI-powered dream analysis via Google Gemini. This policy explains exactly what data is created, where it is stored, and how it is handled.

---

## Data Collection

### Journal and Audio Data (Stored Locally)

| Data | Purpose | Storage |
|---|---|---|
| Dream journal entries (text, title, mood, date) | Core journaling functionality | Room database on your device |
| Voice memo recordings (.m4a or .wav files) | Audio dream recording | App private storage on your device |
| Playback history and audio metadata | In-app playback | Room database on your device |
| App preferences and theme settings | Personalisation | SharedPreferences on your device |

All of the above is stored exclusively on your device and never transmitted to any server operated by Sudarshan Tech Labs.

### Data Sent to Third-Party Services

**Google Gemini API (user-initiated only):**
When you tap "Analyse Dream", the text content of that specific entry is sent to the Google Gemini API.
- **Data sent:** Dream entry text only
- **Sent by:** Your device directly to Google
- **Stored by us:** No — Sudarshan Tech Labs does not receive or retain this data
- **Gemini Privacy:** https://policies.google.com/privacy

**Google Play Billing:**
In-app purchases are processed entirely by Google Play. Sudarshan Tech Labs does not receive or store any payment information.

---

## How We Use Your Data

| Purpose | Data Used |
|---|---|
| Display and manage your dream journal | Local journal entries |
| Play back voice memos | Local audio files |
| Generate AI dream insights (on request) | Dream text sent to Gemini API |
| Provide in-app purchase features | Handled by Google Play |

---

## Data Storage and Security

- **Journal data:** Stored in a Room database in your app's private directory
- **Audio files:** Stored in your app's private storage, inaccessible to other apps
- **No cloud backup:** Sudarshan Tech Labs operates no backend server for DreamWeave
- **Android sandbox:** All data is protected by Android's application sandboxing

## Data Retention

| Data | Retention |
|---|---|
| Journal entries | Until you delete them or uninstall the App |
| Audio recordings | Until you delete them or uninstall the App |
| App preferences | Until you clear app data or uninstall |

---

## Data Sharing

We do not sell or share your data. The only external data transmission is dream text sent to the Gemini API when you explicitly request an analysis.

---

## Permissions Explained

| Permission | Why It Is Needed |
|---|---|
| `RECORD_AUDIO` | To record voice memos of your dreams |
| `INTERNET` | To call the Gemini API when you request dream analysis |
| `ACCESS_NETWORK_STATE` | To check connectivity before making API calls |
| `WRITE_EXTERNAL_STORAGE` (Android 9 and below) | To export files on older Android versions |
| `READ_EXTERNAL_STORAGE` (Android 9 and below) | To access files on older Android versions |
| `VIBRATE` | For haptic feedback in the UI |
| `WAKE_LOCK` | To keep the screen active during audio recording |

---

## Your Rights and Controls

- **Delete individual entries:** Use the delete option within any journal entry
- **Delete audio recordings:** Delete voice memos from within the App
- **Delete all data:** Uninstall the App or clear app data via Android Settings > Apps > DreamWeave > Storage > Clear Data

---

## Children's Privacy

DreamWeave is not directed at children under 13. We do not knowingly collect personal information from children. If you believe a child under 13 is using the App, please contact us at sudarshantechlabs@gmail.com.

---

## Changes to This Policy

We may update this Privacy Policy from time to time. We will notify you of significant changes via:

- In-app notification
- Updated policy date on this page

Continued use of DreamWeave after changes become effective constitutes your acceptance of the updated policy.

---

## Contact Us

For privacy questions, data access requests, or account deletion:

- **Email:** sudarshantechlabs@gmail.com
- **Developer:** sunny.sudarshan@gmail.com
- **Website:** https://sudarshantechlabs.com
- **Response Time:** Within 48 hours

---

## GDPR Rights (EU Users)

If you are in the European Economic Area, you have the right to:

- **Access** — Request a copy of your personal data
- **Rectification** — Correct inaccurate data
- **Erasure** — Request deletion of your data
- **Restrict Processing** — Limit how we use your data
- **Data Portability** — Receive your data in a portable format
- **Object** — Object to certain types of processing

To exercise these rights, contact us at the details above.

---

## Play Store Data Safety Summary

| Data type | Collected | Shared | Purpose |
|---|---|---|---|
| Journal entries | Local only | No | App functionality |
| Audio recordings | Local only | No | App functionality |
| Dream text (Gemini) | On request | Google (Gemini) | AI analysis |

---

---

**This privacy policy complies with:**
- Google Play Store requirements
- GDPR (General Data Protection Regulation)
- CCPA (California Consumer Privacy Act)

**Last reviewed:** 2026-03-21
