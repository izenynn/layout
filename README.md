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

### Windows (Native)

Download the installer from the [Releases](https://github.com/izenynn/layout-nokwtspp/releases) page.

### Windows (EPKL)

1. Install [EPKL](https://github.com/DreymaR/BigBagKbdTrixPKL)
2. Copy the `epkl/NokwtsPP/` folder into EPKL's `Layouts/` directory
3. Add this line to your `EPKL_Layouts_Override.ini` under `[pkl]`:
   ```ini
   layout = NokwtsPP\NktPP-eD_ANS:NokwtsPlusPlus
   ```
4. Run EPKL

### macOS

TODO

## Structure

```
epkl/       EPKL layout files (for BigBagKbdTrixPKL)
kbdedit/    KbdEdit / MSKLC source files
mac/        macOS layout files
```
