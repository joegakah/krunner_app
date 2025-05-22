# Krunner
## An embedded Cube Runner Unity Game in Flutter

This repository contains a **Cube Runner** game developed in Unity and embedded within a Flutter application. It demonstrates how to integrate a Unity 3D game seamlessly into a Flutter app, enabling interactive gaming experiences alongside Flutter's UI capabilities.

---

## Features

- **Unity game embedded as a Flutter widget** for Android and iOS.
- Real-time **communication between Flutter and Unity** allowing message passing and control.
- Utilizes `flutter_embed_unity` package for embedding and interaction.
- Supports pausing and resuming Unity game state when Flutter widget is disposed or rendered.
- Example of controlling Unity game objects from Flutter UI (e.g., setting rotation speed).
- Handles touch inputs and sends events from Unity back to Flutter.

---

## Getting Started

### Prerequisites

- Unity 2022.3 LTS (or compatible version)
- Flutter SDK
- Android Studio / Xcode for platform-specific builds

### Setup

Since this repository **already contains the Unity project embedded inside the Flutter app**, the setup is straightforward:

1. **Clone the repository** from GitHub to your local machine.

2. **Open the project** in your preferred IDE (e.g., Android Studio, VS Code).

3. **Set up Flutter for Unity integration:**

   - The Unity project is located inside the `unity/` folder within the Flutter project root.
   - The Unity project has been pre-configured and exported for Flutter embedding.
   - Ensure you have the `flutter_embed_unity` or `flutter_unity_widget` package installed by running:
     ```
     flutter pub get
     ```
   - No need to import or export the Unity project yourself since it is already included.

4. **Run the Flutter app:**

   - Use `flutter run` to launch the app on your device or emulator.
   - The embedded Unity Cube Runner game will load automatically within the Flutter UI.

## References

- This project uses the `flutter_embed_unity` package for embedding Unity in Flutter apps.
- For detailed setup and examples, refer to the [flutter_embed_unity documentation](https://pub.dev/packages/flutter_embed_unity) and example projects.
- Additional tutorials and integration guides:
  - Embedding Unity games in Flutter apps with `flutter_unity_widget` [source](https://blog.codemagic.io/how-to-embed-an-android-unity-game-in-a-flutter-app/)
  - Developing mobile games using Unity and Flutter [source](https://devvibe.com/develop-mobile-game-using-unity-and-flutter/)

---

## License

Specify your license here.

---

This README provides a comprehensive guide to running and extending the embedded Cube Runner Unity game within a Flutter application, leveraging the powerful combination of Unity's 3D capabilities and Flutter's UI framework.

Citations:
[1] https://blog.codemagic.io/how-to-embed-an-android-unity-game-in-a-flutter-app/
[2] https://devvibe.com/develop-mobile-game-using-unity-and-flutter/
[3] https://pub.dev/packages/flutter_embed_unity/versions/1.2.2
[4] https://github.com/juicycleff/flutter-unity-view-widget
[5] https://pub.dev/packages/flutter_embed_unity/example
[6] https://pub.dev/documentation/flutter_embed_unity/latest/
[7] https://medium.ionicfirebaseapp.com/flutter-unity-3d-widget-for-embedding-unity-in-the-flutter-e6126eb4902c
[8] https://www.dhiwise.com/post/implementing-magic-with-flutter-unity-widget-complete-guide
[9] https://github.com/jamesncl/flutter_embed_unity/blob/main/README.md
[10] https://github.com/learntoflutter/flutter_embed_unity

---
Answer from Perplexity: pplx.ai/share