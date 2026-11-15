# EasyEffects Handheld Presets
EasyEffects presets for handheld gaming PCs and laptops for [EasyEffects](https://github.com/wwmm/EasyEffects).

All the following presets come with spatial audio, only EQ changes per device:

- Universal
- Laptop
- Basshead
- Claw
- XAX
- LeGo2


# Installation on any distribution, in desktop mode only:
Install [EasyEffects](https://github.com/wwmm/EasyEffects), launch it, import the profile of your choice and click on it to load it.


# Installation on [Anatase](https://github.com/anatase-org/anatase), with gamescope support:
In Plasma session first, install the [EasyEffects](https://github.com/wwmm/EasyEffects) flatpak, launch it, import the preset of your choice and click on it to load it. 

You can now open the gamemode session, EasyEffects will start automatically with your last selected profile.

If you want to have EasyEffects on desktop session too, you can check "Autostart on login" in the preferences.


# Optional: Automatic Preset Switching

You can use [EasyEffects](https://github.com/wwmm/EasyEffects) preset autoloading to automatically enable or disable audio processing depending on the connected device.

1. **Create an empty preset** in EasyEffects with no effects enabled.
2. **Open the Preset Autoloading section** in EasyEffects.
3. **Assign a preset from this repository** to your speakers.
4. **Assign the empty preset** to your headphones or any other device you want to exclude from processing.

EasyEffects will automatically switch presets based on the active audio device, applying your chosen effects to the speakers while leaving other devices unprocessed.
