Sage Shooting Range — Bottles
Version: 2025-08-09
Sage Shooting Range — Bottles
==================================
Version: 2025-08-09
What is this?
-------------
A simple 2D browser game. Aim with your mouse, click to shoot bottles.
Bottles respawn 10 seconds after being shot. If you clear all 10
before any respawn, you win.
How to run (no installs needed)
--------------------------------
1) Open the file: shooting_bottles_game.html
2) Move your mouse to aim (you'll see a crosshair).
3) Click to shoot.
4) Music starts after your first click (browser security rule).
Goal
----
• There are always 10 bottles.
• Shoot them all before any respawn (10 seconds) to WIN.
Controls
--------
• Mouse move = aim
• Left click = shoot
• After victory, click "Play again" to restart.
Options (edit file if desired)
------------------------------
Open shooting_bottles_game.html in a text editor and find:
const BOTTLE_COUNT = 10; // change number of bottles
const RESPAWN_MS = 10000; // change respawn time (ms)
const HIT_R = 26; // hit radius (higher = easier)
Notes
-----
• Designed for Chrome/Edge/Firefox on desktop.
• All audio is generated programmatically (no downloads required).
• This is a simple demo you can extend with real graphics and sounds.
Credits
-------
Built for you by ChatGPT as a starter template.
