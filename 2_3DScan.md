## <a name="3d scan"></a>3D Scanning Software

3D scanning apps allow you to capture real-world objects and convert them into digital 3D models, making them useful for creating realistic assets for Unity projects. These apps use photogrammetry or LiDAR technology to reconstruct objects and environments in high detail.

Two apps that work on mobile phones: 
- [Polycam](https://apps.apple.com/de/app/polycam-lidar-3d-scanner/id1532482376)
- [Luma AI](https://apps.apple.com/de/app/luma-3d-capture/id1615849914)

> Note: 3D scanned models are often very detailed and Unity can't handle the data very well. To make sure that Unity can handle the models, you can decimate your 3D-Models in the 3D-Software Blender, you can find a Tutorial here: https://www.youtube.com/watch?v=N4QY-1Vf6LM 

Capture a Real Object Using a 3D Scanning App

Goal: Scan a real-world object and bring it into Unity.

- Install Polycam on a smartphone.
- Capture a scan of a simple object (e.g., a cup, chair, or toy).
- Export the model as .glb and import it into Unity.
- Optimize performance by reducing polygon count in Blender (see tutorial here).
- Place the scanned object in your scene.


[Go to next section](2_OnlineTools.md)\
[Back to the overview](readme.md)