# EPKL Layout Files

Layout files for [EPKL (BigBagKbdTrixPKL)](https://github.com/DreymaR/BigBagKbdTrixPKL).

These mirror the relevant parts of an EPKL install, so installing is just copying
the folders into your EPKL directory.

## Install

1. Copy `Layouts/NokwtsPP/` into EPKL's `Layouts/`
2. Copy `Files/_eD_PwrStrings.ini` into EPKL's `Files/` (it defines the `&AGxx`
   AltGr-safe symbol sends the layout references)
3. Add this to your `EPKL_Layouts_Override.ini` under `[pkl]`:
   ```ini
   layout = NokwtsPP\NktPP-eD_ANS:NokwtsPlusPlus
   ```
4. Run EPKL

## Structure

- `Layouts/NokwtsPP/BaseLayout_NokwtsPP-eD.ini`: base layout with all key mappings, AltGr layer, ligatures, and CapsLock/Backspace swap
- `Layouts/NokwtsPP/NktPP-eD_ANS/Layout.ini`: ANSI variant pointing to the base layout
- `Files/_eD_PwrStrings.ini`: PowerStrings, including the `&AGxx` AltGr-safe symbol sends
- `EPKL_Layouts_Override.ini`, `EPKL_Settings_Override.ini`: reference copies of the EPKL config

## Notes

- Wide mod is built into the base layout, so no ergo remaps (`mapSC_layout`/`mapSC_extend`) are needed
- The layout is eD-type (edition DreymaR), meaning it uses custom AltGr mappings instead of dead keys
- The AltGr symbol layer goes through AltGr-safe PowerStrings (`&AGxx`) that release AltGr's synthetic LCtrl before emitting each symbol, so apps receive the true character
