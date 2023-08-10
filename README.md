# Uber-Hotspot-Detection
## Detects Uber hotspots using Satscan Algorithm(this project is for a small part of the Uber data)

This project involves the analysis of pickup locations from a given CSV file to identify potential hotspots where a higher density of pickups is observed. The project utilizes Python and various libraries such as pandas, numpy, Flask, gmplot, and math for data processing, geospatial calculations, and visualization. The SaTScan algorithm is also employed for hotspot detection.

## Working

* The 'inidist' function calculates the distance between two points on Earth using the Haversine formula.
* The 'enumcircle' function iterates through the pickup data and identifies potential circular areas for hotspot analysis.
* The SaTScan algorithm is applied to calculate the likelihood of each circular area being a hotspot based on certain conditions.
* Detected hotspots are saved in a CSV file named 'circle.csv'.
* Map visualization is generated using the 'gmplot' library.

## Execution

* Run the 'UberHotspotDetection.ipynb' file.
* You will get the plotted map in 'map13.html' file

![Uberhotspots](https://github.com/Victorhugo1412/Uber-Hotspot-Detection/assets/85059453/3ef75de1-7900-4acf-99dc-a0fd226d0cee)
