# My Silakka54 Vial Layout
This is the Vial layout that I've been tweaking since getting my Silakka54 a couple months ago.

### Features
- Home row mods for Shift key and quick layer switching
- Bottom row mods for easy access to Super, Ctrl, and Alt keys
- Mouse control, Media keys, Numpad
- Gaming layer

### Layers
0. Default typing mode (ColemakDH/QWERTY)
1. Gaming mode
2. Alternate typing mode (QWERTY/ColemakDH)
3. Arrow keys / Function keys / Useful symbols
4. Numpad mode
5. Mouse mode / Media keys
6. Blank
7. Default Mode switching layer

#### Notes
- You may need to modify the Tap-Hold settings to your liking in Vial if the mode switching isn't fast enough for you.
- YMMV with the mouse keys on the Silakka's stock firmware. I compiled my own firmware to set the mouse keys to '[Inertia](https://docs.qmk.fm/features/mouse_keys#inertia-mode)' which feels better to me.
  - To do this, simply add `#define MOUSEKEY_INERTIA` to the config.h and compile.
