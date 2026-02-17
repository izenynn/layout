# EPKL Layout Files

Layout files for [EPKL (BigBagKbdTrixPKL)](https://github.com/DreymaR/BigBagKbdTrixPKL).

## Usage

1. Copy the `NokwtsPP/` folder into EPKL's `Layouts/` directory
2. Add this to your `EPKL_Layouts_Override.ini` under `[pkl]`:
   ```ini
   layout = NokwtsPP\NktPP-eD_ANS:NokwtsPlusPlus
   ```
3. Run EPKL

## Files

- `NokwtsPP/BaseLayout_NokwtsPP-eD.ini` — Base layout with all key mappings, AltGr layer, ligatures, and CapsLock/Backspace swap
- `NokwtsPP/NktPP-eD_ANS/Layout.ini` — ANSI variant pointing to the base layout

## Notes

- Wide mod is built into the base layout, so no ergo remaps (`mapSC_layout`/`mapSC_extend`) are needed
- The layout is eD-type (edition DreymaR), meaning it uses custom AltGr mappings instead of dead keys
