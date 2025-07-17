# Analog keyboard input in Cyberpunk 2077

## Using AnalogSense.asi

### Prerequisites

- The Wooting Anlog SDK has to be installed. You can find the latest installers [here](https://github.com/WootingKb/wooting-analog-sdk/releases).
- If your analog keyboard is not from Wooting, you will also need the [universal-analog-plugin](https://github.com/calamity-inc/universal-analog-plugin).

### Setup

1. Download [the latest version of AnalogSense.asi](https://github.com/AnalogSense/AnalogSense.asi/releases/latest/download/AnalogSense.asi).
2. Locate Cyberpunk 2077's **bin/x64** folder. This folder contains the **Cyberpunk2077.exe**.
3. If you're using Cyber Engine Tweaks, you may have a "plugins" folder where you can place the AnalogSense.asi. Otherwise, download [dinput8.dll](https://third-party.files-that-make-your-head-explode.com/ultimate-asi-loader/8.3.0/dinput8.dll) and drop it next to the EXE along with AnalogSense.asi.

### Configuration (Response Curve)

By default, your input is mapped with a linear curve. However, you can add additional points to `%programdata%\AnalogSense\curve_points.json`. You can use [this online tool](https://analogsense.org/Response-Curve-Configurator/) to generate this file for you — it also visualizes & simulates the response curve.
