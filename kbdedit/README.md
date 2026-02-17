# KbdEdit / MSKLC Source Files

Source files for building the native Windows keyboard layout (.dll).

## Files

- `nokwtsplusplus.kbe` — KbdEdit project file (primary source)
- `nokwtsplusplus.klc` — MSKLC-format export

## Building

Open `nokwtsplusplus.kbe` in [KbdEdit](http://www.kbdedit.com/) and build the installer.

The built installer should be uploaded to the [Releases](https://github.com/izenynn/layout-nokwtsplusplus/releases) page.

## Limitations

The native Windows layout does not support:
- CapsLock <-> Backspace swap (use EPKL or other remapping tools)
- Ligatures may have issues in some apps when built with MSKLC (KbdEdit handles them properly)
