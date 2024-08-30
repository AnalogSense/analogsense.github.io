Reading analog keyboard input and making it useful.

## Leverage analogue keyboard input in your favorite games

- [Cyberpunk 2077](cyberpunk-2077)
- [Grand Theft Auto V](gta-v)

## Visualize your analog keyboard input

​ | Type | Shows Digital Input (e.g. to see Rapid Trigger) | Device Support |
-|-|-|-
**[Woot-verlay](https://github.com/DjCrqss/Woot-verlay)** | Website connecting to local or LAN server | Yes | Uses [Wooting Analog SDK](https://github.com/WootingKb/wooting-analog-sdk) so needs [a plugin for other devices](https://github.com/calamity-inc/universal-analog-plugin)
**[AnalogSense.js Demo](https://analogsense.org/JavaScript-SDK/demo)** | Website using Chromium-specific API | No | Wooting, Razer, DrunkDeer

## Add analog keyboard input to your own apps & games

​ | Type | Update Model | Device Support
-|-|-|-
**[Wooting Analog SDK](https://github.com/WootingKb/wooting-analog-sdk)** | Dynamic library using C ABI | Needs to be updated by user | Only Wooting by default; all devices\* with [our plugin](https://github.com/calamity-inc/universal-analog-plugin)
**[soup::AnalogKeyboard](https://github.com/calamity-inc/Soup/blob/senpai/soup/AnalogueKeyboard.cpp)** | C++ class | Requires recompile | All devices\*
**[AnalogSense.js](https://github.com/AnalogSense/JavaScript-SDK)** | JavaScript library | CDN or vendored | Wooting, Razer, DrunkDeer

\* "All devices" refers to every analog keyboard that exposes the analog data that we know of, aka. [The List](https://github.com/calamity-inc/universal-analog-plugin/issues/1).
