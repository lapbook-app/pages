# LapBook Privacy Policy

**Last Updated:** 2026-05-31
**Version:** 1.1

---

## 1. Overview

LapBook ("the App") is a running training journal that helps runners plan, track, and reflect on their training. This Privacy Policy explains what information we collect, how we use it, and your rights regarding your data.

---

## 2. Information We Collect

### 2.1 Account Information
- **Email address** — used for authentication and account recovery
- **Display name (optional)** — a nickname you choose to personalize your profile

### 2.2 Training Data
- Training plans (chapters, laps, splits)
- Workout values (distance, pace, duration, elevation)
- Personal notes and reflections
- Mood and feel ratings

### 2.3 Location Data
- **Approximate location** (city-level accuracy) — used solely to fetch local weather forecasts for your training days
- Location data is **not stored** on our servers
- Location access requires your explicit permission and can be revoked at any time in Settings

### 2.4 Apple Health Data (Optional)
- **Workout data** (distance, pace, duration) — read from Apple Health to auto-fill your running results
- Data is read **only when you enable** Apple Health in the App settings
- LapBook **does not write** any data to Apple Health
- HealthKit data is used locally and saved as part of your training data in your private iCloud

### 2.5 Device Information
- Timezone identifier — used to display correct dates and weekly boundaries

---

## 3. How We Use Your Information

| Data | Purpose | Storage Location |
|------|---------|-----------------|
| Email | Authentication, account recovery | LapBook server (Supabase) |
| Display name | Personalization | LapBook server (Supabase) |
| Training data | Sync across your devices, backup | Your private iCloud (Apple) |
| Location | Weather forecasts | Not stored |
| Apple Health (workouts) | Auto-fill running results | Your private iCloud (Apple) |
| Timezone | Correct date display | LapBook server (Supabase) |
| Preferences (units, week start) | Personalization | LapBook server (Supabase) |

We do **not**:
- Sell your personal information to third parties
- Use your data for advertising
- Share your training data with other users
- Track your real-time location or running routes

---

## 4. Data Storage & Security

### 4.1 Training Data — Stored in Your Private iCloud
Your training data (chapters, laps, splits, workout values, notes) is stored in **your personal iCloud account** using Apple's CloudKit private database. This means:

- **We do not have access to your training data.** It is stored privately under your Apple ID.
- Data is end-to-end protected by Apple's iCloud security.
- Data syncs automatically across all of your devices signed in with the same Apple ID.
- An active iCloud account is required for the App to function.

### 4.2 Account Data — Stored on LapBook Servers
Account-related information (email, display name, preferences such as distance unit and week start day) is stored on **Supabase** (PostgreSQL), hosted on AWS infrastructure.

- All data transmission uses HTTPS/TLS encryption.
- Row Level Security (RLS) ensures you can only access your own account data.
- Authentication tokens are stored securely in the iOS Keychain.

---

## 5. Data Retention & Deletion

### 5.1 Account Deletion
You can **delete your account** at any time from the Runner profile in the App. Account deletion permanently removes:

- All account data (email, display name, preferences) from LapBook servers

### 5.2 Training Data (iCloud)
Your training data is stored in **your own iCloud**, not on LapBook servers. To remove training data:

- Delete chapters/laps/splits individually within the App, or
- Sign out of iCloud, or
- Disable iCloud sync for LapBook in iOS Settings → [Your Name] → iCloud

Because the data resides under your Apple ID, **LapBook cannot delete it for you**. iCloud data is governed by [Apple's Privacy Policy](https://www.apple.com/legal/privacy/).

Deletion is irreversible.

---

## 6. Third-Party Services

| Service | Purpose | Privacy Policy |
|---------|---------|----------------|
| Apple iCloud (CloudKit) | Storage of your training data | https://www.apple.com/legal/privacy/ |
| Supabase | Account authentication & profile storage | https://supabase.com/privacy |
| Apple WeatherKit | Weather forecasts | https://www.apple.com/legal/privacy/ |

---

## 7. Children's Privacy

LapBook is not directed at children under 13. We do not knowingly collect personal information from children under 13.

---

## 8. Your Rights

You have the right to:
- **Access** your data (available in the App)
- **Correct** your data (editable in the App)
- **Delete** your data (account deletion in Runner profile; training data via iCloud)
- **Export** your data (planned for a future update)

---

## 9. Changes to This Policy

We may update this Privacy Policy from time to time. Changes will be reflected by the "Last Updated" date above. Continued use of the App after changes constitutes acceptance.

---

## 10. Contact

If you have questions about this Privacy Policy, please contact:

**Email:** lapbook.run@gmail.com

---

*This policy applies to the LapBook iOS application.*
