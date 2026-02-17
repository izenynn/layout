# KbdEdit / MSKLC Source Files

Source files for building the native Windows keyboard layout (.dll).

## Files

- `nokwtsplusplus.klc` — MSKLC-format layout definition (also compatible with KbdEdit)

## Building

Use [KbdEdit](http://www.kbdedit.com/) to open the `.klc` file and build the installer.

The built installer should be uploaded to the [Releases](https://github.com/izenynn/layout-nokwtsplusplus/releases) page.

## Limitations

The native Windows layout does not support:
- CapsLock <-> Backspace swap (use EPKL or other remapping tools)
- Ligatures may have issues in some apps when built with MSKLC (KbdEdit handles them properly)
