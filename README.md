# CMake-C-App
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

CMake-C-App is a template application for programming in C and building with CMake. You can use it as a starting point for developing your own application.

## What you need

To obtain and build CMake-C-App, make sure that your Linux system has C development and Git related packages installed:

* Debian/Ubuntu: `sudo apt install git gcc gdb make cmake`
* Fedora: `sudo dnf install git gcc gdb make cmake`
* openSUSE: `sudo zypper install git gcc gdb make cmake`

## Getting the code

To get the code, clone the Git repository to a subdirectory, for example inside your own home directory:

* `git clone https://github.com/pragmaticlinuxblog/cmake_c_app.git ~/myapp`

## Building the application

After cloning the Git repository, you can prepare the build environment with the help of CMake:

* `cd ~/myapp/build`
* `cmake ..`

Note that this only has to be done once. From now on you can build the application by running this command from inside the `build` subdirectory:

* `make all`

## Installing the application

The *CMakeLists.txt* contains details on how to install the application as well. To install the application on your Linux system, run this command from the `build` subdirectory:

* `sudo make install`

