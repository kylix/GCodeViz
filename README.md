# GCodeViz #
Open source G-Code visualization tool

![demo](https://farm2.staticflickr.com/1693/25655823712_60dcdaf007_b.jpg)

## Implemented Functions ##
 - Load G-Codes
 - Visualize supported G-Codes
 - Rotate G-Code view
 - Pan G-Code view
 - Convert to Servotronix softMC compatible motion program

## Supported G-Code ##
 - G00
 - G01
 - G02
 - G03
 - G17
 - G18
 - G19
 - G90
 - G91

## Building Intructions ##
 Requirements:
 - Qt 5.4+
 - Compiler that supoports C++11
### macOS ##
 - Install [homebrew](https://brew.sh)
 - `brew install qt5`
 - `brew cask install qt-creator`
 - Open and build `GCodeViz.pro` via Qt-Creator

### License ###
 - MIT