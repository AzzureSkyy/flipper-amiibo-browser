<div align="center">

![amiibo](https://assets.nintendo.com/image/upload/f_auto/q_auto/dpr_1.5/Dev/aem-component-demo/logo-amiibo-glow)

</div>

# Flipper Amiibo Browser

A Flipper Zero app that browses amiibo `.nfc` files by game and emulates them.
Despite the supposed MIT license anyone does not have to right to sell this
Say outside of Nintendo direct use for intended purposes alone
this app should not be tzken and resold, and or distributed on any platform with permissions
to do so, the app is licensed by Nintendo and not MIT granteing resall permissions.

## Contents
- `FlipperApp/amiibo_browser/` - app source (`amiibo_browser.c`, `application.fam`) and built `.fap` in `dist/`.
- `Flipper_SD/` - ready-to-copy SD card layout:
  - `apps/NFC/amiibo_browser.fap`
	- `nfc/Amiibo/By_Game/...`
  - `amiibo_index.csv` / `amiibo_index.md` - library index (not needed on the device)

## Install
Copy `Flipper_SD/apps` and `Flipper_SD/nfc` to the root of the Flipper SD card, then open
**Apps > NFC > Amiibo Browser**.

## Build
```
pip install ufbt
cd FlipperApp/amiibo_browser
ufbt          # build
ufbt launch   # install and run over USB
```
Built against official firmware SDK 1.5.1.
