# About

Use it here: https://wareya.github.io/webtyler/

Autotyler JS is an autotile conversion tool for turning small/incomplete autotile tilesets into complete, fleshed-out ones.

It supports seven different input formats and two different output formats, and displays a preview.

![screenshot](etc/screenshot.png)

Example inputs:

![minitiles](etc/mini.png)

![4x4plus](etc/grass4x4plus.png)

Outputs:

![minitiles output](etc/miniout.png)

![4x4plus](etc/grass4x4plusout.png)

# Extra

Autotyler's "killer feature" that sets it apart from other autotile tilemap conversion tools is the ability to specify exactly where the tiles get cut up (with the "margin offset" options), so you can use tiles with tops that overhang the halfway point without issue:

![margin example](etc/marginexample.png)

![margin example output](etc/marginexampleout.png)

Also supports outputting RPG maker autotile chipsets:

![rpg maker output](etc/grassrpgmaker.png)

The intended bitmask for the godot output is the following:

![godot minimal bitmask](etc/out%20bitmask.png)
