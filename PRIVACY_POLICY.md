# Privacy Policy for My Med Journal

**Effective Date:** October 17, 2025  
**Last Updated:** October 17, 2025  
**Version:** 1.0.0

---

## Introduction

My Med Journal ("we", "our", or "us") is committed to protecting your privacy. This Privacy Policy explains how our mobile application ("App", "Application", or "My Med Journal") handles your personal health information.

**Our Core Privacy Principle: We collect NO data from you.**

This policy is designed to be clear and transparent about exactly what happens to your data when you use My Med Journal.

---

## Table of Contents

1. [Data We Do NOT Collect](#data-we-do-not-collect)
2. [Data You Store Locally](#data-you-store-locally)
3. [How Your Data is Stored](#how-your-data-is-stored)
4. [Data Security](#data-security)
5. [Data You Choose to Export](#data-you-choose-to-export)
6. [Subscription and Payment](#subscription-and-payment)
7. [Third-Party Services](#third-party-services)
8. [Children's Privacy](#childrens-privacy)
9. [Your Privacy Rights](#your-privacy-rights)
10. [Changes to This Policy](#changes-to-this-policy)
11. [Contact Information](#contact-information)

---

## Data We Do NOT Collect

**My Med Journal does not collect, transmit, or have access to any of your data.**

We do not:
- ❌ Collect any personal information
- ❌ Collect any health information
- ❌ Transmit data to our servers (we don't have servers)
- ❌ Use analytics or tracking tools
- ❌ Use advertising networks
- ❌ Share information with third parties
- ❌ Require account creation or login
- ❌ Store data in the cloud
- ❌ Access your contacts, photos, or other device data (except as needed for app functionality)
- ❌ Track your location
- ❌ Monitor your app usage
- ❌ Collect device identifiers for tracking

**We literally cannot see your data because it never leaves your device.**

---

## Data You Store Locally

All information you enter into My Med Journal is stored **locally on your device only**. This includes:

### Health Tracking Data
- **Medications:** Names, dosages, timing, and notes
- **Symptoms:** Types, severity levels (1-10), and notes
- **Vital Signs:** 
  - Blood pressure (systolic/diastolic)
  - Blood sugar/glucose levels
  - Body temperature
  - Heart rate/pulse
  - Oxygen saturation (SpO2)
  - Pain levels (0-10)
  - Weight measurements
- **Food & Nutrition:** Foods consumed, quantities, and timing
- **Liquid Intake:** Beverages consumed, amounts, and timing
- **Notes:** Free-form text entries about your health

### Optional Profile Information
- **Name:** Optional, used only for exports
- **Date of Birth:** Optional, used only for exports
- **Unit Preferences:** Weight (kg/lbs/stones), Blood Sugar (mg/dL/mmol/L), Liquid (ml/fl oz), Temperature (°F/°C)
- **Regional Settings:** Your selected region for default unit preferences

### App Settings & Preferences
- **Dashboard Configuration:** Tile order and visibility preferences
- **Appearance Settings:** Theme mode (light/dark/auto), selected font
- **Custom Items:** User-created medications, foods, liquids, and symptoms
- **Reminders:** Medication and water reminder schedules (stored locally, notifications handled by device OS)

### Important Notes:
- This information **never leaves your device** except when you explicitly choose to export it
- We **cannot access** any of this information
- You have **complete control** over all of this data

---

## How Your Data is Stored

### Local Database Storage
Your data is stored in an encrypted SQLite database on your device using **SQLCipher** with AES-256 encryption.

**Storage Location:**
- **Android:** App-specific directory (accessible only to the app)
- **iOS:** App sandbox (isolated from other apps)

**Encryption:**
- **At Rest:** All health data is encrypted using SQLCipher (AES-256 bit encryption)
- **Encryption Key:** Stored securely in your device's secure storage (Android Keystore / iOS Keychain)
- **Access Control:** Protected by your device authentication (PIN, fingerprint, face unlock, or pattern)

### Data Persistence
Your data persists on your device until you:
- Manually delete individual entries within the app
- Clear the app's data through device settings
- Uninstall the application

**When you uninstall the app, ALL your local data is permanently deleted from your device.**

---

## Data Security

### Security Measures We Implement

1. **Encryption at Rest**
   - Database encrypted with SQLCipher (AES-256)
   - Encryption key stored in device secure storage
   - Cannot be accessed without device authentication

2. **Device Authentication**
   - App requires device PIN, pattern, fingerprint, or face unlock
   - Leverages your device's built-in security
   - No app-specific passwords to remember

3. **No Network Transmission**
   - No automatic uploads or syncing
   - No background data transmission
   - Only network activity is subscription verification (through app stores)

4. **Secure Exports**
   - Exports (PDF/CSV) are encrypted in transit if shared via encrypted channels (email, cloud storage)
   - You control where exports are saved or shared

5. **Automatic Corruption Recovery**
   - Database integrity checks
   - Automatic backup before major operations
   - Corruption detection and recovery mechanisms

### Your Security Responsibilities

You are responsible for:
- **Keeping your device secure** with a PIN, password, or biometric lock
- **Not sharing your device** with others if you want to keep your health data private
- **Creating regular backups** using the app's backup feature
- **Storing backups securely** (we recommend password-protected cloud storage or encrypted email)
- **Keeping your device's operating system updated** for the latest security patches

---

## Data You Choose to Export

My Med Journal allows you to export your health data for sharing with healthcare providers or personal backup.

### Export Features

**PDF Export:**
- Professional medical report format
- Includes selected date range and categories
- Optionally includes your name and date of birth
- Generated locally on your device
- **You control** where to share it (email, print, save to device)

**CSV Export:**
- Spreadsheet format for data analysis
- Compatible with Excel, Google Sheets, etc.
- Includes selected date range and categories
- Generated locally on your device
- **You control** where to share it

**Backup & Restore:**
- Full encrypted database backup
- JSON metadata file with backup info
- Saved locally or shared to your chosen destination
- Can be restored on the same or different device
- **Important:** Backups contain all your health data - store them securely!

### Export Privacy

When you export data:
- ✅ Export is generated **locally on your device**
- ✅ **We do not receive** copies of your exports
- ✅ **You choose** what data to include (date range, categories)
- ✅ **You choose** where to send or save it (email, cloud storage, device storage)
- ✅ **You are responsible** for securing exported files

**Privacy Tip:** When sharing exports with healthcare providers, use encrypted email or secure patient portals when available.

---

## Subscription and Payment

My Med Journal offers optional premium subscriptions with enhanced features.

### How Subscriptions Work

**Payment Processing:**
- All subscriptions are purchased through **Google Play Store** (Android) or **Apple App Store** (iOS)
- Billing is handled **entirely by Google or Apple**
- We **do not process** payments directly
- We **do not store** your payment information
- We **do not have access** to your credit card or payment details

**Subscription Information We Receive:**
- ✅ **Subscription status:** Active, expired, or canceled
- ✅ **Subscription tier:** Free trial, monthly, or annual
- ❌ **We do NOT receive:** Your name, email, payment method, billing address, or transaction history

**Managing Subscriptions:**
- Subscriptions are managed through your **Google Play** or **App Store** account
- Cancel or modify subscriptions in your app store settings
- Refund requests must be submitted to Google or Apple (per their policies)

**No Personal Data Required:**
- No email address needed
- No account creation required
- Anonymous subscription verification

---

## Third-Party Services

My Med Journal uses minimal third-party services to provide essential functionality.

### Services We Use

1. **Google Play Billing (Android) / Apple StoreKit (iOS)**
   - **Purpose:** Subscription management and verification only
   - **Data Shared:** Anonymous subscription status (active/inactive)
   - **Privacy Policy:** [Google Play](https://policies.google.com/) / [Apple](https://www.apple.com/legal/privacy/)

2. **Device Operating System APIs**
   - **Purpose:** Core app functionality
   - **Examples:** File system access, notifications, biometric authentication
   - **Data Shared:** None - all processing is local

### Services We Do NOT Use

- ❌ **Analytics Services** (Google Analytics, Firebase, Mixpanel, etc.)
- ❌ **Crash Reporting** (Crashlytics, Sentry, etc.)
- ❌ **Advertising Networks** (AdMob, Facebook Ads, etc.)
- ❌ **Social Media SDKs** (Facebook SDK, Twitter SDK, etc.)
- ❌ **Cloud Storage** (AWS, Google Cloud, Azure, etc.)
- ❌ **Data Collection Tools** of any kind

**We intentionally keep third-party code to an absolute minimum to protect your privacy.**

---

## Children's Privacy

### Age Requirements

My Med Journal is designed for general audiences and is not specifically directed at children under 13.

**Children Under 13:**
- We do not knowingly collect information from children under 13
- If you are under 13, please do not use the app or enter any information
- Parents/guardians should supervise use by children

**Children 13-17:**
- Parental or guardian consent may be required depending on your location
- We collect no more data from minors than from adults (which is no data)
- All data stays local on the device

If we become aware that a child under 13 has entered information into the app, we will... actually, we can't delete it because we don't have access to it. The data exists only on the user's device.

---

## Your Privacy Rights

You have complete control over your data because it's stored only on your device.

### Your Rights

**Right to Access:**
- ✅ View all your data through the Timeline screen
- ✅ Search and filter your entries
- ✅ Export to PDF or CSV at any time

**Right to Edit:**
- ✅ Edit any entry through the Timeline screen
- ✅ Update your profile information anytime
- ✅ Modify your preferences and settings

**Right to Delete:**
- ✅ Delete individual entries through the Timeline
- ✅ Clear all app data through device settings
- ✅ Uninstall the app to remove all data permanently

**Right to Export (Data Portability):**
- ✅ Export data to PDF or CSV format
- ✅ Create encrypted backups
- ✅ Move data to another device via backup/restore

**Right to Object:**
- Since we don't collect or process your data, there's nothing to object to
- You control all data processing on your device

### Exercising Your Rights

You can exercise these rights directly within the app:
- **Access:** Tap Timeline to view all entries
- **Edit:** Tap any entry to edit it
- **Delete:** Tap delete icon on any entry
- **Export:** Settings → Share/Export Journal
- **Backup:** Settings → Backup & Restore

**No request needed - you're always in control.**

---

## California Privacy Rights (CCPA)

If you're a California resident, the California Consumer Privacy Act (CCPA) provides you with specific rights regarding your personal information.

**Under CCPA, you have the right to:**
- Know what personal information is collected
- Know whether personal information is sold or disclosed
- Say no to the sale of personal information
- Access your personal information
- Request deletion of your personal information
- Not be discriminated against for exercising these rights

**For My Med Journal:**
- ❌ We collect **no personal information**
- ❌ We sell **no personal information**
- ❌ We share **no personal information** with third parties
- ✅ All data stays **on your device**
- ✅ You have **complete access and control**

Since we don't collect any data, CCPA's data collection and sale provisions don't apply.

---

## European Union Privacy Rights (GDPR)

If you're in the European Union, the General Data Protection Regulation (GDPR) provides you with specific rights.

**Under GDPR, you have the right to:**
- Access your personal data
- Rectify inaccurate data
- Erase your data ("right to be forgotten")
- Restrict processing
- Data portability
- Object to processing

**For My Med Journal:**
- ❌ We are **not a data controller** (we don't control your data)
- ❌ We are **not a data processor** (we don't process your data on behalf of others)
- ✅ **You are the sole controller** of your data
- ✅ All data processing happens **locally on your device**
- ✅ You can exercise all GDPR rights **directly in the app**

**Legal Basis for Processing:**
Since we don't process your data, no legal basis is required from us. You process your own data on your device for your own purposes.

---

## HIPAA Compliance Note

**Important:** My Med Journal is **not a HIPAA-covered entity**.

We are not:
- ❌ A healthcare provider
- ❌ A health plan
- ❌ A healthcare clearinghouse
- ❌ A business associate of any HIPAA-covered entity

**Therefore:**
- HIPAA regulations **do not apply** to our app
- We are **not required** to comply with HIPAA
- Your data is **not protected health information (PHI)** under HIPAA when stored in our app
- However, we implement **privacy practices that align with HIPAA principles**

**If you share exported data with a healthcare provider:**
- Once shared, that data may become part of your official medical record
- Your healthcare provider is responsible for HIPAA compliance regarding that data
- You control what data to share and when

---

## International Data Transfers

**There are no international data transfers** because:
- Your data stays on your device
- We don't have servers or cloud storage
- No data crosses borders via our app

If you travel internationally with your device, your data travels with you, but no data is transmitted to us or any servers.

---

## Data Retention

**How Long Data is Kept:**
- Your data is retained on your device **indefinitely** until you delete it
- Individual entries can be deleted anytime
- All data is deleted when you uninstall the app

**We don't have retention policies** because we don't have access to your data.

**Best Practice:** We recommend:
- Creating monthly backups
- Keeping backups for at least 1 year
- Deleting old entries you no longer need (optional)

---

## Changes to This Privacy Policy

We may update this Privacy Policy from time to time to reflect:
- Changes in app features
- Changes in laws or regulations
- Improvements to privacy practices
- User feedback

**When We Update:**
- We will update the "Last Updated" date at the top
- We will increment the version number
- Material changes will be announced through the app
- Continued use after changes constitutes acceptance

**Where to Find Updates:**
- In the app: Settings → Privacy Policy
- Online: [Your privacy policy URL]
- GitHub: [Your repository URL]/PRIVACY_POLICY.md

**You can always check the version number and date to see if the policy has changed.**

---

## Contact Information

If you have questions, concerns, or requests regarding this Privacy Policy or your data, please contact us:

**Support Email:** [support@mymedjournal.app or your email]  
**Website:** [Your website URL]  
**GitHub:** [Your GitHub repository URL]

**Response Time:** We typically respond within 48 hours (2 business days).

---

## Summary - Privacy Policy in Plain English

**What We Collect:**
- Nothing. Zero. Nada.

**Where Your Data Goes:**
- Nowhere. It stays on your phone.

**Who Can See Your Data:**
- Only you (and anyone you share your phone or exports with).

**How We Use Your Data:**
- We can't use what we can't see.

**How to Delete Your Data:**
- Delete entries in the app or uninstall the app.

**Your Privacy:**
- 100% private. We can't see your data even if we wanted to.

---

## Legal Disclaimer

**Medical Information:**
This app is for personal health tracking only. It is not intended to:
- Diagnose any medical condition
- Provide medical advice or treatment
- Replace consultation with healthcare professionals
- Be used in medical emergencies

**Always consult qualified healthcare providers for medical advice.**

**Data Loss:**
While we implement security measures and backup features, we are not responsible for data loss due to:
- Device failure, damage, or theft
- User error or accidental deletion
- Software bugs or errors
- Operating system changes
- Failure to create backups

**You are responsible for maintaining your own backups.**

---

## Transparency Report

**Data Requests Received:** 0 (we have no data to provide)  
**Data Shared with Third Parties:** 0 (we have no data to share)  
**Government Requests:** 0 (we have no data to provide)  
**Data Breaches:** 0 (we have no centralized data to breach)

**Last Updated:** October 17, 2025

---

## Version History

| Version | Date | Changes |
|---------|------|---------|
| 1.0.0 | October 17, 2025 | Initial public release - comprehensive privacy policy |

---

## Acknowledgment

By downloading, installing, or using My Med Journal, you acknowledge that you have read and understood this Privacy Policy and agree to its terms.

---

**My Med Journal - Your Health. Your Privacy. Your Control.**

*This Privacy Policy is effective as of October 17, 2025 and will remain in effect except with respect to any changes in its provisions in the future, which will be in effect immediately after being posted in the app and on this page.*

---

**Questions?** We're here to help. Contact us at [your support email].

**Want even more privacy details?** Check our End User License Agreement (EULA) and App Store privacy declarations for additional information about how we handle your privacy.
