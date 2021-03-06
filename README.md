# Microtubule-Extraction
 
Maurits Kok, 2020  
version 1.0

## ImageJ macro

Script to find, filter, and store individual microtubule images with a molecular motor 
profile from a scanned image stack. Use the provided "Sample.tif" for example data.

This script requires the plugin "Ridge Detection": https://imagej.net/Ridge_Detection.  

INPUT:
* dual channel .tif stack (surface scan data, not time-dependent data)

OUTPUT:
* .tif stacks with separate microtubule and molecular motor signal   
* list of all identified microtubules  
* RoiSet.zip contains coordinates  
* Optional: .tif stack with overlapping microtubules (debug mode)

## Sample data
Data of dual channel dataset containing microtubules and dynein profiles (32-bit). 
The data was obtained with TIRF microscopy and by scanning the sample.
