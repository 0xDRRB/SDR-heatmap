# SDR heatmap with custom gradient

This is a standalone fork of [Kyle Keen heatmap.py](https://github.com/keenerd/rtl-sdr-misc/tree/master/heatmap)) with added fonctionality : customs gradients.

The new option ```--gradient``` let you specify a 256x1 image file filled with a custom gradient (left to right) and get this :

![heatmapgrad_cgradient](heatmapgrad_cgradient.jpg?raw=true)

instead of this :

![heatmapgrad_orig](heatmapgrad_orig.jpg?raw=true)

or this (if you change ```rgb2()``` to ```rgb3()``` in the original script) :

![heatmapgrad_rgb3](heatmapgrad_rgb3.jpg?raw=true)

Without ```--gradient FILE``` option, ```heatmapcp.py`` behave like Kyle's ```heatmap.py```.

