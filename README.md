# Glasses 3D Player - 3DoF Video Player for VITURE & RayNeo

Glasses 3D Player is a high-performance Android video player designed specifically for XR (Extended Reality) glasses. It features advanced 3DoF (3 Degrees of Freedom) head tracking, spatial stabilization, and support for ultra-high-resolution VR180/SBS content.

## 🚀 Features

- **Multi-Device Support**: Optimized for VITURE (One/Pro) and RayNeo (Air/X2) glasses.
- **Advanced 3DoF Tracking**: Zero-drift head tracking for immersive viewing.
- **VR180 & SBS Support**: Full support for 180-degree immersive and Side-by-Side 3D video.
- **16 KB Alignment**: Optimized for Android 15 and 16 with high-performance memory alignment.
- **Spatial UI**: Intuitive spatial menu that follows your head movement.
- **Smart Stabilization**: Custom-built calibration for RayNeo sensors with persistence across sessions.
- **Premium Performance**: Support for 8K video playback with hardware-accelerated decoding.

## 🛠 Tech Stack

- **Kotlin Multiplatform**: Core logic shared across modules.
- **Jetpack Compose**: Modern, reactive UI.
- **OpenGL ES 2.0**: High-performance spatial rendering and VR warping.
- **Media3 (ExoPlayer)**: Robust video engine with custom FFmpeg extensions.
- **Google Play Billing**: Integrated premium upgrade system.

## 📦 Getting Started

### Prerequisites
- Android Studio Ladybug or later.
- Android SDK 35 (Android 15).
- VITURE or RayNeo AR Glasses.

### Building
1. Clone the repository.
2. Open in Android Studio.
3. Sync Gradle.
4. Run the `:composeApp` module on your Android device.

## 🔧 RayNeo Calibration
For the best experience with RayNeo glasses:
1. Connect your glasses.
2. Go to **Settings > Stabilize RayNeo**.
3. Place the glasses **UPSIDE DOWN** on a flat surface.
4. The app will automatically save the calibration bias for future use.

## 📄 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
*Developed with ❤️ for the XR Community.*
