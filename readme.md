svg2gcode
========
A command line utility for converting SVG to Gcode using [Gcanvas](https://github.com/em/gcanvas) and [canvg](https://code.google.com/p/canvg/).

### Installation
First make sure you have [nodejs](http://nodejs.org) installed.
```
npm install -g svg2gcode
```

### Usage
```
  Usage: svg2gcode [options] <file ...>

  Options:

    -h, --help                 output usage information
    -V, --version              output the version number
    -s, --speed <number>       spindle speed
    -f, --feed <number>        feed rate
    -d, --depth <number>       z of final cut depth
    -c, --depthofcut <number>  z offset of layered cuts
    -t, --top <number>         z of top of work surface
    -a, --above <number>       z of safe area above the work
```
