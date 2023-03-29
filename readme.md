# kagoromo's zmk-config

Hi, this is my personal [ZMK firmware](https://github.com/zmkfirmware/zmk/) configuration. I implement my 36-key layout that is based on the wonderful [Miryoku](https://github.com/manna-harbour/miryoku_zmk) here (If you just want to get started with Miryoku on ZMK, the official repo might be a better fit).

My variant of Miryoku has the following characteristics:
- QWERTY alphas (with P and ' swapped because I find it the most comfortable for my right pinky).
- Inverted-T nav (instead of vi-style).
- Flipped layers (I simply prefer Space on the left, numbers on the right for example).
- Left hand centric (various shortcuts accessible with only left hand like copy/pase, undo/redo, mouse buttons).

The same base keymap is reused for multiple keyboards via the #include directive. Mouse support is enabled by building the firmware with [ftc's ZMK branch](https://github.com/ftc/zmk/tree/mouse-ftc).

That's all. Thanks for taking a glance, and I hope you can find some useful ideas for your own keymap!