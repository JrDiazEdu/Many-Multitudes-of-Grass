# Many-Multitudes-of-Grass
CS460 final project

This project is a simple grass simulation built using WebGL2 with no framework.

This project implements methods described in an AMD GPUOpen article on procedural grass to create and animate large patches of grass efficiently. 
https://gpuopen.com/learn/mesh_shaders/mesh_shaders-procedural_grass_rendering/#combining-grass-blades-to-a-grass-patch

This project also makes some use of AI coding assitance, identifiable in the source by areas marked with the following comments:

//AI GENERATED CODE BEGINS HERE//////////////////////////////////////
*************
//AI GENERATED CODE ENDS HERE///////////////////////////////////////

The project generates a ground patch with roughly 20,000 blades of grass and sways the grass over time to simulate wind effects. The light source also periodically moves and illuminates the grass.

Camera Controls:
W - Move Forward
A - Move Left
S - Move backwards
D - Move Right
Q - Raise Camera
E - Lower Camera

Left Mouse Button - Click, Hold, and Drag to rotate camera, release to lock it again.

Grass blades should have a slight effect that causes them to bend towards the camera during movement.
