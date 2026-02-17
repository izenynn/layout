# NokwtsPlusPlus

A custom keyboard layout designed for programming, with a built-in Wide mod and a custom AltGr symbol layer.

## Layout

### Base Layer

```
`~  9(  3#  1!  5%  7&  \|  6^  2@  0)  4$  8*  =+
 z   m   r   l   f  [{   j   y   o   u  _-  /?
  n   t   h   s   b  ]}   c   d   e   i   a  '"
   x   q   w   k   v  <>   p   g  ,;  .:
```

### AltGr Layer (Programming Symbols)

```
 --  --  --  --  --  --  --  --  --  --  --  --  --
  '   <   >   "   #  --   $  ::   [   ]   %   @
   !   -   +   =   _  --   |  ->   (   )  ?   ñ
    ^   /   *   \  ../  --  ~   &   {   }
```

Ligatures: `::` (double colon), `->` (arrow), `../` (parent dir)

### Special Keys

- **CapsLock <-> Backspace**: Full swap (EPKL only)
- **A key (SGCap)**: AltGr gives `?`, AltGr+Shift gives `¿`, AltGr gives `ñ`, AltGr+Shift gives`Ñ`

## Installation

Download the assets from the [Releases](https://github.com/izenynn/layout-nokwtsplusplus/releases) page.

### Windows (Native)

1. Download `nokwtspp-vX.X.X-windows.exe`
2. Run the installer

### Windows (EPKL)

1. Install [EPKL](https://github.com/DreymaR/BigBagKbdTrixPKL)
2. Download `nokwtspp-vX.X.X-epkl.zip`
3. Extract the `NokwtsPP/` folder into EPKL's `Layouts/` directory
4. Add this line to your `EPKL_Layouts_Override.ini` under `[pkl]`:
   ```ini
   layout = NokwtsPP\NktPP-eD_ANS:NokwtsPlusPlus
   ```
5. Run EPKL

### MacOS

1. Download `nokwtspp-vX.X.X-mac.keylayout`
2. Copy it to `~/Library/Keyboard Layouts/`
3. Log out and back in (or reboot)
4. Add the layout in System Settings > Keyboard > Input Sources

## Structure

```
epkl/       EPKL layout files (for BigBagKbdTrixPKL)
kbdedit/    KbdEdit source and MSKLC export files
mac/        macOS layout files
```
