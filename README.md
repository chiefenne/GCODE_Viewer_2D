# G-code Viewer 2D
A Python based G-code viewer for 2D contours. It only plots data from the x,y-plane.

## Features

- Plot 2D contours of G-code
- Qt (Pyside6) based GUI
- Plot a raster
- Plot outline and dimensions

## Requirements

- Python 3 (any version which works with Pyside6)
- Pyside6 (Qt for Python)

## GUI

![Image](Images/GCODE_Viewer_2D.png)


## Usage

Start the program GUI. Later use the menu ```File/Open``` to load and plot a G-code.

```sh
python GCODE_Viewer_2d.py
```

The command below directly opens and plots the given file immediately.

```sh
python GCODE_Viewer_2d.py any_gcode_file.nc
```

When clicking the right mouse button acontext menu opens and raster and/or outline can be plotted as well. The raster size is set to a default of 10mm and can be redefined through the context menu.

### Command Line Arguments

None or a G-code file (see above).