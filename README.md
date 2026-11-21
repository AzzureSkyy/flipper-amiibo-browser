<div align="center">

![amiibo](https://assets.nintendo.com/image/upload/f_auto/q_auto/dpr_1.5/Dev/aem-component-demo/logo-amiibo-glow)

</div>

# Flipper Amiibo Browser

A Flipper Zero app that browses amiibo `.nfc` files by game and emulates them.
Despite the supposed MIT license anyone does not have to right to sell this
Say outside of Nintendo direct use for intended purposes alone,
this app should not be taken and resold, and or distributed on any platform with permissions
to do so, the app is licensed by Nintendo and not MIT,granting resall permissions.
Mit license will be removed eventually when I get around too it until then the official 
GitHub Readme is a required read of any software informations above and beyond vauge and misdirective 
licensing that doesnt have the authority to grant resale of a Nintendo Centric product.
Before any official implementation of an official nature the app would require work for appropriate behavior
for any truly licensed Ninendo device, the flipper is the only item that this function to a minimum standard on
and all flipper applications are free to use,for people who own a flipper and do not have capacity for physical Amiibos
only Nintendo reserves the right to sell digital Amiibos in the future on a choosen platform ad NFC to be used as a Nintendo
Product. However this application Violates no sales rights as it boasts the use and possible purchase of real Amiibos
and the sale of digitally licensed NFC by Nintendo if desired at a later date. 
Nothing in the app is Nefarious or Anti Nintendo, and does not to my knowledge and the knowledge of my AI companion collect or misue any data,
Further unofficial forks or approvals in other channels are not my responsibility and explicitly rely on the responsibility 
of the User but more importantly the methods and intentions of the person altering the app.

Rights Reserved:Nintendo Corporation 
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
