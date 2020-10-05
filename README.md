# dxf2fbd
2D AutoCAD DXF to CalculiX GraphiX FBD converters

hi,

i make a tool utilities, a converter of 2D AutoCAD DXF to CalculiX GraphiX FBD files called dxf2fbd 1 (password: calculix.discourse.group). this small code modification and adaptation are based on works of David Colignon from GMSH source codes.

current features:

*support lines, arch & circle objects
*a circle will be split automatically to four arch objects
*Z-offset to place at some elevation
*merge coincident nodes with a coordinate tolerances
*remove duplicated object in the same position.

Hopes it will be useful to create base of geometry to extrude or revolve in making of three dimensional models.

thank you for interest,
