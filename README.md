# Splash Screen
This asset allows you to create custom and dynamic splash screens for your Unity project.

## Features

- **Simple Splash Screen:** Just add your game's logo image.
- **Animated Splash Screen:** Add a sequence of images to create an animation.
- **Multiple Splash Screens:** Create different splash screens for various parts of your game.

## Installation
This package has a mandatory dependency: com.unity.ugui. To ensure correct functionality, please make sure it's installed in your project via the Unity Package Manager.

### Installing the UI Package

1.  Go to **Window > Package Manager**.

2.  Go to **search bar** and write → **com.unity.ugui**.

3.  Click the **Install** button.

### Installing the Splash Screen Package

1. Make sure you are using **Unity 2022.3 or later**.

2. Open your project's `manifest.json` file and add the following line inside the `dependencies` section:

```json
"com.supertactic.splashscreen": "1.0.1"
```

---

## How to Use

1.  **Import the Samples** from the Package Manager.

2.  Navigate to the **`Runtime/Prefabs`** folder.

3.  **Drag and drop** the `SplashScreenMovie` or `SplashScreenUI` prefab into your scene. The asset is ready to use right away.

4.  For any custom changes, it's highly recommended to **create a Prefab Variant** first before adjusting its properties.