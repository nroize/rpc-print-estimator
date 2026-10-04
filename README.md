# RPC Print Estimator

Drop an STL, 3MF, OBJ or PLY file to estimate what it costs to print at the University of Waterloo [Rapid Prototyping Centre](https://uwaterloo.ca/rapid-prototyping-centre/), which charges by printed weight (supports included).

Live: https://nroize.github.io/rpc-print-estimator/

Weight is estimated from the mesh's volume and surface area using an approximation of Bambu Studio's 0.20 mm standard profile (walls, top/bottom shells, infill, and supports for overhangs past 30°). If you've already sliced the part, enter the slicer's weight for an exact figure. Unofficial; rates may change.

Single static `index.html`, no build step. Uses three.js from jsDelivr for parsing and the 3D preview.
