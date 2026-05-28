# Basic Face Filter

A Unity AR face filter app for Android, built with AR Foundation 6.3 and ARCore XR Plugin. The app detects the user's face using the front camera and overlays themed prop filters such as cat ears, devil horns, goblin accessories, and classy gentleman props. Users can switch between filters using on-screen buttons.

## Built With

* Unity 6 (6000.3.16f1)
* AR Foundation 6.3.4
* ARCore XR Plugin 6.3.4
* Universal Render Pipeline (URP)
* TextMesh Pro

## Project Structure

* `Assets/Scenes/Basic_Face_Filter.unity` — Main AR scene
* `Assets/_BasicFaceFilter/Prefabs/` — Face prefab and prop prefabs
* `Assets/_BasicFaceFilter/Scripts/FilterSwitcher.cs` — Script for switching filters during runtime

## Requirements

### Windows PC

* Windows 10 or Windows 11
* Unity Hub installed
* Unity 6 installed
* Android Build Support module installed

### Android Device

* Android 10 or newer
* ARCore-supported device
* USB Debugging enabled

## How to Run

1. Open the project in Unity 6.
2. Go to `File > Build Settings`.
3. Select `Android` platform.
4. Click `Switch Platform`.
5. Make sure `Basic_Face_Filter` is the only enabled scene.
6. Connect your Android phone using a USB cable.
7. Enable `USB Debugging` in Developer Options on your phone.
8. Click `Build and Run`.
9. Choose a new folder to save the build files.
10. Unity will build and install the application automatically on your Android device.

