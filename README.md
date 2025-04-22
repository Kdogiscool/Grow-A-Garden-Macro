# Grow-A-Garden-Macro

A macro for automating fruit collection in Roblox's Grow a Garden game.

**⚠️ THIS IS A VERY EARLY PRE-ALPHA VERSION!**  
Expect bugs and limited functionality. This might not even work with your garden setup. The next update will be massive and will include the ability to create your own paths! :)

## Pre-Alpha Release Notes

### Features
- Automatically collects fruits by spamming the E key (every 2ms).
- Optional auto-sell feature using a key sequence.
- Discord webhook support for status notifications (Starting, Stopping, Fruits Sold).
- Auto-update feature to download new versions from GitHub.

### Usage
1. Download `Grow-A-Garden-Macro.exe` from the [Releases](https://github.com/Kdogiscool/Grow-A-Garden-Macro/releases) page.
2. Run the executable.
3. In the GUI:
   - Check "Collect Fruits (Spam E)" to enable fruit collection.
   - Check "Auto Sell Fruits" to enable automatic selling.
   - Set the number of movement loops (1-10).
   - Add a Discord webhook URL in the Webhook tab (optional).
4. Press F1 to start, F2 to pause, and F3 to stop.  
   **Note**: The "Pause" feature (F2) is likely broken. Use F3 to stop instead.

### Requirements
- Windows OS.
- Roblox with Grow a Garden game.
- Screen resolution set to 1920x1080 (other resolutions are not supported in this pre-alpha version).

### Important Notes
- **Center your camera** before starting the macro (a disclaimer will remind you on first run).
- **Resolution Limitation**: This only works on 1920x1080 resolution. Support for other resolutions will be added in a future update.
- **Garden Side Limitation**: This only works on the **RIGHT side** of the garden. Support for the left side will be added in the next update.
- This pre-alpha version may be buggy—use at your own risk!
- The "Settings" and "Credits" tabs are placeholders and will be implemented in future updates.

## Auto-Update
To enable auto-updates:
1. Run the macro once to generate `GardenMacroConfig.ini` in your Documents folder. (this isnt turned on by default bc ive heard aniviruses hate auto updaters)
2. Open the config file and set `EnableAutoUpdate=1`.
3. Save the file.
The macro will check for updates on startup and prompt you to download new versions.

## Future Updates
The next update will be massive! Planned features include:
- Support for custom movement paths.
- Support for all garden sides (including the left side).
- Support for different screen resolutions.
- Bug fixes and improved stability.
- Functional Pause feature.
- Implementation of Settings and Credits tabs.
