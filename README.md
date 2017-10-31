# Measure Tool

Measure Tool is a matlab function (measuretool.m) that provides a Graphical User Interface (GUI) that is designed the aid measurements on images.

If an image contains some visible object of known length, for example, a scale bar, or a ruler. Then the physical size of an area as imaged by a pixel (i.e. the pixel size) can be calibrated. This tool provides tools to perform this calibration (draw a line on the ruler) and then perform measurements on the image:
- Distance: point-point distance
- Caliper: line-point perpendicular distance
- Polyline: multi-point distance
- Spline: smooth multi-point distance (Catmull-Rom interpolated)
- Circle: center and radius
- Angle: line-line intersection angle

The main motivation behind the tool is precision. This is achieved by allowing image magnification changes while measuring. This allows the user to place points precisely using the mouse. Additionally, all measurements can by edited to allow further refinement.

The GUI is reasonably self contained, all code resides in one file: measuretool.m
This file also contains the GUI help, which is available through the GUI itself. See the header of measuretool.m for more info.

The tool has been hosted on the Matlab FileExchange since November 2009, the corresponding website can be found here:
http://www.mathworks.com/matlabcentral/fileexchange/25964-image-measurement-utility

The current version (2.00) is not yet uploaded to the file exchange, since it is
currently in BETA state, and requires testing before it can be uploaded. Please let me know if you find any bugs or issues, or if you have some nice ideas for improvement.

