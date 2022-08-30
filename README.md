# ScanAnalysis

## Prerequisites
This program requires the following python modules:
* os
* Python Image Library
* math
* opencv-python
* numpy
* matplotlib
* pathlib
* scipy
* tqdm
* [cellprofiler as a python library](https://github.com/CellProfiler/CellProfiler/wiki/CellProfiler-as-a-Python-package) 

## Running the Script
Run the first cell to simply import all of the necessary libraries.

Run the second cell only once to create the file system, and then put the .czi scans in `images/CZI/`.

From there you can run the rest of the cells and they will output the intensity analysis and cell-count analysis. 
