# JustEnoughInputs-JEI
JustEnoughInputs is a Turbowarp extension that adds useful reporters for detecting special keys like LeftShift.

---

# Features

## Keyboard Input

JEI provides access to keyboard inputs that Scratch normally cannot distinguish.

### Modifier Keys

- Left Shift
- Right Shift
- Left Control
- Right Control
- Left Alt
- Right Alt
- Left Meta (Windows/Command key)
- Right Meta

### Additional Keyboard Data

- Detect currently pressed keys using keyboard codes
- Get the last key pressed
- Get the physical key code of the last key pressed

---

## Mouse Input

JEI adds additional mouse controls.

### Mouse Buttons

Supports:

- Left mouse button
- Middle mouse button
- Right mouse button

### Mouse Data

Includes:

- Mouse movement delta (X/Y)
- Mouse wheel movement
- Last mouse button pressed

---

# Why JEI?

Vanilla Scratch provides simple keyboard input, but advanced projects often need more information.

Examples:

- Games with custom controls
- Rhythm games
- First-person games
- Keybind systems
- Applications requiring precise input
- Advanced UI systems

JEI fills the gap between simple Scratch input and full JavaScript browser input.

---

# Requirements

JEI requires:

- TurboWarp
- Unsandboxed extensions enabled

Because JEI listens directly to browser input events, it cannot run inside the normal Scratch sandbox.

---

# Installation

## Using TurboWarp

1. Open [TurboWarp](https://turbowarp.org/)
2. Open the **Extensions** menu
3. Select **Custom Extension**
4. Enter the JEI extension URL
5. Load the extension

Example:

```
https://evil-fih.github.io/JustEnoughInputs-JEI/JustEnoughInputs.js
```

---

# Blocks

## Keyboard Blocks

### `[KEY] pressed?`

Checks whether a specific keyboard key is currently held.

Example:

```
ShiftLeft pressed?
```

Returns:

```
true / false
```

---

### `last key`

Returns the last key pressed.

Example:

```
A
```

---

### `last key code`

Returns the physical keyboard code.

Example:

```
KeyA
```

or:

```
ShiftLeft
```

---

## Mouse Blocks

### `mouse dx`

Returns the horizontal mouse movement since the previous check.

---

### `mouse dy`

Returns the vertical mouse movement since the previous check.

---

### `mouse wheel delta`

Returns the amount the mouse wheel moved.

---

### `left mouse pressed?`

Checks if the left mouse button is held.

---

### `middle mouse pressed?`

Checks if the middle mouse button is held.

---

### `right mouse pressed?`

Checks if the right mouse button is held.

---

### `last mouse button`

Returns the most recently pressed mouse button.

Possible values:

```
Left
Middle
Right
```

---
# Development

Clone the repository:

```bash
git clone https://github.com/yourusername/JustEnoughInputs.git
```

Edit:

```
JustEnoughInputs.js
```

Reload the extension in TurboWarp to test changes.
---

# Credits

Created by **evil-fih**

---

# License

This project is licensed under the MIT License.

See `LICENSE` for details.
