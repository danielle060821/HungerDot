# HungerDot — Arduino Survival Game

A mini survival game built with Arduino, joystick, IR remote, and a 16×2 LCD.  
Players control a moving dot to collect food (X) before starving. The game supports restarting and toggling the screen via the IR remote.  
An NPN transistor is integrated to control the LCD backlight programmatically.

---

## Features
- Dot moves on a 16×2 LCD using a joystick
- Food randomly appears; players must collect it to survive
- IR remote control:
  - POWER button: Turn the LCD on/off
  - 0 button: Restart the game
- Countdown and welcome messages at game start
- LCD backlight controlled via NPN transistor

---

## Tools & Tech
- Arduino Uno  
- C++  
- 16×2 LCD  
- Joystick module  
- IR remote and receiver  
- NPN transistor  
- Resistors  
- Breadboard
- M-M & M-F wires
---

## Skills Learned
- Hardware-software integration  
- Real-time input handling  
- Embedded systems programming  
- Circuit design and debugging  

---

## How to Play
1. Upload the code to Arduino
2. Turn on the LCD using the IR POWER button
3. Use the joystick to move the dot and collect food (X)
4. Survive as long as possible
5. Press "0" on the IR remote to restart

---

## Personal Notes
My first Arduino project! I learned Arduino from scratch in four days, then built this game in two days of hyperfocus.  
Originally inspired by Snake, I simplified mechanics due to hardware limitations—but discovered new challenges like array-based position tracking and input delays. Learned a lot in the hard way, and it was worth it!