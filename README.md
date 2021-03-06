[![Open in Code Ocean](https://codeocean.com/codeocean-assets/badge/open-in-code-ocean.svg)](https://codeocean.com/capsule/5221262/tree)

DOI: https://doi.org/10.24433/CO.5221262.v1

# world-earthquake-one-month

This program shows the number of earthquakes occurred around the world during a one-month period on a map.

Using a USGS dataset, 'eqone' can visualize where earthquakes occurs.

The USGS dataset is downloadable from:

https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/all_month.csv

This is sample of earthquakes around Japan.

<img src='https://github.com/Junya-Toyokura/world-earthquake-one-month/blob/main/sample.png' width=640 height=480>

# How to install eqone on Linux, MacOS, or WSL on Windows

You may need folium library.

$pip install folium

$pip install eqone

# How to run eqone
 
Eqone program allows user to specify up to arthquake scale(1~) to plot on world map.

$eqone 4

<img src='https://github.com/Junya-Toyokura/world-earthquake-one-month/blob/main/sample2.png' width=640 height=480>

If you don't specify a number, program shows where earthquakes with intensity 5 upper are around the world.

$eqone

<img src='https://github.com/Junya-Toyokura/world-earthquake-one-month/blob/main/sample3.png' width=640 height=480>

If it does not appear the map, there are 'map.html' file on your folder.

MaxOSX $open map.html

Windows $start map.html or explorer map.html

WSL $explorer.exe map.html
