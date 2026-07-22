# JustEnoughInputs-JEI

JustEnoughInputs is a TurboWarp extension that adds useful reporters for detecting special keys like Left Shift.

## Features

### Keyboard

**Modifier and Function Keys**
- Left Shift
- Right Shift
- Left Control
- Right Control
- Left Alt
- Right Alt
- Left Meta (Windows/Command key)
- Right Meta
- Function Keys (F1, F2, etc.)

**Misc. Keyboard Data**
- Detect currently pressed keys using keyboard codes
- Get the last key pressed
- Get the physical key code of the last key pressed

### Mouse

**Mouse Buttons**
JEI can detect:
- Left Mouse Button
- Right Mouse Button
- Middle Mouse Button

**Misc. Mouse Data**
Includes things like:
- Change in mouse movement
- Scroll wheel movement
- Last mouse button pressed

## What is JEI used for and why did I suffer through a JS course to do this?

Both Scratch and TurboWarp don't have any "special key detection" blocks, so I made an extension for it.

You can make stuff like:
- Custom keybinds for games
- A fully functional computer (NOT TESTED YET)

Also because I was bored.

## Requirements

JEI needs to be run **UNSANDBOXED!!**

Unsandboxed mode allows the extension to listen to browser input events. Without unsandboxed mode it will break!!!

## Installation

Currently TurboWarp restricts URL-loaded extensions to sandboxed mode (for security reasons) so you need to download `JustEnoughInputs.js` and load it with unsandboxed mode.

(Don't worry, I tested the code.)

## Credits

Created by evil-fih on GitHub  
(darcknd on Scratch)

## License

This project is licensed under the MIT License.

See LICENSE for details.

Thanks for using this extension!
