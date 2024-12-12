Reading analog keyboard input and making it useful.

## Leverage analogue keyboard input in your favorite games

- [Cyberpunk 2077](cyberpunk-2077)
- [Grand Theft Auto V](gta-v)
- [Grand Theft Auto: San Andreas (GTA SA)](gta-sa)
- [Kerbal Space Program](https://github.com/Kristallranke/KSPW00tNow)
- [Space Engineers](https://github.com/Garbius/WootingPlugin)

## Visualize your analog keyboard input

​ | Type | Shows Digital Input (e.g. to see Rapid Trigger) | Device Support |
-|-|-|-
**[Woot-verlay](https://github.com/DjCrqss/Woot-verlay)** | Website connecting to local or LAN server | Yes | Uses [Wooting Analog SDK](https://github.com/WootingKb/wooting-analog-sdk) so needs [a plugin for other devices](https://github.com/AnalogSense/universal-analog-plugin)
**[AnalogSense.js Demo](https://analogsense.org/JavaScript-SDK/demo)** | Website using Chromium-specific API | No | Wooting, Razer, NuPhy, DrunkDeer

## Add analog keyboard input to your own apps & games

​ | Type | Update Model | Device Support
-|-|-|-
**[Wooting Analog SDK](https://github.com/WootingKb/wooting-analog-sdk)** | Dynamic library using C ABI | Needs to be updated by user | Only Wooting by default; [our plugin](https://github.com/AnalogSense/universal-analog-plugin) provides all devices supported by soup::AnalogKeyboard
**[soup::AnalogKeyboard](https://github.com/calamity-inc/Soup/blob/senpai/soup/AnalogueKeyboard.cpp)** | C++ class | Requires recompile | Wooting, Razer Huntsman, NuPhy, DrunkDeer, Keychron, Madlions MAD60HE
**[AnalogSense.js](https://github.com/AnalogSense/JavaScript-SDK)** | JavaScript library | CDN or vendored | Wooting, Razer Huntsman, NuPhy, DrunkDeer, Keychron

## Our list of analog keyboards

We have what we simply refer to as [The List](https://github.com/AnalogSense/universal-analog-plugin/issues/1). This lists all keyboards we know provide their analog data, keyboards we are interested in, and keyboards that unfortunately do not provide their analog data.
