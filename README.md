# Hardware for Upkie wheeled bipeds

<img align="right" width="200" src="https://github.com/user-attachments/assets/6c9b24ed-2439-414a-94e7-167b035e9f6f">

This repository provides FreeCAD and STL files to 3D print the mechanical parts of [Upkie wheeled bipeds](https://github.com/upkie/upkie).

### Getting started

This repository uses Git LFS to distribute large files, as the full revision history of CAD files would be memory-consuming. You will need to install Git LFS for your operating system. For instance, on a Debian-based Linux distribution:

```console
sudo apt install git-lfs
```

If you cloned this repository with Git LFS installed, all files will be in your working directory. If you cloned the repository without Git LFS, you can pull large files by `git lfs pull`.

## Add-ons

### Handle

Regular handle to grab the robot and move it around.

* [STL file](add-ons/handle/handle.stl)
* [Blender project](add-ons/handle/handle.blend)

## See also

- [Build instructions](https://github.com/upkie/upkie/wiki): printing and assembling a new Upkie
- [Discussions](https://github.com/upkie/upkie/discussions): around Upkie's hardware and software
- [mjbots/quad](https://github.com/mjbots/quad/tree/main/hw/chassis/3dprint): an open-source quadruped from which torso meshes in Upkie were initially imported
