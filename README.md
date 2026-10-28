​app-debug.apk​
# 🎧 SmartAnything

> [!NOTE]  
> **Source Code Status**: SmartAnything is currently released as pre-built APKs. The full source code will be opened on GitHub in the near future.

> [!NOTE]  
> **Vibecoded**: This app was built and iterated rapidly using AI tools.

---

**SmartAnything** is an Android app built with **Jetpack Compose** that brings customizable device dashboards, gesture volume overlays, system equalizer shortcuts, app launchers, and Samsung DeX mode to wired IEMs, Bluetooth earbuds, speakers, and smart audio glasses.

---

## ✨ Features

### Artwork & Themes
- Dark Mode (`#000000`) and Light Mode (`#FFFFFF`).
- Hand-drawn line art sketches for IEMs, TWS Earbuds, Speakers, and Smart Glasses.
- Dark Mode sketch color inversion.

### One UI Volume Capsule
- Press and hold the hero image to open a One UI-style vertical volume slider overlay.
- Drag up/down to adjust media volume with haptic feedback.
- Configurable press-and-hold action per device (Volume Capsule, Voice Assistant, or Disabled).

### Samsung DeX Desktop Mode
- Multi-column desktop layout with a collapsible sidebar and device selector grid.
- Launch settings: `Auto & Button` (auto-launches when rotating to landscape), `Button Only`, or `Disabled`.

### Home View Modes
- Toggle between **Feature Cards**, **Grid Tiles**, and **Compact List**.

### Reorderable Category Tabs
- Organize utility cards into 3 categories:
  - **Sound & Audio**: Equalizer, Dolby Atmos / Spatial Audio, L/R Stereo Channel Test, Ear Balance
  - **Controls & Launch**: Quick Launch Media Apps, Docked Volume Slider
  - **Utilities & Find**: Find My Earbuds / Glasses, Noise Control, System Sound Settings
- Reorder tabs and cards per device in Edit Layout mode.

### Find My Earbuds & Find My Glasses
- Fullscreen alert with progressive volume ramping (starts low and increases step-by-step).
- Restores original volume when stopped.
- Plays through both audio temples simultaneously for Smart Audio Glasses.

### L/R Stereo Channel Test
- Uses Text-to-Speech (TTS) to speak `"Left Side"` and `"Right Side"` with stereo balance.

---

## 🛠 Tech Stack

- **Framework**: Jetpack Compose (Material 3)
- **Language**: Kotlin 2.2+
- **APIs Used**: `AudioManager`, `AudioEffect`, `TextToSpeech`, `BluetoothAdapter`, `WindowInsetsControllerCompat`.

---

## 🚀 Installation

1. Download the latest `app-release.apk` from the Releases section.
2. Install on an Android device running Android 12 (API 31) or higher.
3. Grant Bluetooth permissions on first launch.

---

## License
MIT License
