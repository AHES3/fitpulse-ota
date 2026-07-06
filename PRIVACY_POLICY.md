# FitPulse Privacy Policy

Last updated: July 4, 2026

## 1. Overview

FitPulse ("we", "our", "the app") is a fitness tracking application. This policy explains what data we collect, how we use it, and your rights. By using FitPulse, you agree to the practices described here.

## 2. Data We Collect

### 2.1 Account Information
When you create an account, we collect your email address and a password (stored securely via Firebase Authentication). You may optionally provide a display name.

### 2.2 Fitness & Health Data
- **Exercise logs**: Sets, reps, weights, duration, exercise names, workout notes
- **Body metrics**: Weight, body fat percentage (optional, user-entered)
- **Custom metrics**: User-defined tracking values
- **Nutrition data**: Food logs and nutritional information (optional)
- **Recovery/readiness**: Muscle readiness and workout readiness scores

### 2.3 App Usage Data
- Theme preferences (light/dark, accent color)
- Weight unit preference (kg/lbs)
- Workout history and program structures
- Active workout checkpoints (stored locally for session resumption)

### 2.4 Device Data
- App version for update management (via Capacitor Updater)
- Notification permissions status

## 3. How We Collect Data

All fitness and health data is entered directly by you within the app. No data is collected from device sensors, health APIs, or third-party sources without your explicit action.

## 4. How We Use Data

- **Provide core functionality**: Display workout history, track progress, generate statistics
- **Cloud sync**: Keep your data consistent across devices via encrypted Firestore storage
- **App updates**: Check for and deliver over-the-air updates
- **Local notifications**: Remind you of workouts or notify you of updates (only with your permission)

We do **not** sell your data, use it for advertising, or share it with third parties for marketing.

## 5. Data Storage & Processing

### 5.1 Local Storage
Most app data is stored locally on your device using IndexedDB (persistent local cache). Active workout checkpoints are stored in localStorage for session resumption.

### 5.2 Cloud Storage
When you log in and have internet connectivity, your data is synced to Firebase Firestore (Google Cloud, US-based servers). This includes workout logs, body metrics, programs, preferences, and nutrition data. Data is encrypted in transit (TLS) and at rest.

### 5.3 Third-Party Services
- **Firebase (Google)**: Authentication and Firestore database. See [Google's Privacy Policy](https://policies.google.com/privacy).
- **Capacitor (Ionic)**: Cross-platform app runtime. No user data is sent to Ionic by the app itself.

## 6. Data Retention

Your data is retained for as long as your account remains active. You may delete your data at any time:

- **Individual data**: Most entries can be deleted directly within the app.
- **Full account deletion**: Contact us to request complete deletion of your account and all associated data from our servers.

Local data can be removed by clearing app storage or uninstalling the app.

## 7. Data Sharing

We do not share your personal data with third parties except:
- Firebase (Google) for authentication and database hosting — governed by Google's privacy practices.
- If required by law or to protect the rights and safety of users.

We do not use analytics SDKs, crash reporting services, or advertising platforms.

## 8. Your Rights

Depending on your jurisdiction, you may have the right to:
- Access the data we hold about you
- Request correction or deletion of your data
- Withdraw consent for data processing
- Export your data
- File a complaint with your local data protection authority

To exercise these rights, contact us at the email below.

## 9. Children's Privacy

FitPulse is not directed at children under 13 (or under 16 in the EEA). We do not knowingly collect data from children. If you believe a child has provided us with personal data, contact us so we can delete it.

## 10. Changes to This Policy

We may update this policy from time to time. Material changes will be communicated through the app. Continued use after changes take effect constitutes acceptance of the updated policy.

## 11. Contact

For questions about this policy or to request data deletion: **fitpulse.app@ahmeds.dev**

---

This policy is provided as a starting point. Consider having it reviewed by a legal professional for your specific jurisdiction and use case.
