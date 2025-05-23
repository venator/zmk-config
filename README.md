A firmware for the [Urchin Keyboard](https://github.com/duckyb/urchin) and the [Forager Keyboard](https://github.com/carrefinho/forager), tuned to be used with the [Ergo-L layout](https://ergol.org/).

## Getting started

**Are you trying to make your own ZMK firmware?**
[Here are the steps you need to take.](./GETTING_STARTED.md)

**Do you want to download my keymap?**

> [!IMPORTANT]
> This firmware is meant to be used with the Ergo-L layout. Symbols and accents will be missing with other layouts.

[Download the firmware zip from the latest action run.](https://github.com/venator/zmk-config/actions/workflows/build.yml?query=is%3Asuccess+branch%3Amain) Check [the ZMK docs](https://zmk.dev/docs/user-setup#installing-the-firmware) for instructions on how to flash it.

## Keymap Cheat Sheet (Ergo-L layout)

<div align="center">

  ![urchin-cheatsheet](assets/3x5_ergol_base_navnum.svg)

</div>

## Keymap Layout

<div align="center">

  ![urchin-layout](assets/keymap.svg)

</div>

Diagram generated using [keymap-drawer](https://github.com/caksoylar/keymap-drawer):
```sh
keymap parse -c 10 -z config/urchin.keymap > keymap.yaml
keymap draw keymap.yaml > assets/keymap.svg
```

## References

This layout is inspired by:
- https://ergol.org/claviers/compacts/#kbd_3x5
- https://github.com/OneDeadKey/arsenik
- https://github.com/qmk/qmk_firmware/tree/master/keyboards/ferris/keymaps/default
- https://github.com/duckyb/urchin-zmk-firmware
- https://github.com/ulounge/zmk-urchin
- https://github.com/carrefinho/forager-zmk-module
- https://github.com/manna-harbour/miryoku_zmk
- https://github.com/hbmarchive/ferris-sweep
- https://precondition.github.io/home-row-mods
