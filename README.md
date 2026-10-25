# 🧮 CalcVault

![CalcVault Feature Banner](https://files.catbox.moe/40w85q.png)

<div align="center">

<img src="https://files.catbox.moe/3vfqqh.png" alt="CalcVault App Logo" width="128" height="128" style="border-radius: 28px; box-shadow: 0 10px 30px rgba(124, 58, 237, 0.4);" />

**Your Ultimate Military-Grade Stealth Vault Hidden Behind a Fully Functional Calculator**

[![Version](https://img.shields.io/badge/Version-4.3.1_(Build_40301)-7c3aed?style=for-the-badge&logo=android)](https://github.com/Manohar630/Calcvault-V1)
[![Android](https://img.shields.io/badge/Platform-Android_7.0+_(API_24--36)-34d399?style=for-the-badge&logo=android)](https://github.com/Manohar630/Calcvault-V1)
[![Kotlin](https://img.shields.io/badge/Kotlin-2.1.0-7f52ff?style=for-the-badge&logo=kotlin)](https://kotlinlang.org)
[![Jetpack Compose](https://img.shields.io/badge/Jetpack_Compose-BOM_2024.12-4285f4?style=for-the-badge&logo=jetpackcompose)](https://developer.android.com/jetpack/compose)
[![SQLCipher](https://img.shields.io/badge/Database-SQLCipher_AES--256-10b981?style=for-the-badge&logo=sqlite)](https://www.zetetic.net/sqlcipher/)
[![Media3](https://img.shields.io/badge/ExoPlayer-Media3_1.5-ff007f?style=for-the-badge&logo=google)](https://developer.android.com/media/media3)
[![Privacy](https://img.shields.io/badge/Privacy-100%25_Offline_/_Zero_Cloud-fbbf24?style=for-the-badge&logo=shield)](https://github.com/Manohar630/Calcvault-V1)
[![License](https://img.shields.io/badge/License-MIT-gray?style=for-the-badge)](LICENSE)

<br/>

<!-- Google Play Store Direct Download Badge -->
<p align="center">
  <a href="https://play.google.com/store/apps/details?id=com.calcvault.safe" title="Download on Google Play Store">
    <img src="https://play.google.com/intl/en_us/badges/static/images/badges/en_badge_web_generic.png" height="70" alt="Get it on Google Play" />
  </a>
</p>

> 📲 **Direct Google Play Store Link:**  
> [👉 **Click Here to View / Download on Google Play Store**](https://play.google.com/store/apps/details?id=com.calcvault.safe) *(Package: `com.calcvault.safe`)*

<br/>

> **Zero Cloud Telemetry • No Accounts Required • Military-Grade Local Encryption**  
> All private photos, 4K videos, audio tracks, sensitive documents, and personal notes are AES-256-GCM encrypted and strictly stored on your physical device.

</div>

---

## 📸 Play Store Visual Showcase (Screenshots)

| 01. Calculator Disguise & PIN | 02. Encrypted Vault Home | 03. Private Photos Gallery | 04. ExoPlayer Video Player |
| :---: | :---: | :---: | :---: |
| [![Calculator Disguise](https://files.catbox.moe/pzvffe.png)](https://files.catbox.moe/pzvffe.png) | [![Encrypted Vault Home](https://files.catbox.moe/l9bni3.png)](https://files.catbox.moe/l9bni3.png) | [![Photos Gallery](https://files.catbox.moe/4dswup.png)](https://files.catbox.moe/4dswup.png) | [![Video Player](https://files.catbox.moe/3nf8zz.png)](https://files.catbox.moe/3nf8zz.png) |
| *Functional math engine & PIN gateway* | *Category cards, storage bars & search* | *AES-256 on-the-fly streaming & zoom* | *Hardware accelerated, PiP & gestures* |

| 05. Audio Vault & Playback | 06. Documents & Secret Notes | 07. Branded Icon Camouflage | 08. Intruder Selfie & Consent |
| :---: | :---: | :---: | :---: |
| [![Audio Vault](https://files.catbox.moe/qojbo2.png)](https://files.catbox.moe/qojbo2.png) | [![Documents & Notes](https://files.catbox.moe/6v06m8.png)](https://files.catbox.moe/6v06m8.png) | [![Icon Camouflage](https://files.catbox.moe/zkquj3.png)](https://files.catbox.moe/zkquj3.png) | [![Intruder Selfie](https://files.catbox.moe/s1s19l.png)](https://files.catbox.moe/s1s19l.png) |
| *Background media session & waveforms* | *Built-in PDF reader & secure notepad* | *Dynamic launcher activity camouflage* | *Opt-in CameraX silent threat capture* |

---

## 📖 Table of Contents

- [✨ Overview](#-overview)
- [📸 Play Store Visual Showcase](#-play-store-visual-showcase-screenshots)
- [🌟 Key Pillars \& Feature Matrix](#-key-pillars--feature-matrix)
- [🏗️ System Architecture](#️-system-architecture)
- [🔐 Cryptography, Privacy \& Security Deep-Dive](#-cryptography-privacy--security-deep-dive)
- [📱 Android Permissions Reference](#-android-permissions-reference)
- [📁 Project Structure](#-project-structure)
- [🚀 Quickstart \& Developer Setup](#-quickstart--developer-setup)
- [🧪 Testing \& Quality Gates](#-testing--quality-gates)
- [📦 Build \& Release Pipeline](#-build--release-pipeline)
- [🛡️ Git Safety Checklist](#️-git-safety-checklist)
- [👨💻 Author \& Credits](#-author--credits)

---

## ✨ Overview

**CalcVault** is a state-of-the-art privacy vault and media sanctuary engineered for Android. Built natively with **Kotlin 2.1**, **Jetpack Compose (Material You / M3)**, **Room with SQLCipher**, and **Media3 ExoPlayer**, it disguises an impenetrable AES-256 encrypted storage vault behind an authentic, fully operational scientific calculator.

Standard vault apps upload sensitive media to unverified third-party cloud servers, display predatory tracking trackers, or leave unencrypted thumbnails exposed in system caches. **CalcVault is 100% local-first and anti-forensic**:
- **Zero Cloud Footprint:** No external servers, no tracking telemetry, no logins, no email signups.
- **True Calculator Stealth:** Functions as an authentic daily calculator with realistic audio and haptic feedback until your secret numeric PIN followed by `=` unlocks the vault.
- **Authenticated Encryption:** All files are chunk-encrypted using **AES-256-GCM** with random 12-byte IVs; metadata and notes are locked in a **SQLCipher-encrypted database**.
- **Anti-Forensics & Privacy:** Automated `.nomedia` sentinels prevent Android's MediaScanner and third-party apps from discovering hidden items; memory sweeps clear decrypted buffers immediately upon session exit.
- **Emergency Protection:** Includes decoy fake vault PINs, face-down quick lock, instant app icon camouflage, and panic wipes.

---

## 🌟 Key Pillars & Feature Matrix

### 1. 🧮 Deceptive Calculator Stealth Engine
- **Fully Working Math Calculator:** Addition, subtraction, multiplication, division, percentages, and floating-point math with instant calculation.
- **Authentic Haptics & Acoustic Feedback:** Realistic tactile button presses and low-latency audio tones (ECC sound pipeline).
- **Stealth Gateway:** Type your secret PIN (2 to 4 digits) and press `=` to instantly launch the encrypted sanctuary.
- **Recovery Fallback:** Long-press `=` to initiate the secure recovery process using security questions or BIP39 recovery passphrases.

### 2. 🔒 Military-Grade Encryption & Anti-Forensics
- **AES-256-GCM Cipher:** Strong Galois/Counter Mode authenticated encryption ensuring both data confidentiality and cryptographic integrity.
- **SQLCipher SQLite Database:** File metadata, album hierarchies, tags, and secure notes are safeguarded inside an encrypted SQLite database.
- **PBKDF2 Key Derivation:** Master encryption keys are derived using PBKDF2 with HMAC-SHA256 across **15,000 iterations**.
- **Hardware Keystore Integration:** Master secrets can be securely bound to the hardware-backed Android Keystore and unlocked via Biometrics (Fingerprint / Face).
- **Automated EXIF Sanitizer:** Strips sensitive GPS coordinates, device models, and timestamps from incoming photos to eliminate metadata leakage.
- **`.nomedia` Sentinel:** Encrypted directories include invisible `.nomedia` tags to block Android MediaStore indexers permanently.

### 3. 🖼️ Private Photos Gallery & In-Vault Viewer
- **On-the-Fly Encrypted Streaming:** Powered by Coil with custom `EncryptedThumbnailFetcher` to decode encrypted images in-memory without ever saving unencrypted image files to disk.
- **Advanced Touch Gestures:** Fluid pinch-to-zoom, pan, double-tap zoom, rotation, and high-performance thumbnail caching.
- **Album Organization:** Create personalized photo albums, filter by favorites, search by filename or date, and batch export back to device gallery.

### 4. 🎬 High-Performance ExoPlayer Video Vault
- **Encrypted Media3 ExoPlayer:** Custom `EncryptedMediaDataSource` streams multi-gigabyte 4K and 1080p videos directly from encrypted ciphertext chunks.
- **Picture-in-Picture (PiP):** Seamless background and overlay PiP playback while multitasking.
- **Gesture Control System:** Vertical edge swipe for display brightness and system volume; horizontal swipe for timeline scrubbing.
- **Playback Controls:** Playback speed customization (0.5x to 2.0x), 10s instant skip/rewind, aspect ratio fitting, and auto-rotation.

### 5. 🎵 Audio Vault & Background Playback
- **Foreground Audio Service:** Native `VaultAudioPlaybackManager` maintains audio playback through a foreground service with lock screen and notification media controls.
- **Interactive Visualizer:** Audio waveform visualizer, shuffle, repeat, and playlist queuing for encrypted music, podcasts, and voice memos.

### 6. 📄 Encrypted Documents & Secret Notes
- **In-Vault PDF Reader:** Native multi-page PDF rendering (`PdfViewerScreen`) with zoom, page jumps, and search within encrypted storage.
- **Secure Text Editor:** Markdown-friendly notes editor for passwords, secret journals, and financial records, protected under SQLCipher encryption.

### 7. 📸 Intruder Selfie & Threat Detection
- **CameraX Silent Capture:** Captures high-resolution front-facing camera snapshots whenever an incorrect PIN is entered.
- **Strict Opt-In Consent:** Adheres strictly to Google Play privacy policies with explicit opt-in disclosure dialog (`08_intruder_consent.png`).
- **Audit Logs:** Intruder records log the intruder's photo, timestamp, and attempted PIN with a 50-photo / 25MB automated storage limit.

### 8. 🎭 Camouflage Disguise & Decoy Vault
- **Dynamic App Icon Switcher:** Switch the launcher icon on the fly to **Calculator**, **Weather Vault**, **Compass Vault**, **Notes Vault**, or **Clock Vault** using dynamic activity aliases.
- **Decoy Fake Vault:** Enter an alternative decoy PIN under coercion to unlock a convincing, clean decoy vault with harmless dummy data.
- **Face-Down Quick Lock:** Built-in accelerometer listener (`FaceDownService`) instantly closes the vault and returns to the locked calculator when the phone is flipped face down.
- **Emergency Panic Wipe:** One-tap cryptographic destruction of all encryption keys and local databases.

### 9. 🗑️ Secure Trash & Storage Janitor
- **Recycle Bin with 30-Day Auto-Purge:** Trashed items are retained safely for 30 days before irreversible wiping, allowing one-tap restoration.
- **Visual Storage Breakdown:** Categorized storage bars displaying space utilized by Photos, Videos, Audio, Documents, Notes, and Trash.
- **Janitor Cleanup Service:** `TempFileJanitor` automatically purges temporary cache files on app cold start and lifecycle transitions.

---

## 🏗️ System Architecture

```
┌────────────────────────────────────────────────────────────────────────┐
│                        ANDROID DEVICE HARDWARE                         │
│     CameraX Sensor • Accelerometer • Biometric Sensor • Storage        │
└──────────────────────────────────┬─────────────────────────────────────┘
                                   │
                                   ▼
┌────────────────────────────────────────────────────────────────────────┐
│               ANDROID NATIVE SECURITY & ENGINE LAYER (KOTLIN)          │
│                                                                        │
│   CryptoEngine.kt (AES-256-GCM Authenticated Encryption Pipeline)      │
│   ├── PBKDF2 Master Key Derivation (15,000 Iterations + HMAC-SHA256)   │
│   ├── Android Keystore Hardware Wrapper + Biometric Prompt             │
│   ├── Chunked Encrypted File Streaming & In-Memory Decryption          │
│   └── ExifSanitizer.kt (Strips GPS & camera metadata upon import)      │
│                                                                        │
│   Database Layer (Room + SQLCipher)                                    │
│   ├── CalcVaultDatabase (Full-database AES-256 PRAGMA encryption)      │
│   └── VaultFileDao • NoteDao • IntruderLogDao • SettingsDao            │
│                                                                        │
│   Media & System Services                                              │
│   ├── EncryptedMediaDataSource.kt (ExoPlayer custom ciphertext source) │
│   ├── VaultAudioPlaybackManager.kt (Foreground media playback service) │
│   ├── FaceDownService.kt (Instant sensor-based privacy lock)           │
│   ├── AppIconService.kt (Dynamic launcher alias switcher)             │
│   └── TempFileJanitor.kt (Zero-plaintext cache hygiene sweeper)        │
└──────────────────────────────────┬─────────────────────────────────────┘
                                   │
                           Dagger Hilt 2.52
                 (Repository & Domain Use-Case Layer)
                                   │
                                   ▼
┌────────────────────────────────────────────────────────────────────────┐
│                 PRESENTATION LAYER (JETPACK COMPOSE / M3)              │
│                                                                        │
│   MainActivity.kt • AppNavigation.kt (Animated Screen State Machine)    │
│   ├── CalculatorScreen.kt (Genuine math engine + secret PIN gateway)   │
│   ├── VaultHomeScreen.kt (Categorized cards, storage bars, quick jump) │
│   ├── PhotosScreen.kt & PhotoViewerScreen.kt (Coil encrypted loader)   │
│   ├── VideosScreen.kt & VideoPlayerScreen.kt (ExoPlayer + PiP)         │
│   ├── AudioScreen.kt & AudioPlayerScreen.kt (Foreground audio session) │
│   ├── DocumentsScreen.kt & PdfViewerScreen.kt (Encrypted PDF viewer)   │
│   ├── NotesScreen.kt & NoteEditorScreen.kt (Encrypted SQLCipher notes) │
│   ├── IntruderLogsScreen.kt (CameraX audit records & consent dialog)   │
│   ├── StorageAnalysisScreen.kt (Storage metrics & cleanup tools)       │
│   └── VaultSettingsScreen.kt (Disguise icons, decoy PIN, backup)       │
│                                                                        │
│   Theme: Material Design 3 • Material You Dynamic Color • Glassmorphic │
└────────────────────────────────────────────────────────────────────────┘
```

---

## 🔐 Cryptography, Privacy & Security Deep-Dive

CalcVault is architected around an uncompromising **zero-knowledge, local-first security model**:

1. **Cryptographic Primitives:**
   - **Symmetric Cipher:** AES-256 in Galois/Counter Mode (`AES/GCM/NoPadding`) provides both confidentiality and built-in message authentication.
   - **Initialization Vector:** A cryptographically secure random 12-byte IV is generated for every encrypted file and prepended to the ciphertext.
   - **Tag Length:** 128-bit authentication tag ensures tampering detection.
2. **Key Derivation & Hierarchy:**
   - **User PIN:** User enters a 2–4 digit secret PIN.
   - **Salt:** Unique 16-byte cryptographically secure random salt generated on initial setup.
   - **PBKDF2:** Master key derived via `PBKDF2WithHmacSHA256` with **15,000 iterations**.
   - **Database Security:** SQLCipher database encrypted using keys derived directly from the master secret.
3. **Zero Plaintext Leakage:**
   - Images and thumbnails are loaded via custom streaming decoders that decrypt bytes directly into memory buffers.
   - Any video frames or temporary files generated during system sharing are isolated in private app cache directories and swept automatically by `TempFileJanitor`.
4. **Google Play Store Data Safety Compliance:**
   - **Data Collection:** **NO** (Google Play defines data collection as transmitting user data off the device).
   - **Data Sharing:** **NO**.
   - **Target SDK:** 36 (Android 15+ / 16KB Page Size compliant).
   - **Network Usage:** Purely local; no cloud syncing. Internet permission is restricted to serving Google AdMob ads in the free version (with one-time Lifetime VIP ad-free upgrade).

---

## 📱 Android Permissions Reference

| Permission | Category | Purpose | User Disclosure |
|---|---|---|---|
| `CAMERA` | Runtime | In-vault camera capture and optional Intruder Selfie | Clear opt-in consent dialog before activation |
| `RECORD_AUDIO` | Runtime | Audio capture during in-vault video recording only | Only requested when switching to Video recording mode |
| `READ_MEDIA_IMAGES` | Runtime | Importing photos from device into encrypted vault (Android 13+) | Standard system media picker prompt |
| `READ_MEDIA_VIDEO` | Runtime | Importing videos from device into encrypted vault (Android 13+) | Standard system media picker prompt |
| `READ_MEDIA_AUDIO` | Runtime | Importing audio tracks into encrypted vault (Android 13+) | Standard system media picker prompt |
| `READ_EXTERNAL_STORAGE` | Runtime | Legacy file import support for Android 7.0–12 | Requested only on legacy OS versions |
| `POST_NOTIFICATIONS` | Runtime | Background audio playback controls and security alerts | System notification permission prompt |
| `USE_BIOMETRIC` | Normal | Optional Fingerprint / Face Unlock for fast access | Configured in Vault Settings |
| `VIBRATE` | Normal | Authentic tactile haptic feedback on calculator button taps | Standard system utility |
| `FOREGROUND_SERVICE` | Normal | Uninterrupted background audio playback | Persistent notification showing current track |
| `BILLING` | Normal | Google Play Billing for Lifetime VIP ad-free upgrade | In-app purchase sheet |

---

## 📁 Project Structure

```
Calcvault-V1/
├── app/                                  # Android Native Kotlin & Jetpack Compose Application
│   ├── src/main/AndroidManifest.xml      # Manifest, launcher aliases & service declarations
│   ├── src/main/java/com/calcvault/app/
│   │   ├── CalcVaultApp.kt               # Application entry point, Hilt setup & cache janitor
│   │   ├── MainActivity.kt               # Jetpack Compose host & lifecycle coordinator
│   │   ├── crypto/                       # Cryptographic Engine
│   │   │   └── CryptoEngine.kt           # AES-256-GCM, PBKDF2 & Keystore integrations
│   │   ├── data/                         # Data Layer
│   │   │   ├── billing/BillingManager.kt # Google Play In-App Billing integration
│   │   │   ├── database/                 # Room + SQLCipher database & DAOs
│   │   │   ├── datastore/                # DataStore preferences & secure keys
│   │   │   ├── model/                    # VaultFile, Note, IntruderLog, AppSettings
│   │   │   └── repository/               # VaultRepository, SettingsRepository, NotesRepository
│   │   ├── domain/                       # Business Logic & Use Cases
│   │   │   ├── service/                  # ExifSanitizer, MediaImportHelper, MediaExportHelper
│   │   │   └── usecase/                  # IntruderCapture, Backup, AppIconDisguise
│   │   ├── navigation/                   # Jetpack Compose Navigation & transitions
│   │   ├── service/                      # Background services
│   │   │   ├── EncryptedMediaDataSource  # Custom ExoPlayer data source for encrypted media
│   │   │   ├── VaultAudioPlaybackManager # Foreground audio playback service
│   │   │   ├── FaceDownService.kt        # Accelerometer sensor face-down detector
│   │   │   └── AppIconService.kt         # Dynamic launcher activity alias switcher
│   │   ├── ui/                           # Jetpack Compose UI
│   │   │   ├── calculator/               # Realistic Calculator Screen & theme engines
│   │   │   ├── vault/                    # Vault Home, Photos, Videos, Audio, Docs, Notes, Trash
│   │   │   ├── security/                 # PIN setup, Decoy PIN, Security questions, Permissions
│   │   │   ├── settings/                 # Disguise launcher icons & preferences
│   │   │   └── theme/                    # Material 3 color schemes, shapes & motion tokens
│   │   └── util/                         # Constants, TempFileJanitor, InAppUpdateManager
│   └── build.gradle.kts                  # App build configuration (SDK 36, Version 4.3.1)
├── play-listing/                         # Official Play Store listing assets
│   ├── feature-graphic.png               # 1024x500 Official Play Store Banner
│   ├── icon-512.png                      # 512x512 High-Resolution App Icon
│   └── en-US/                            # Store listing metadata (title, short/full description)
├── screenshots/                          # Showcase screenshots for store & repository
│   ├── 01_calculator.png                 # Calculator interface & secret PIN entry
│   ├── 02_vault_home.png                 # Encrypted vault dashboard & categories
│   ├── 03_photos_gallery.png             # Private photo gallery & albums
│   ├── 04_video_player.png               # ExoPlayer in-vault video player
│   ├── 05_audio_vault.png                # Audio vault with background playback
│   ├── 06_documents.png                  # Encrypted documents & secret notepad
│   ├── 07_disguise_icons.png             # Dynamic disguise icon selection
│   └── 08_intruder_consent.png           # Intruder selfie consent dialog
├── src/                                  # Web prototype (React 19 + TypeScript + Vite)
│   ├── components/                       # Web UI components & calculator engine
│   └── lib/                              # Web encryption & storage prototypes
├── docs/                                 # Play Store compliance, data safety & monetization
├── gradle/                               # Gradle wrapper and version catalog (libs.versions.toml)
├── keystore.properties                   # Local signing configuration (git-ignored)
├── calcvault-release.jks                 # Production release keystore (git-ignored)
└── package.json                          # Web prototype dependencies
```

---

## 🚀 Quickstart & Developer Setup

### Prerequisites
- **Android Studio**: Ladybug / Hedgehog or newer (Ladybug Feature Drop recommended)
- **Java Development Kit (JDK)**: `17` or higher
- **Android SDK Platform**: API 36 / 35 / 34 installed
- **Node.js**: `20.x` or higher (optional, for web prototype)
- **Git**

### 1. Clone the Repository
```bash
git clone https://github.com/Manohar630/Calcvault-V1.git
cd Calcvault-V1
```

### 2. Configure Keystore Credentials
For release signing, create a `keystore.properties` file in the project root:
```properties
CALCVAULT_STORE_FILE=calcvault-release.jks
CALCVAULT_STORE_PASSWORD=your_keystore_password
CALCVAULT_KEY_ALIAS=calcvault
CALCVAULT_KEY_PASSWORD=your_key_password
```
*(Debug builds work automatically without requiring a custom keystore).*

### 3. Open in Android Studio
1. Open Android Studio and choose **Open an existing project**.
2. Select the `Calcvault-V1` folder.
3. Allow Gradle to sync dependencies automatically.

---

## 🧪 Testing & Quality Gates

CalcVault incorporates comprehensive automated testing layers to guarantee stability:

### Run Pure JVM Unit Tests
Executes unit tests for PIN encryption, PBKDF2 derivation, recovery codes, import limits, and mathematical calculations:
```bash
./gradlew testDebugUnitTest
```

### Run On-Device UIAutomator Tests
Executes end-to-end device tests that unlock the calculator with a PIN and traverse all vault categories:
```bash
./gradlew connectedAndroidTest
```

### Run Web Prototype Tests (Vitest & Playwright)
```bash
# Unit tests
npm test

# End-to-end Playwright tests
npm run test:e2e
```

---

## 📦 Build & Release Pipeline

### 1. Build Android Debug APK (Full VIP Access Unlocked)
Compiles a debug build with full VIP features permanently enabled (`FREE_BUILD=true`), allowing complete access to all premium capabilities without in-app purchase:
```bash
# Windows
gradlew.bat assembleDebug

# Linux / macOS
./gradlew assembleDebug
```
Artifact generated at:  
`app/build/outputs/apk/debug/app-debug.apk`

#### Install Directly via ADB:
```bash
adb install -r app/build/outputs/apk/debug/app-debug.apk
```

### 2. Build Production Release Android App Bundle (AAB)
Compiles a production-ready, signed `.aab` bundle with version **4.3.1 (Build 40301)** optimized with R8/Proguard:
```bash
# Windows
gradlew.bat bundleRelease

# Linux / macOS
./gradlew bundleRelease
```
Artifact generated at:  
`app/build/outputs/bundle/release/app-release.aab`

### 3. Build Standalone Production Release APK
```bash
# Windows
gradlew.bat assembleRelease

# Linux / macOS
./gradlew assembleRelease
```
Artifact generated at:  
`app/build/outputs/apk/release/app-release.apk`

---

## 🛡️ Git Safety Checklist

To protect sensitive keys, signing configurations, and private credentials, adhere strictly to these rules:

- [x] **Keystores & Properties:** `*.jks`, `*.keystore`, and `keystore.properties` are strictly excluded in `.gitignore` and must **never** be committed.
- [x] **Fail-Closed Release Signing:** The release build fails closed if signing credentials are missing, preventing accidental debug-key release artifacts.
- [x] **No Unapproved Git Pushes:** Always review staged diffs with `git status` and `git diff` before executing commits.
- [x] **Zero Plaintext In-Repo:** No master passwords, user data, or personal photos are ever included in the repository.

---

## 👨💻 Author & Credits

- **Developer & Creator:** **Manohar** ([@Manohar630](https://github.com/Manohar630))
- **Email Contact:** [smanohar33733@gmail.com](mailto:smanohar33733@gmail.com)
- **Google Play Package:** [`com.calcvault.safe`](https://play.google.com/store/apps/details?id=com.calcvault.safe)
- **Project Repository:** [Calcvault-V1](https://github.com/Manohar630/Calcvault-V1)

---

<div align="center">
  <sub>CalcVault is designed and engineered by Manohar. Built with ❤️ for uncompromised privacy, security, and digital peace of mind.</sub>
</div>
