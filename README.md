# G-code Viewer 2D
A Python based G-code viewer. It only plots data from the x,y-plane.

## Features

- Plot 2D contours of G-code
- Qt (Pyside6) based GUI
- Plot a raster
- Plot outline and dimensions

## Requirements

- Python 3 (any version which works with Pyside6)
- Pyside6 (Qt for Python)

## Usage

Start the program GUI. Later use the menu ```File/Open``` to load and plot a G-code.

```sh
python GCODE_Viewer_2d.py
```

The command below directly opens and plots the given file immediately.

```sh
python GCODE_Viewer_2d.py any_gcode_file.nc
```

### Command Line Arguments

None or a G-code file (see above).