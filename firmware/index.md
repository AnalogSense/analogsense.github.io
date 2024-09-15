# Patched firmware with full analog report

Some keyboards do support analog input but [with severe limitations](https://www.youtube.com/watch?v=-pyBl7InRv8). To allow you to make the most of your keyboard, we provide custom firmware with full analog report functionality.

## Keychron Q1 HE (Knob)

1. To install this firmware, you will need [QMK Toolbox](https://github.com/qmk/qmk_toolbox/releases/latest).
2. Download the firmware appropriate for your keyboard model:
  - [ANSI](keychron_q1_he_ansi_encoder_via.bin) ← 1-row enter key; left shift is followed by a letter, typically `Z`
  - [ISO](keychron_q1_he_iso_encoder_via.bin) ← 2-row enter key; left shift is followed by a symbol, typically `\|`
  - [JIS](keychron_q1_he_jis_encoder_via.bin) ← 2-row enter key; left shift is followed by a letter, typically `Z`
3. Drag the .bin file into the QMK Toolbox (or press "Open" to select it).
4. Tick the "Auto-Flash" checkbox.
5. Unplug your keyboard.
6. Hold the Escape key while plugging it in. The firmware will now be flashed and your keyboard will be usable again in just a few seconds.

[Compare changes to upstream firmware.](https://github.com/Keychron/qmk_firmware/compare/hall_effect_playground...AnalogSense:qmk_firmware:far-q1-he)
