summon-arm-toolchain for MinGW
==============================

Copy and modify http://www.microbuilder.eu/Tutorials/SoftwareDevelopment/BuildingGCCToolchain.aspx.

## Install

Install MinGW and MSYS on C:\MinGW.
Run MinGW Installation Manager, and install following packages.

* mingw32-base
* mingw32-gcc-g++
* mingw32-gmp (dev)
* mingw32-mpc (dev)
* mingw32-mpfr (dev)
* msys-base
* msys-wget (bin)

Open msys console, and mount mingw dir.

    $ mount c:/mingw /mingw

Run following command.

    $ sh summon-arm-toolchain.sh ~ arm-none-eabi

## Usage

xxx
