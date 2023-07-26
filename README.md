# Solving 3D string art with Fourier Analysis

But why? - "The goal of this project is to review linear algebra by making a tool that dictates where on a sphere you'd want to attach a piece of string to create a 3-dimensional shadow of a model inside of the sphere. Inspired by this video(https://www.youtube.com/watch?v=WGccIFf6MF8)."

Just to review linear algebra and become more comfortable working with Python visualizations. 

My goal is to be able to upload a 3d model(file formats not selected yet) and to create a series of vertices that will rest on the surface of a sphere. Each vertex will be connected to two other vertices (edges) that will travel through the interior of the sphere. The goal is that we could make everything transparent other than the edges connecting the vertices, and this should create something similar to the 3d depiction of our model in edges.

## Things to answer before beginning

-What Python libraries will I use
-What file format will I upload 3d models in.
-Do I want to track points on the sphere in [x,t,z] point pairs representing vectors(linear algebra).
-(Maybe don't rotate) Do I want to use quaternions(abstract algebra), does this make sense if I avoid rotations, think gimble lock with linear matrix approach and Euler angles. 
-Maybe use MatPlotLib, pyMesh, pyTorch3d and solidPython as potential options. 

# Setup

## Virtual env

=> source fourier-analysis-3d-string-art/bin/activate
