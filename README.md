# Hardware for Upkie wheeled bipeds

<img align="right" width="200" src="https://github.com/user-attachments/assets/6c9b24ed-2439-414a-94e7-167b035e9f6f">

This repository provides FreeCAD and STL files to 3D print the mechanical parts of [Upkie wheeled bipeds](https://github.com/upkie/upkie).

### Getting started

This repository uses Git LFS to distribute large files, as the full revision history of CAD files would be memory-consuming. You will need to install Git LFS for your operating system. For instance, on a Debian-based Linux distribution:

```console
sudo apt install git-lfs
```

If you cloned this repository with Git LFS installed, all files will be in your working directory. If you cloned the repository without Git LFS, you can pull large files by `git lfs pull`.

## Legs

### Lower leg

Lower segment connecting to the wheel hub.

- [FreeCAD project](legs/lower_leg/lower_leg.FCStd)
- [STL file](legs/lower_leg/lower_leg.stl)

### qdd100 support

This optional 3D printed part with a bearing can be added to reduce play and "protect" qdd100 actuators from radial load.

- [FreeCAD project](legs/hip_support/hip_support.FCStd)
- [STL file](legs/hip_support/hip_support.stl)
- Reference of the corresponding bearing: 40x52x7mm [Amazon](https://amzn.eu/d/3NPo64S)

### Upper leg

Upper segment of the leg assembly.

- [FreeCAD project](legs/upper_leg/upper_leg.FCStd)
- [STL file](legs/upper_leg/upper_leg.stl)

### Wheel hub

Integrated wheel and hub assembly for mounting tires.

- [FreeCAD project](legs/wheel_hub/wheel_hub.FCStd)
- [STL file](legs/wheel_hub/wheel_hub.stl)

There is also an [Hex variant](legs/wheel_hub/hex_variant/) with a tiny shaft that can be used with a 17 mm wheel hex driver RC cars. It is easier to adapt to various RC wheels, but more brittle.

## Torso

### Battery shore plug

Plug where two leaf springs can be connected to the battery via an XT90-S cable.

- [STL file](torso/battery_shore_plug/battery_shore_plug.stl)

### Battery stud

Two-part hold for securing the battery inside the Upkie.

- [STL file (top)](torso/battery_stud/battery_stud_top.stl)
- [STL file (bottom)](torso/battery_stud/battery_stud_bottom.stl)

### Case

Main torso enclosure.

- [FreeCAD project](torso/case/case.FCStd)
- [STL file](torso/case/case.stl)

### Raspberry Pi support

Mounting bracket for the Raspberry Pi.

- [FreeCAD project](torso/raspberry_support/raspberry_support.FCStd)
- [STL file](torso/raspberry_support/Raspberry_support.stl)

### Power dist board support

Mounting bracket for the power distribution board.

- [FreeCAD project](torso/powerboard_support/powerboard_support.FCStd)
- [STL file](torso/powerboard_support/Powerboard_support.stl)

## Add-ons

### Camera support

Mounting bracket for an OAK-D Lite camera.

- [FreeCAD project](add-ons/camera_support/camera_support.FCStd)
- [STL file](add-ons/camera_support/camera_support.stl)

### Handle

Regular handle to grab the robot and move it around.

- [STL file](add-ons/handle/handle.stl)

## See also

- [Build instructions](https://github.com/upkie/upkie/wiki): printing and assembling a new Upkie
- [Discussions](https://github.com/upkie/upkie/discussions): around Upkie's hardware and software
- [mjbots/quad](https://github.com/mjbots/quad/tree/main/hw/chassis/3dprint): an open-source quadruped from which torso meshes in Upkie were initially imported
