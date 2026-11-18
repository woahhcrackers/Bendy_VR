# Bendy VR

Bendy and the Ink Machine, chapters 1-5, running standalone on Quest. No PC, no link cable, just the headset.

This repo is for the builds and for bug reports. The project source isn't in here, only releases.

## What it is

A VR conversion of the original game. You move around the studio in room scale or with the stick, and the menus sit in the world instead of being stuck to your face.

## Install

1. Grab the latest `.apk` from [Releases](../../releases).
2. Enable developer mode on the headset, plug it in, then:
   ```
   adb install -r Bendy_VR.apk
   ```
3. It shows up under Unknown Sources in the library.

Quest 3 is the target. Quest 2 works but gets a lower render scale and shorter shadow distance, so it looks softer.

## Options

All of these are in the Advanced menu under "VR Options":

- Snap turn (on by default, 45 degrees) or smooth turn with adjustable speed
- Movement direction from the head or from the controller
- Left handed mode, swap sticks
- Laser pointer for menus
- Height offset if your floor is off

Graphics defaults are tuned per headset (MSAA, shadow distance, foveated rendering). You can still change quality in the menu.

## Known issues

Check the [issues](../../issues) tab before filing a new one.

## Reporting a bug

Use the bug report template. The things that actually help: which headset, which chapter, and what you were doing right before it broke. A short video from the headset beats a long description.

## Credits

Original game by Joey Drew Studios / Meatly. VR port built on the two forks VR work and a lot of testing. This is a fan project and isn't affiliated with the original developers.
