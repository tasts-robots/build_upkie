# Hardware for Upkie wheeled bipeds

This repository provides 3D printing (STL files, 3MF projects) and CAD (Blender, FreeCAD) files to produce the mechanical parts of Upkie wheeled bipeds.

> [!NOTE]\
> We maintain this separate repository because the full revision history of hardware parts is memory-consuming. Only part designers should have to clone this repository; most users will just clone the main [upkie](https://github.com/upkie/upkie) repository.

## Assembly

Assembly files are also available on Hackaday.io:

- [`upkie.blend`](https://cdn.hackaday.io/files/1857297946229536/upkie-blender.zip): Blender project of the fully assembled robot
- [`upkie.stl`](https://cdn.hackaday.io/files/1857297946229536/upkie-stl.zip): STL model of the fully assembled robot

## Add-ons

### Earflap

Provisional connector to attach a [60x60x25 mm, 24 V DC fan](https://www.amazon.fr/Ventilateur-60x60x25mm-22dBA-Sunon-MF60252V21000UA99/dp/B07ZBSBP33/) to Upkie's head. Helps avoid thermal throttling when the robot actively balances for more than one hour.

* [STL file](add-ons/earflap/earflap.stl)

### Handle

Regular handle to grab the robot and move it around.

* [STL file](add-ons/handle/handle.stl)
* [Blender project](add-ons/handle/handle.blend)

<img align="right" src="https://github.com/upkie/upkie_parts/assets/1189580/0c6855b4-e5e8-41a2-86e3-0561b63a771f" height="150">

### Switch support

A small part to hold the on-off switch, and have it easy to access on the side of the robot.

* [STL file](add-ons/switch_support/switch_support.stl)
* [FreeCAD file](add-ons/switch_support/switch_support.FCStd)

## See also

- [Build instructions](https://github.com/upkie/upkie/wiki): printing and assembling a new Upkie
- [Discussions](https://github.com/upkie/upkie/discussions): around Upkie's hardware and software
- [mjbots/quad](https://github.com/mjbots/quad/tree/main/hw/chassis/3dprint): an open-source quadruped from which torso meshes in Upkie were initially imported
