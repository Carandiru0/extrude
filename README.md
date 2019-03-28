# magicavoxel-extrude-shader

[![Supports](https://img.shields.io/badge/MagicaVoxel-0.99.2-brightgreen.svg)][mv-link]

__Extrude Shader for [MagicaVoxel](https://ephtracy.github.io/) to enhance common and repetitive tasks.__

## Installation

Install the shader files by copying the files from the `shader` directory in this project into the `shader` directory of your MagicaVoxel installation.

<h3 id="extrude_shader">Extrude</h3>

```
xs ex [direction] (optional)[decay]
xs ey [direction] (optional)[decay]
xs ez [direction] (optional)[decay]
```

<img src="/img/extrude.png?raw=true" alt="">

The extrude shader will "duplicate" the voxels of the chosen palette color on the axis chosen(ex, ey, ez), in the direction (-1,1) of that axis. Optionally the a decay argument can be supplied to remove a ring/border of voxels around the opposite axis' perimeter. Repetively repeating the extrude shader will extrude in the direction, and with decay will falloff / create a stair case effect following the countour of the voxels selected by palette color. (Similar to pyramid, but in on any axis).

I hope that the voxel shader is as useful for you as it has been for me!

[developer-link]: http://www.supersinfulsilicon.com/
[mv-link]: https://ephtracy.github.io/
