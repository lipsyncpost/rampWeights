# rampWeights & weightsServer
Weight controller nodes for Autodesk Maya to control blend shape weights or weighted deformers for various effects.

Originally the plug-ins were part of the blend shape editor [SHAPES](http://www.braverabbit.com/shapes/). The open source release is intended to give easier access to these nodes even without the editor.

## Videos
[rampWeights on Vimeo](https://vimeo.com/311842397)

[weightsServer on Vimeo](https://vimeo.com/256378129)

## Installation
Installation is easy with the included installer.

[Easy Install](https://github.com/IngoClemens/rampWeights/wiki/Installation)

## Getting Started
Visit the [Quick Guide](https://github.com/IngoClemens/rampWeights/wiki/Quick-Guide) for a brief workflow description.

See the [Wiki](https://github.com/IngoClemens/rampWeights/wiki) for full details.

## Linux Compile Instructions For Maya 2020

export CC="/sw/pkg/gcc/6.3.1/bin/gcc"

export DEVKIT_LOCATION="/sw/pkg/maya/2020/maya2020/devkit"

cmake -H. -Bbuild -G "Unix Makefiles"

cmake --build build/