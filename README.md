# excel-swimmer

Simple Excel-based swimmer plots to illustrate patient stories.

## Examples

![Swimmer plot with vertical layout](swimmer-vertical.png)

![Swimmer plot with horizontal layout](swimmer-horizontal.png)

## Overview

This repository contains a simple Excel spreadsheet for creating swimmer plots to illustrate patient stories. It does not require or depend on any other software to use. Edit any of the cells with blue text to customize the swimmer plots which are available in both horizontal and vertical orientations.

The default configuration allows for up to 100 data items in five categories:
 * Patient Information -- sets the bounds for a swim lane bar (ID, History Start Date, History End Date)
 * "Treatment" Event -- adds a red triangle to the swim lane (Patient ID and Date)
 * "Biopsy" Event -- adds a black circle to the swim lane (requires Patient ID and Date)
 * "Transplant" Event -- adds a green square to the swim lane (requires Patient ID and Date)
 * "Alive" Indicator -- adds an arrow to the end of a swim lane (requires Patient ID)

If you add or remove patients, adjust the chart axis limits to ensure all are visible (left click to select patient axis, right click and select "Format Axis...").

If you add or more events, edit the chart series (right click, select "Select data...", click "Add" or "Remove", similar to existing event series).

## Contact

Paul T. Grogan <pgrogan@stevens.edu>

School of Systems and Enterprises, Stevens Institute of Technology
