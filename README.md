# sf-svg
SFML-based library to draw .svg files and Bézier Curves.

## What it does:
- SVG files loading / drawing;
- SVG rasterization;
- Implements Square- and Cubic Bézier curves;
- Curves inherit sf::Shape;
- Provides interface for Bézier curves;
- Provides debug-friendly features like "helper lines" etc.

## What it lacks (yet):
- Loading SVG from memory/stream;

## Documentation
You can find docs [here](https://koczurekk.github.io/sf-svg/).<br />
Generated using doxygen, It's not good-looking, but I don't have time to change doxygen's .css files.

## Usage:
### Compilation
```
$ git clone https://github.com/KoczurekK/sf-svg.git
$ cd sf-svg
$ qmake curves-shared.pro
$ make
```
### Installation & usage
Copy SFC headers to /usr/include/SFC or to any other path supported on your OS. Then copy .so/.dll files wherever you want to and remember to pass linker option -lsfsvg.
