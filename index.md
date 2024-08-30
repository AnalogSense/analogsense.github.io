Reading analog keyboard input and making it useful.

## Leverage analogue keyboard input in your favorite games

- [Cyberpunk 2077](cyberpunk-2077)
- [Grand Theft Auto V](gta-v)

## Visualize your analog keyboard input

- [Woot-verlay](https://github.com/DjCrqss/Woot-verlay)
	- The Wooting Anlog SDK has to be installed. You can find the latest installers [here](https://github.com/WootingKb/wooting-analog-sdk/releases).
	- If your analog keyboard is not from Wooting, you will also need the [universal-analog-plugin](https://github.com/calamity-inc/universal-analog-plugin).

## Add analog keyboard input to your own apps & games

There are a few libraries ready for you to use:

​ | [Wooting Analog SDK](https://github.com/WootingKb/wooting-analog-sdk) | [soup::AnalogKeyboard](https://github.com/calamity-inc/Soup/blob/senpai/soup/AnalogueKeyboard.cpp) | [AnalogSense.js](https://github.com/AnalogSense/JavaScript-SDK)
-|-|-|-
Type | Dynamic library using C ABI | C++ class | JavaScript library
Update Model | Needs to be updated by user | Requires recompile | CDN or vendored
Device Support | Only Wooting by default; all devices\* with [our plugin](https://github.com/calamity-inc/universal-analog-plugin) | All devices\* | Wooting, Razer, DrunkDeer

\* "All devices" refers to every analog keyboard that exposes the analog data that we know of, aka. [The List](https://github.com/calamity-inc/universal-analog-plugin/issues/1).
