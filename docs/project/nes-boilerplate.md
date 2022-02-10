---
layout: page
title: NES-BOILERPLATE
permalink: /project/nes-boilerplate.html
---

{% include file-start.md %}

## NES Boilerplate Project

This is a default NES project to start with an already working and programmable game (in ASM or C).

### **Features**

This project has/can:

- Compile the game from assembly code.
- Compile the game from c code.
- A reset handler that reset memory to 0 and call the main function.
- A general NMI handler to draw stuff on the screen.
- An IRQ handler (that does nothing, but we need one).
- Support for the FamiStudio Sound Engine (<https://famistudio.org>)
- Some defined constant (PPU, APU, etc.).

### **Example**

By default, the game play an animation with moving background tiles, a sprite and a little music to show that the game is working correctly.

![Boilerplate Screenshot](/img/nes-boilerplate.gif)

### **Sources**

You can find the project sources here: [NES Boilerplate Game](https://github.com/Safyrus/NES-Boilerplate-Game)

Explanation of how to configure the game to your need is explained there.

{% include file-end.md %}
