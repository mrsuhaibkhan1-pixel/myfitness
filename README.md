# My Fitness 🏋️‍♂️

A modern, offline-first Android fitness, habit, and mindfulness tracker designed with a high-contrast **Neo-Brutalist** visual system.

---

## ✨ Features

- **Daily Movement & Activity:** Real-time step counter utilizing hardware step sensors (`Sensor.TYPE_STEP_COUNTER`) with midnight auto-reset offsets.
- **Custom Goal Tracking:** Dynamically editable daily targets for steps and hydration.
- **Dynamic Workout Session Builder:** Create custom routines (e.g., Push, Pull, Legs), add custom exercises, and log sets/reps/weight with real-time completion toggles.
- **Habit & Streak Engine:** Dual-target streak calculations based on meeting both step and hydration thresholds.
- **Mindfulness & Breathing Tool:** Guided Box Breathing (4s Inhale, 4s Hold, 4s Exhale, 4s Hold) with haptic feedback.
- **Local Analytics & Trends:** Minimalist stepped line charts and bar charts for mood and sleep logs.
- **Crisis & Safety Resources:** Dedicated access to emergency help lines and safety hotlines.
- **Privacy & Security:** 100% on-device database encrypted using SQLCipher and Android Keystore.
- **Monetization & Tiers:**
  - **Free:** Full tracking, habit logging, local analytics, CSV export, ad-supported (AdMob Banners, App Open, Rewarded Interstitials).
  - **Pro Subscription:** 100% ad-free experience + PDF summary report generation.

---

## 🛠 Tech Stack & Architecture

- **Language:** Kotlin
- **UI Toolkit:** Jetpack Compose (Material3 + Custom Neo-Brutalist Theme)
- **Architecture:** Clean Architecture + MVVM / MVI with Kotlin Coroutines & Flow
- **Local Database:** Room Database with KSP (Kotlin Symbol Processing)
- **Encryption:** SQLCipher (`net.zetetic:android-database-sqlcipher`)
- **Monetization:** Google Mobile Ads SDK (AdMob)
- **Preferences:** Jetpack DataStore

---

## 🚀 Setup & Build Instructions

1. **Clone the Repository:**
   ```bash
   git clone [https://github.com/your-username/my-fitness-android.git](https://github.com/your-username/my-fitness-android.git)
   cd my-fitness-android
