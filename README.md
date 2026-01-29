# doom-nano
A 3d raycast engine for Arduino

To be clear. **This is not an actual Doom game**, just picked some sprites from it (and simplified a lot). The rendering engine is more like a Wolfeistein 3D. The Doom idea came because I started this building the fancy melt-screen effect (included in an early version, but not anymore).

Hardware I used:
- A breadboard
- An Arduino Nano (ATmega328P - old bootloader)
- An OLED Display (i2c 128x64)
- 5 buttons
- Buzzer (Optional)

Simplified version (using an Arduino UNO, built-in pull-up resistors for buttons and a buzzer):
![](/images/input-pull-up-version.jpg?raw=true)

Wiring:
![](/images/wiring.png?raw=true)
