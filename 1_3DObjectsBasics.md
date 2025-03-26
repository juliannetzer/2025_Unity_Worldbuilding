# <a name="basic3d"></a> Basic 3D Objects

In this section, we cover the fundamental aspects of creating, customizing, and importing 3D objects into Unity. Whether using Unity’s built-in 3D objects, custom materials and shaders, or external 3D models, understanding how these elements work together is essential for building interactive and visually appealing environments.

Key Topics:
- Basic 3D Objects – How to use Unity’s built-in primitives for prototyping and scene construction.
- Materials, Shaders, and Textures – How materials define an object’s appearance, and how shaders control rendering properties such as lighting and transparency.
- Importing and Managing 3D Assets – Best practices for bringing in models from external software, configuring materials, and troubleshooting common issues.
- Optimizing for Performance – Considerations for reducing model complexity and ensuring smooth performance on different platforms.

By following these instructions, you will learn how to create efficiently structured and visually engaging 3D environments in Unity.

# Unitys Built-in 3D Shapes

Unity provides a set of basic 3D models that can be used for prototyping or as foundational elements in a scene. These include Cubes, Spheres, Planes, Cylinders, Capsules, and Quad Primitives.

**Adding 3D Object to your scene**
You can add them to your scene when you got to GameObject -> 3D Object
![](images/models.jpeg)

**Adjusting the Model**
Once added, the 3D object will appear in the Hierarchy and Scene View. Use the Inspector to modify properties such as scale, position, and rotation.

Once added, the 3D object appears in the hierarchy and scene view. 
You can now select the object by clicking on it and change its size, position and rotation. To do this, either select the relevant tool in the scene view: 
![](images/Basic3D.jpeg)
> You can also use the ‘w’, ‘e’, ‘r’ keys to switch between the functions. 

Alternatively, you can also change the values using the Inspector: 
![](images/Basic3D_2.jpeg)

> You can also use these simple 3D Objects to build complex scenes, for example when using quads as surfaces and then apply a texture to it you can build simple 2.5D-worlds like [here](https://vk-showcase.kh-berlin.de/project/whomans).

# Exercise: Build a Simple Structure with 3D Objects

Goal: Learn to place and transform 3D objects in the scene.

- Add a Plane to act as the ground.
- Add at least three different primitive 3D objects (Cube, Sphere, Cylinder, etc.).
- Position, rotate, and scale each object to create a simple structure (e.g., a table, a tower, or an abstract sculpture).
