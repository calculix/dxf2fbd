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

attached image screenshots for example usage and clarity,

[<img src="https://github.com/xyont/dxf2fbd/blob/main/pictures/2020-09-27%2022_22_20-example1.dxf_.png" width="600"/>](image1.png)

[<img src="https://github.com/xyont/dxf2fbd/blob/main/pictures/2020-09-28%2014_34_56-Command%20Prompt3.png" width="600"/>](image2.png)

[<img src="https://github.com/xyont/dxf2fbd/blob/main/pictures/2020-09-28%2014_35_35-Source2.png" width="600"/>](image3.png)

[<img src="https://github.com/xyont/dxf2fbd/blob/main/pictures/2020-09-27%2021_57_51-CalculiX%20GraphiX.png" width="600"/>](image4.png)

[<img src="https://github.com/xyont/dxf2fbd/blob/main/pictures/2020-09-27%2022_03_59-CalculiX%20GraphiX.png" width="600"/>](image5.png)

