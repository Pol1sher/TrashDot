# TrashDot Engine

<p align="center">
  <a href="https://github.com/Pol1sher/TrashDot">
    <img src="logo_outlined.svg" width="400">
  </a>
</p>

## 2D and 3Dish cross-platform game engine

**TrashDot Engine is a feature-packed, cross-platform
game engine to create 2D and 3Dish games from a unified interface.** It provides a
comprehensive set of common tools, so that users can focus on making games
without having to reinvent the wheel. Games can be exported with one click to a
number of platforms, including the major desktop platforms (Linux, macOS,
Windows), mobile platforms (Android, iOS), as well as Web-based platforms
(HTML5).

## Free and open source
TrashDot is completely free and open source under the very permissive MIT license.
No strings attached, no royalties, nothing. The users' games are theirs, down
to the last line of engine code.

![Screenshot of a 3D scene in the Godot Engine editor](https://raw.githubusercontent.com/godotengine/godot-design/master/screenshots/editor_tps_demo_1920x1080.jpg)

### Compiling for Windows

## Requirements

[Visual Studio Community](https://www.visualstudio.com/vs/community/), version 2017 or later. VS 2019 is recommended.

[MinGW-w64](http://mingw-w64.org/) with GCC can be used as an alternative to Visual Studio. Be sure to install/configure it to use the posix thread model. Important: When using MinGW to compile the master branch, you need GCC 9 or later.

[Python 3.5+](https://www.python.org/downloads/windows/) Make sure to enable the option to add Python to the ``PATH`` in the installer.

[SCons](https://www.scons.org/) build system. Using the latest release is recommended, especially for proper support of recent Visual Studio releases.

### Compiling for Linux

## Requirements
For compiling under Linux or other Unix variants, the following is required:
GCC 7+ or Clang 6+.
Python 3.5+.
SCons 3.0+ build system. If your distribution uses Python 2 by default, or you are using a version of SCons prior to 3.1.2, you will need to change the version of Python that SCons uses by changing the shebang (the first line) of the SCons script file to #! /usr/bin/python3. Use the command which scons to find the location of the SCons script file.
pkg-config (used to detect the dependencies below).
X11, Xcursor, Xinerama, Xi and XRandR development libraries.
MesaGL development libraries.
ALSA development libraries.
PulseAudio development libraries.
Optional - libudev (build with udev=yes).

### Compiling from Source for other systems

[See the official godot docs](https://docs.godotengine.org/en/latest/development/compiling/)
for compilation instructions for every supported platform.

## Documentation and demos

The official documentation is hosted on [ReadTheDocs](https://docs.godotengine.org).
It is maintained by the Godot community in its own [GitHub repository](https://github.com/godotengine/godot-docs).
