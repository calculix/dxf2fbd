# dxf2fbd
<h3>2D AutoCAD DXF to CalculiX GraphiX FBD converters</h3>

hi,

i make a tool utilities, a converter of 2D AutoCAD **DXF** to CalculiX GraphiX **FBD** files called **dxf2fbd**. this small code modification and adaptation are based on works of David Colignon from GMSH source codes.

current features:
<ul>
  <li>support point, line, arch & circle objects</li>
<li>a circle will be split automatically to four arch objects</li>
<li>Z-offset to place at some elevation</li>
<li>merge coincident nodes with a coordinate tolerances</li>
<li>remove duplicated object in the same exact position</li>
</ul>

Hopes it will be useful to create base of geometry to extrude or revolve in making of three dimensional models.

thank you for interest,

attached image screenshot for clarify,

![image1](https://github.com/xyont/dxf2fbd/blob/main/pictures/2020-09-27%2022_22_20-example1.dxf_.png =600x)

![image1](https://github.com/xyont/dxf2fbd/blob/main/pictures/2020-09-27%2021_55_36-Command%20Prompt.png =600x)

![image1](https://github.com/xyont/dxf2fbd/blob/main/pictures/2020-09-27%2021_57_51-CalculiX%20GraphiX.png =600x)

![image1](https://github.com/xyont/dxf2fbd/blob/main/pictures/2020-09-27%2022_03_59-CalculiX%20GraphiX.png =600x)
