---
layout: default
title: Privacy Policy
description: Fitly Privacy Policy — how we collect, use, and protect your data.
---

# Privacy Policy

<p class="subtitle">Effective date: February 16, 2026</p>

Fitly ("the App") is a personal fitness tracking application. This policy explains what data the App collects, how it is stored, and your choices regarding that data.

## Data We Collect

### Data You Provide

- **Profile information**: name, body weight, height, birth year, and sex (used for calorie calculations and workout personalization).
- **Workout data**: exercises, sets, reps, weights, duration, and session notes.
- **Weekly goals**: calorie targets, active minutes targets, and workout frequency targets.

### Data Collected Automatically

- **Heart rate data**: if you connect a Bluetooth heart rate monitor (e.g., Polar H10), the App records real-time heart rate, RR intervals, and energy expenditure during workouts. This data is stored locally on your device.
- **Body composition data**: if you connect to Android Health Connect, the App reads weight, body fat percentage, height, lean body mass, and bone mass from Health Connect. This data is stored locally on your device.

### Data From Third-Party Services

- **Firebase Authentication**: the App uses Firebase for anonymous sign-in and email magic link authentication. Firebase processes your email address (if you sign in with email) and assigns an anonymous user identifier. See [Google's Privacy Policy](https://policies.google.com/privacy).
- **OneSignal Push Notifications**: if you opt in to push notifications, OneSignal receives a device identifier to deliver notifications. No personal data is shared with OneSignal beyond what is necessary to deliver push messages. See [OneSignal's Privacy Policy](https://onesignal.com/privacy_policy).

## How Data Is Stored

### Local Storage

The majority of your data — workouts, heart rate logs, body composition records, goals, and preferences — is stored **locally on your device** in an SQLite database. This data does not leave your device unless you explicitly export it.

### Cloud Services

- **Firebase**: stores your anonymous user ID, friend codes, and friend list for the social features. If you sign in with email, Firebase stores your email address.
- **OneSignal**: stores a push notification device token if you opt in to notifications.

The App does **not** upload your workout data, heart rate data, or body composition data to any cloud server.

## Bluetooth and Sensor Data

When you connect a Bluetooth heart rate monitor:

- The App uses Bluetooth Low Energy (BLE) to communicate with the device.
- Heart rate, RR intervals, battery level, and energy expenditure are read from the sensor.
- All sensor data is stored locally on your device and is not transmitted to any external server.
- You can disconnect the sensor at any time from Settings.

## Health Connect Integration

When you connect to Android Health Connect:

- The App requests **read-only** access to weight, body fat, height, lean body mass, and bone mass records.
- Data is read from Health Connect and stored locally in the App's database for display on the Progress screen.
- The App does **not** write data to Health Connect.
- You can revoke Health Connect permissions at any time from Android Settings or from the App's Settings screen.

## Data Export and Deletion

- **Export your data**: use Settings > Data > Download My Data to export a full backup of your local database as a JSON file.
- **Automatic backups**: you can configure automatic backups (daily, weekly, or after each workout) that save to a folder you choose on your device.
- **Delete your data**: uninstalling the App removes all locally stored data. To delete cloud data (Firebase account and friend list), you can sign out and delete your account from Settings.

## Data Sharing

We do **not** sell, rent, or share your personal data with third parties for advertising or marketing purposes.

Data is shared with third-party services only as described above (Firebase for authentication, OneSignal for push notifications) and only to the extent necessary to provide those features.

## Children's Privacy

The App is not directed at children under 13. We do not knowingly collect personal information from children under 13.

## Changes to This Policy

We may update this Privacy Policy from time to time. Changes will be posted on this page with an updated effective date.

## Contact

If you have questions about this Privacy Policy or your data, please contact us at:

**Email**: [contact.builtbylee@gmail.com](mailto:contact.builtbylee@gmail.com)
