# Summary

This template can be used for a quick setup
of a OpenGL, GLFW project in C++ using CMake as build system.

# Why GLFW

There is a long list of libraries built on top of OpenGL to abstract a lot of low-level stuff to make it easier for you.</br>
From looking around on the internet a bit, it seems like GLFW is a popular choice if you want a library that is lightweight, that doesn't abstract away a lot of the low-level code concerened with graphics rendering and interaction with OpenGL, which is the part you are likely most interested in writing yourself when doing a project like this.</br></br>
All GLFW does is make it easier to setup and manage Window and Inputs (Keyboard, Mouse and Joystick), something you would otherwise have to write quite a lot of platform specific code, for each platform you want to support.</br>
GLFW lets you write just a few lines of code to have cross-platform Window and Input management setup in no time.

# Prerequisites

In this template I've opted for linking GLFW from installed binaries/libraries as suppose to building it from source. It's simply less code to manage ourselves so until it actually feels neccessary to build from source, we'll keep it this way. This means you need to actually install GLFW before hand though. Heres what you run in the terminal to do this:
* Ubuntu (Same for Ubuntu run in WSL): ```sudo apt-get install libglfw3-dev```
* Windows: TBD
* OSX: TBD
