# 2D Plotter

This project is my attempt at converting HPGL2 plot files into Gerber G-Code to send to a 3D printer (or other Gerber device) as if it was a HPGL compatible plotter.  I currently attach a marker to my printer's print head and clip a sheet of paper to the bed for plotting.  This has produced some interesting results using a Watcom Tablet with InkScape.  It also generated good results plotting mechanical drawings generated in AutoCAD.

## Branches

The Master branch will contain the latest stable version of the program.  Other branches will contain features that are being worked on in various stages of completeness/stability.

## Furture Goals

At the time of writing this README, this program is very much in a Beta state with little funtionallity.  It does, however plot out hpgl files genterated from Inkscape quite well.  It has also been tested on some old AutoCAD generated plot files with resonable results.  

Currently the program ignores pen changes.  But that may be added at a later date.  This program does NOT CHECK FOR OVERTRAVEL.  Make sure the plots files you use are small enough to fit on your printer and/or paper.  I hope to add a settings configuration window that will allow these limits to be added and watched while plotting.
