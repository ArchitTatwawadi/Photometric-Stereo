# Photometric-Stereo
This is a project to implement a Photometric stereo application. 
The basic idea of this project is that it allows us to reconstruct a 3D object's surface from 2D images of it under different lighting conditions. 
Suppose we are in a dark room with an object on a dark table, a camera fixed above it, and a moveable light source. We model the object surface as z = f(x; y), where (x; y) denotes the coordinates on the table and z is the height above the table.
Assume that the m x n sized image I is a representation of f(x; y) for each (x; y) tuple. (Given one light source, f(x; y) is the z coordinate of the position where a ray of light hits the surface at (x; y; z).). 
The pixel intensity I(x; y) indicates how much light reflects of the surface f(x; y). 
This project is implemented in Python using Numpy and Scipy libraries explaining the details of mathematics involved.
