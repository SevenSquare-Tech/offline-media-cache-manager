Offline Media Cache Manager

offline-media-cache-manager is a Flutter plugin that allows you to cache
and display network images, SVGs, and Lottie animations with disk
caching and offline support.

---

✨ Features

- 📦 Disk caching for network media
- 🖼️ Supports network images
- 🎨 Supports SVG rendering
- 🎬 Supports Lottie animations
- 📡 Works offline after first load
- 👀 Visibility detection support
- 🔌 Cross-platform (Android & iOS)

---

📦 Installation

Add the dependency in your pubspec.yaml:

    dependencies:
      offline-media-cache-manager: ^1.0.5

Then run:

    flutter pub get

---

🚀 Environment

Requirement Version

---

Dart SDK ^3.9.2
Flutter >=3.3.0

---

📚 Dependencies

- flutter_svg
- lottie
- plugin_platform_interface
- visibility_detector

---

🧩 Supported Platforms

- ✅ Android
- ✅ iOS

---

🛠️ Basic Usage

Display Cached Network Image

    // Example usage (adjust according to your widget API)
    CacheNetworkImage(
      url: "https://example.com/image.png",
    )

Display SVG

    CacheNetworkSvg(
      url: "https://example.com/image.svg",
    )

Display Lottie Animation

    CacheNetworkLottie(
      url: "https://example.com/animation.json",
    )

⚠️ Replace widget names with actual ones if your implementation
differs.

---

📂 Plugin Structure

    android/
    ios/
    lib/
    test/

---

🔧 Platform Configuration

Android

- Package: com.theextremity.cache_network_media
- Plugin Class: CacheNetworkMediaPlugin

iOS

- Plugin Class: CacheNetworkMediaPlugin

---

🧪 Development

Run tests:

    flutter test

Analyze code:

    flutter analyze

---
