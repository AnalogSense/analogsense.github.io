# Analog keyboard input in Grand Theft Auto V

## Using AnalogSense.asi

### Prerequisites

- The Wooting Anlog SDK has to be installed. You can find the latest installers [here](https://github.com/WootingKb/wooting-analog-sdk/releases).
- If your analog keyboard is not from Wooting, you will also need the [universal-analog-plugin](https://github.com/calamity-inc/universal-analog-plugin).

### Setup

1. Download [the latest release](https://github.com/AnalogSense/AnalogSense.asi/releases/latest/download/x64.zip)
2. Locate Grand Theft Auto V's installation folder. This folder contains the **GTA5.exe**.
3. Drop the dinput8.dll & AnalogSense.asi into this folder.

If you've already used other ASI mods, you may already have a dinput8.dll or are using another ASI loader, in which case you are free to discard the bundled dinput8.dll.

### Configuration (Response Curve)

By default, your input is mapped with a linear curve. However, you can add additional points to `%programdata%\AnalogSense\curve_points.json`. You can use [this online tool](https://analogsense.org/Response-Curve-Configurator/) to generate this file for you — it also visualizes & simulates the response curve.

## Using Stand

[Stand](https://stand.sh/) is a popular mod menu for GTA V that is free to use in story mode and has its own analog keyboard support.

Once Stand is injected, you can navigate to [Game > Analogue Keyboard Support](https://stand.sh/focus#Game%3EAnalogue%20Keyboard%20Support) and enable it.
