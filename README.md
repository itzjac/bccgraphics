# Computer Graphics 101

This course will help you to understand the mathematics and algorithms necessary to perform
real time 3D graphics using a modern 3D API like OpenGL, DirectX or Vulkan.


Requisites
 * Linear algebra
 * Calculus
 * Data structure and algorithms
 * C and C++
 * Optimizing CPU programs

IMPORTANT

What this course is NOT about
 * Specifics on how to use a 3D API like Direct3D, Vulkan or OpenGL
 * Specifics on how to program in C or C++, or any other low level language, previous experience on any of those languages is mandatory
 
Syllabus Part 1

 ## 3D graphics pipeline & rasterization 
   * Pipeline stages
   * Matrices through the pipeline
   * The rasterization algorithm
   * Z-buffer
   
 ### Project 0
   * Familiarize with the framework and solutions (Windows VS2019 community)
   * Familiarize with a particular API and real time rendering

 ## Cameras, scenes graphs 
   * Matrices for the camera
   * Tansformations
   * Perspective and orthogonal cameras
   * Algorithms to build graphs
   * Derive formulas for the camera

 ### Project 1
   * Manipulate a crystal ball and/or fly camera
   * Define and load scenes using general transformations
    
 ## Blinn Phong lighting model and texturing
   * Lambertian term
   * Blinn-Phong model
   * Texturing
    
 ### Project 2
   * Apply the lighting model to a general scene
   
 ## Ray tracing
   * Stages
   * Intersection algorithms
   * Shadows
   * Reflection
   * Shading
   * Recursion

 ### Project 3
   * Generate high quality images using ray tracing algorithms
    
 ## Optimization (optional)
   * AABB
   * Space traversal
   * Multiple rays
   * Multi-threading
   * SIMD
 
 ### Project 4
   * Get the most out of the CPU power using at least 3 or all the recommended optimizations


![cornellbox](pics/cornell.png)
![dragon](pics/image.png)
![checkerboard](pics/checkerboard5.png)




Part 2 of the course continues after the Ray Tracing assignment (Project 3). 
It is a mandatory to have completed with good scores all the 
previous projects (except otional sections).

Syllabus Part 2
 ## Refraction
 
 ### Project 1
  
 ## Real time ray tracing using a modern API like Optix or DXR
 
 ### Project 2
  
 ## Direct lighting
   * The rendering equation
   * Area lights
   * Analytic solution
   * Monte Carlo stratify, random sampling
    
 ### Project 3
   *  Cornell box using Monte Carlo stratify area lights
    
 ## Global illumination
  
 ### Project 4
  
 ## Optimization (optional)
 
 ### Project 5

![cornelldirectlighting](pics/cornelldi.png)
![Blender TBC mesh exporter to ray tracer with Area Lights](pics/monkey_sphere.png)
![Blender TBC mesh exporter to recursive ray tracer](pics/monkey.png)

Resources

* The OpenGL Programming Guide Ninth Edition (The Red Book) http://www.opengl-redbook.com/
* The OpenGL Shading Language: Third Edition (Orange Book) https://www.oreilly.com/library/view/opengl-shading-language/9780321669247/fm.html
* Computer Graphics: Principles and Practice (3rd Edition), John F. Hughes Andries van Dam Morgan McGuire David F. Sklar James D. Foley Steven K. Feiner Kurt Akeley https://www.pearson.com/uk/educators/higher-education-educators/program/Hughes-Computer-Graphics-Principles-and-Practice-3rd-Edition/PGM819382.html
* An introduction to ray tracing By Andrew Glassne https://www.realtimerendering.com/raytracing/An-Introduction-to-Ray-Tracing-The-Morgan-Kaufmann-Series-in-Computer-Graphics-.pdf
* Ray tracing in a weekend https://github.com/RayTracing/raytracing.github.io
* Physically Based Rendering: From theory to practice https://www.pbrt.org/
* Introduction to DirectX Ray Tracing https://intro-to-dxr.cwyman.org/
* Mitsuba https://github.com/mmp/pbrt-v4
* pbrt https://github.com/mmp/pbrt-v4 
* Test scenes https://www.pbrt.org/scenes-v3



