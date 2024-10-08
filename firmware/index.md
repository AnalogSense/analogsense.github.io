# Patched firmware with full analog report

Some keyboards do support analog input but with severe limitations. To allow you to make the most of your keyboard, we provide custom firmware with full analog report functionality. [See here for the difference it makes.](https://www.youtube.com/watch?v=-pyBl7InRv8)

## Pre-built firmware images

- Keychron Q1 HE
  - [ANSI](keychron_q1_he_ansi_encoder_via.bin)
  - [ISO](keychron_q1_he_iso_encoder_via.bin)
  - [JIS](keychron_q1_he_jis_encoder_via.bin)
- Keychron Q3 HE
  - [ANSI](keychron_q3_he_ansi_encoder_via.bin)
- Keychron Q5 HE
  - [ANSI](keychron_q5_he_ansi_encoder_via.bin)
- Keychron K2 HE
  - [ANSI](keychron_k2_he_ansi_rgb_via.bin)
  - [ISO](keychron_k2_he_iso_rgb_via.bin)
  - [JIS](keychron_k2_he_jis_rgb_via.bin)

## How to flash custom firmare

1. Download [QMK Toolbox](https://github.com/qmk/qmk_toolbox/releases/latest).
2. Drag the firmware bin file into the QMK Toolbox (or press "Open" to select it).
3. Tick the "Auto-Flash" checkbox.
4. Unplug your keyboard.
5. Hold the Escape key while plugging it in. The firmware will now be flashed and your keyboard will be usable again in just a few seconds.

## ANSI, ISO, or JIS — which to pick?

These refer to different layouts of the keys:

- ANSI has a 1-row high enter key and left shift is followed by a letter, typically `Z`
- ISO has a 2-row high enter key and left shift is followed by a symbol, typically `\|`
- JIS has a 2-row high enter key and left shift is followed by a letter, typically `Z`

## What changes did you make? How do I compile it myself?

You can compare the changes to the upstream Keychron HE firmware [here](https://github.com/Keychron/qmk_firmware/compare/hall_effect_playground...AnalogSense:qmk_firmware:keychron-far).

The .bin files we provide are the result of executing the following on the keychron-far branch:

```bash
make -j keychron/q1_he/ansi_encoder:via && make -j keychron/q1_he/iso_encoder:via && make -j keychron/q1_he/jis_encoder:via
make -j keychron/q3_he/ansi_encoder:via
make -j keychron/q5_he/ansi_encoder:via
make -j keychron/k2_he/ansi_rgb:via && make -j keychron/k2_he/iso_rgb:via && make -j keychron/k2_he/jis_rgb:via
```
