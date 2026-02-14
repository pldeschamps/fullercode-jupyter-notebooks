# fullercode-jupyter-notebooks

## Purpose of this Notebook
fullercode https://github.com/pldeschamps/fullercode-js is a geocode system based on the Fuller projection : https://en.wikipedia.org/wiki/Dymaxion_map

Fullercode is a hierarchical and regular Discrete Global Grid (DGG) in which every spherical triangle is divided in 16 smaller triangles.

First, the global surface of the Earth is divided in 20 triangles according to https://www.researchgate.net/publication/334307604_Dymaxion_Map_Transformations_-_Technical_White_Paper.

In the above document, the rounded values are the latitude and longitude of point No. 1 'CHINA' and the longitude of point No. 2 'NORWAY' (which is located near Vestbrakan Island):

Table 1: Icosahedron Vertex Locations (9/28/1979)

| Number|Location | Longitude | Latitude | x | y | z |
|-------|---|-----------|----------|---|---|---|
| 1 | CHINA | E 122.30000000 | N 39.10000000 | -0.41468222 | 0.65596241 | 0.63067581 |
| 2 | NORWAY | E 10.53619898 | N 64.70000000 | 0.42015243 | 0.07814525 | 0.90408255 |
| 3 | ARABIAN SEA | E 58.15770555 | N 10.44734504 | 0.51883673 | 0.83542038 | 0.18133184 |
| 4 | LIBERIA | W 5.24539058 | N 2.30088201 | 0.99500944 | -0.09134780 | 0.04014717 |
| 5 | PUERTO RICO | W 67.13232659 | N 23.71792533 | 0.35578140 | -0.84358000 | 0.40223423 |
| 6 | ALASKA | W 143.47849033 | N 50.10320164 | -0.51545596 | -0.38171689 | 0.76720099 |
| 7 | BUENOS AIRES | W 57.70000000 | S 39.10000000 | 0.41468222 | -0.65596241 | -0.63067581 |
| 8 | ANTARTICA | W 169.46380102 | S 64.70000000 | -0.42015243 | -0.07814525 | -0.90408255 |
| 9 | PITCAIRN ISLAND | W 121.84229445 | S 10.44734504 | -0.51883673 | -0.83542038 | -0.18133184 |
| 10| GILBERT ISLAND | E 174.75460942 | S 2.30088201 | -0.99500944 | 0.09134780 | -0.04014717 |
| 11| AUSTRALIA | E 112.86767341 | S 23.71792533 | -0.35578140 | 0.84358000 | -0.40223423 |
| 12| PRINCE EDWARD ISLAND | E 36.52150967 | S 50.10320164 | 0.51545596 | 0.38171689 | -0.76720099|

**The purpose of this notebook** is to calculate all the coordinates with 18 digits.
