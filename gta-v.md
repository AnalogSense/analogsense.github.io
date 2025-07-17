# Analog keyboard input in Grand Theft Auto V

## Using AnalogSense.asi

### Prerequisites

- The Wooting Anlog SDK has to be installed. You can find the latest installers [here](https://github.com/WootingKb/wooting-analog-sdk/releases).
- If your analog keyboard is not from Wooting, you will also need the [universal-analog-plugin](https://github.com/calamity-inc/universal-analog-plugin).

### Setup

1. Locate Grand Theft Auto V's installation folder. This folder contains **GTA5.exe** or **GTA5_Enhanced.exe**.
2. Ensure there is an ASI loader within this folder — [dinput8.dll](https://third-party.files-that-make-your-head-explode.com/ultimate-asi-loader/8.3.0/dinput8.dll) for legacy, [input1_4.dll](https://third-party.files-that-make-your-head-explode.com/ultimate-asi-loader/8.3.0/xinput1_4.dll) for enhanced.
3. Download [the latest version of AnalogSense.asi](https://github.com/AnalogSense/AnalogSense.asi/releases/latest/download/AnalogSense.asi).
4. Drop the AnalogSense.asi into this folder.

### Configuration (Response Curve)

By default, your input is mapped with a linear curve. However, you can add additional points to `%programdata%\AnalogSense\curve_points.json`. You can use [this online tool](https://analogsense.org/Response-Curve-Configurator/) to generate this file for you — it also visualizes & simulates the response curve.

## Using Stand

[Stand](https://stand.sh/) is a popular mod menu for GTA V that is free to use in story mode and has its own analog keyboard support.

Once Stand is injected, you can navigate to [Game > Analogue Keyboard Support](https://stand.sh/focus#Game%3EAnalogue%20Keyboard%20Support) and enable it.
