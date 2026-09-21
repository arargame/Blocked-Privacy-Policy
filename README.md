# Blocked: Pixel Panzer – Privacy Policy

**Last Updated: 22 September 2026**

This privacy policy explains what data the mobile game **Blocked: Pixel Panzer** (package name `com.arargames.blocked`, "the Game") processes, why, and what choices you have.

The Game is developed and published by **Arar Games** ("we", "us").  
Contact: **arargame@hotmail.com** | **korayarar@gmail.com**

---

## Summary

The Game does **not** collect or request personally identifiable information (PII) such as your real name, email address, phone number, physical address, contacts, photos, microphone, or camera access, and it does **not** track your precise GPS location.

However, the Game **does** show advertisements, **does** offer in-app purchases, **does** collect anonymous gameplay telemetry to balance levels and tanks, and **does** integrate Google Play services. These involve data processing that is described in detail below.

---

## Data We Process

### 1. Analytics & Telemetry (Google Analytics for Firebase)

The Game uses **Google Analytics for Firebase** (Firebase Analytics) to monitor game performance, evaluate player progression funnels, balance tank combat difficulty, and improve player experience.

Data processed includes:

- **Anonymous Gameplay Events:** Level started (`level_started`), level completed (`level_completed`), level failed (`level_failed`), shop interactions, powerup upgrades, boss battle outcomes, rewarded ad revive responses (`second_chance_used`), and navigation events.
- **Screen Transitions (`screen_view`):** Navigated screens (such as `MainMenuScreen`, `GameBoard`, `PauseScreen`, `GameOverScreen`).
- **Anonymous User Properties:** Progression stage bucket (`progress_bucket`), unlocked level, control style preference, and device performance tier (`device_tier`).
- **Pseudonymous Player Identifier:** A randomly generated local GUID assigned upon installation (`PlayerId`). This identifier is completely pseudonymous and contains no personally identifiable data.
- **Firebase App Instance ID:** An anonymous, auto-generated pseudonymous identifier created by Google Play Services to route diagnostic and telemetry events.

**GDPR / Privacy Safeguard:**  
In accordance with GDPR, KVKK, and Google UMP guidelines, Firebase Analytics data collection is **disabled by default** on app startup (`firebase_analytics_collection_enabled = false`). Telemetry collection is only enabled after user consent choices are established through the consent form.

Learn more:
- [Google Privacy Policy](https://policies.google.com/privacy)
- [Firebase Privacy and Security in Firebase](https://firebase.google.com/support/privacy)

---

### 2. Advertising (Google AdMob)

The Game displays banner, interstitial, and rewarded video ads through **Google AdMob**.

To do this, Google may collect and process:

- Your **advertising identifier** (Android Advertising ID). The Game declares the `com.google.android.gms.permission.AD_ID` permission for this purpose.
- Technical device data such as device model, operating system version, language, and screen resolution.
- **Approximate location derived from your IP address** (country/city level, not precise GPS location).
- Interaction data such as ad impressions, clicks, and video completion.

This data is used to deliver, measure, and — where permitted — personalise ads, and to detect invalid traffic and fraud.

Google acts as an independent controller and/or processor for this data:
- [Google Privacy Policy](https://policies.google.com/privacy)
- [How Google uses information from sites or apps that use our services](https://policies.google.com/technologies/partner-sites)

---

### 3. Consent Management (Google User Messaging Platform)

If you reside in the **European Economic Area (EEA), the United Kingdom, Switzerland, or Türkiye**, the Game shows a consent form powered by the **Google User Messaging Platform (UMP)** on initial launch.

- Your consent choices are stored **locally on your device** (including IAB TCF 2.2 standard values).
- Personalised advertising and analytics telemetry are only used if you consent to them.
- **You can change or fully withdraw your consent at any time** from within the Game: open **Options → PRIVACY OPTIONS**. This reopens the consent form. Withdrawing consent is as easy as giving it.

---

### 4. In-App Purchases (Google Play Billing)

The Game offers optional in-app purchases through **Google Play Billing**:

| Product ID | Description |
| :--- | :--- |
| `10_gold_product` | 10 Gold Pack |
| `50_gold_product` | 50 Gold Pack |
| `100_gold_product` | 100 Gold Pack |
| `REMOVE_ADS` | Removes Banner & Interstitial Advertisements |

- All payment information is processed exclusively and securely by **Google Play**. Arar Games never sees, receives, or stores your credit card, bank details, or billing address.
- The Game stores **purchase tokens** returned by Google Play in its local encrypted save file. This is done solely to verify and grant entitlements offline. These tokens stay on your device and are not transmitted to external servers.

---

### 5. Google Play Games Services

The Game integrates **Google Play Games Services** for sign-in, achievements, and leaderboards.

- If you sign in, your Play Games profile (such as gamer tag and player ID) and submitted high scores are processed by Google and may be visible on public leaderboards.
- Signing in is entirely **optional**. The Game is fully playable offline without signing in.

---

### 6. Local Game Data & Offline Storage

Your progress is stored in a save file on your own device (`savegame.json`). It contains: level progress, high scores, gold balance, unlocked tank skills, and Game settings.

- It also contains a **randomly generated player identifier (GUID)** created locally on your device. This identifier is not linked to your real identity.
- This file is stored locally in private application storage and is **not** uploaded to any external server.
- Uninstalling the Game or clearing application data removes it.

---

### 7. Notifications

The Game may schedule **local reminder notifications** (for example, regarding your daily reward streak) using the Android AlarmManager.

- These are generated entirely offline on your device. No data leaves your device for this purpose, and no push notification service is used.
- You can disable notifications at any time in device settings (**Android Settings → Apps → Blocked → Notifications**).

---

### 8. Crash and Performance Data

Google Play may automatically collect anonymous crash, ANR, and performance reports. We use these only to fix bugs and improve game stability.

---

## Legal Basis (GDPR / KVKK)

For users in the EEA, the UK, Switzerland, and Türkiye (Law No. 6698 / KVKK):

- **Consent (Art. 6(1)(a) GDPR):** For personalised advertising and analytics telemetry storage, requested through the consent form and revocable at any time.
- **Contractual necessity (Art. 6(1)(b) GDPR):** For delivering in-app purchases you have chosen to make via Google Play.
- **Legitimate interests (Art. 6(1)(f) GDPR):** For fraud and invalid-traffic prevention, game security, bug diagnostics, and basic non-personalised advertising that keeps the Game free.

---

## Data Retention & Deletion

- **Consent choices:** Stored locally on your device until you change them, clear app data, or uninstall the Game.
- **Save data & purchase tokens:** Stored locally on your device until you reset your progress or uninstall the Game.
- **Analytics data:** Retained in Google Analytics according to Google's standard retention period (up to 14 months), after which it is automatically deleted.
- **Data Deletion Inquiries:** Because we do not collect or hold identifiable personal data on external servers, most requests can be managed directly on your device:
  - Reset or delete your advertising ID: **Android Settings → Privacy → Ads**
  - Change your consent: **Options → PRIVACY OPTIONS** inside the Game
  - Manage your Google data: [Google Account settings](https://myaccount.google.com/data-and-privacy)
  - For inquiries regarding telemetry records associated with your random Player ID, contact us at **arargame@hotmail.com**.

---

## Children's Privacy

The Game is **not directed at children under 13** (or under 16 in the EEA). It serves advertising and is not part of the Google Play Families programme.

We do not knowingly collect personal data from children. If you believe a child has provided personal information through third-party services in the Game, contact us at **arargame@hotmail.com** and we will take prompt corrective action.

---

## Third-Party Services Used

For full transparency, the third-party SDKs integrated into the Game:

| Service | Provider | Purpose | Privacy Reference |
| :--- | :--- | :--- | :--- |
| **Google Analytics for Firebase** | Google LLC | Gameplay telemetry & optimization | [Firebase Privacy](https://firebase.google.com/support/privacy) |
| **Google AdMob** | Google LLC | In-game advertising | [AdMob Privacy](https://policies.google.com/technologies/partner-sites) |
| **Google User Messaging Platform (UMP)** | Google LLC | Consent management (GDPR/KVKK) | [Google Privacy](https://policies.google.com/privacy) |
| **Google Play Billing** | Google LLC | In-app purchases | [Google Play Terms](https://play.google.com/about/play-terms/) |
| **Google Play Games Services v2** | Google LLC | Sign-in, achievements & leaderboards | [Google Privacy](https://policies.google.com/privacy) |

---

## Changes to This Policy

If this policy changes, the updated version will be published in this repository with a new "Last Updated" date. Material changes affecting how data is used will, where required by law, be accompanied by a renewed consent request.

---

## Contact

Questions about this privacy policy:

**Arar Games**  
Developer: Koray Arar  
Location: Bursa, Türkiye  
Email: **arargame@hotmail.com** | **korayarar@gmail.com**  
Website: [https://arargames.com](https://arargames.com)  
GitHub: [https://github.com/arargame](https://github.com/arargame)
