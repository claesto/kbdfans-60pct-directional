# kbdfans-60pct-directional

> Custom 60% keyboard layout for the KBDFans 60% PCB

## Requirements

This project depends on:

* [QMK Firmware](https://github.com/qmk/qmk_firmware/)

## Usage

1. Read the [QMK documentation](https://docs.qmk.fm/#/newbs_getting_started) on how to get the QMK firmware
2. Put this project in the `qmk_firmware/keyboards/dz60/keymaps/` folder
3. Build with `$ make dz60:kbdfans-60pct-directional`

## Key layout

#### Layer 0

```
,-----------------------------------------------------------------------------------------.
| Esc |  1  |  2  |  3  |  4  |  5  |  6  |  7  |  8  |  9  |  0  |  -  |  =  |   Bkspc   |
|-----------------------------------------------------------------------------------------+
| Tab    |  Q  |  W  |  E  |  R  |  T  |  Y  |  U  |  I  |  O  |  P  |  [  |  ]  |    \   |
|-----------------------------------------------------------------------------------------+
| Caps    |  A  |  S  |  D  |  F  |  G  |  H  |  J  |  K  |  L  |  ;  |  '  |    Enter    |
|-----------------------------------------------------------------------------------------+
| Shift     |  Z  |  X  |  C  |  V  |  B  |  N  |  M  |  ,  |  .  |    RSh    |  U  | FN  |
|-----------------------------------------------------------------------------------------+
| Ctrl |  Alt  |  Cmd  |              Space                | Cmd | RAlt |  L  |  D  |  R  |
`-----------------------------------------------------------------------------------------'
```

#### Layer 1

```
,-----------------------------------------------------------------------------------------.
| ` ~ |  F1 |  F2 |  F3 |  F4 |  F5 |  F6 |  F7 |  F8 |  F9 |  F10 |  F11 |  F12 |   Del  |
|-----------------------------------------------------------------------------------------+
|     | RGB T | RGB M | HUE+ | HUE- | SAT+ | SAT- | VAL+ | VAL- |   |  |  |   |   RESET   |
|-----------------------------------------------------------------------------------------+
|         |     |     |     |     |     |     |     |     |     |     |     |             |
|-----------------------------------------------------------------------------------------+
| Mute     | Vol- | Vol+ | Play | Prev |  Next  |     |     |     |     |     |   |   |   |
|-----------------------------------------------------------------------------------------+
|      |       |       |                                   |     |      |     |     |     |
`-----------------------------------------------------------------------------------------'
```

## Mod-Tap keys

Read the QMK documentation on [mod-tap keys](https://docs.qmk.fm/#/feature_advanced_keycodes?id=mod-tap).

#### Right shift
* Tap `right shift` = `/`
* Hold `left shift` + tap `right shift` = `?`
* Hold `right shift` = regular shift function

#### Caps lock
* Tap `caps lock` = Toggle caps lock
* Hold `caps lock` = `Left CTRL`
