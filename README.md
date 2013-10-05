Spline3D
========

Simply a bezier surface, that can be illuminated by using number of light sources.
The 3D coordinate system is all self made using perspective projection equations. Basically, everything done here is pixel plotting.
The surface is modeled with Phong model. And the Gourard shading is still not working. There are some mistakes with surface vector computations. 
Appeared to be my assignment for Computer Graphics. And I haven't been devoted to solve the mistakes since then.

Compilation
===========
It is a Netbeans Project so you won't hae difficulty in compilation.

Running
=======
Execute dist/3DSpline.jar

Instructions
- Check/Uncheck Wireframe radio button to toggle wireframe view
- Check "Show Control Points" to show the control points. While they are shown, the shape of surface can be modified by dragging control points.
- Check "Show Light Sources" to show the light sources. While showing, click on the light to select the light source. Then you can change the tab from "General" to "Light Source" to control parameters of light - x,y,z positioning, light color, or delete the light source.
- Click "FlatShade/Gourard" button to toggle the shading algorithm.
- Click "Add Light Source" button to add a new light source to the space.
- Navigation buttons are for rotating the surface.
- Surface Divisions is for varying the triangle approximation over the surface. Check it yourself.