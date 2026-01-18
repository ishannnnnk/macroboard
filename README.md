4 key macropad

<img width="729" height="685" alt="image" src="https://github.com/user-attachments/assets/ce8d9222-2807-43f1-8660-337a8a98a662" />

<img width="729" height="685" alt="image" src="https://github.com/user-attachments/assets/8dba9b76-deba-47a1-b2b0-e5240d7904a0" />


What is this
Basically I wanted a small macropad for my most used keybinds/websites (copy, paste, chatgpt, google docs) lol

Runs on a Seeed XIAO RP2040 with KMK firmware (CircuitPython-based). Super easy to reprogram without reflashing.

Hardware
MCU: Seeed XIAO RP2040
Switches: 4x Cherry MX compatible switches
LEDs: 2x SK6812 RGB LEDs
the PCB is designed in KiCad and shaped like a cricket ball (well, as close as you can get with a PCB).

Default keymap
SW1 (top left): Play/Pause
SW2 (top right): Next Track
SW3 (bottom left): Toggle LEDs
SW4 (bottom right): Cycle RGB animations
Programming
It's running KMK so you just edit kmk/main.py and save it to the CIRCUITPY drive. No compiling, no flashing tools, just plug it in and go.

The code's pretty straightforward if you want to change the keys or add macros. Check out the KMK docs for more info.

BOM
4x Cherry MX Switches 2x SK6812 MINI LEDs 1x XIAO RP2040 4x Blank DSA Keycaps 4x M3x16 Bolts 4x M3 Heatset Inserts ~100g PLA
