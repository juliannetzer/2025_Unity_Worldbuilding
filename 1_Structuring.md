# How to structure your unity projects

A well-structured Unity project is essential for maintaining organization, efficiency, and scalability. As projects grow, managing assets, scenes, and scripts becomes increasingly complex. Proper folder organization helps prevent clutter and makes collaboration easier.

Key best practices include:
## Organizing assets into folders 
You can use folders in the Project Window to organize your assets. To create a new folder, right-click inside the Project Window and select Create -> Folder.

Here is an example of a recommended folder structure: 
Assets/
│── Animations/         # Animator controllers & animation clips  
│── Audio/              # Sound effects, background music  
│── Materials/          # Materials and shaders  
│── Models/             # Imported 3D models  
│── Textures/           # Images for materials and UI  

## Using clear names
Using consistent names helps avoid confusion and ensures files and GameObjects are easy to locate.

## Organizing GameObjects
In Unity, you can use Empty GameObjects to organize objects in your scene, similar to how folders help structure files in the Project Window. This improves hierarchy management and makes it easier to navigate large scenes.

How to Create an Empty GameObject:
- In the Hierarchy Window, right-click and select Create Empty (or use GameObject → Create Empty from the menu).
- Rename it to reflect its purpose (e.g., "Environment", "UI Elements", "Enemies").
- Drag related GameObjects under the empty GameObject to group them together.

> When you group GameObjects under an Empty GameObject, you can move and scale them all at once by adjusting the parent object. This makes it easier to manage and reposition groups of objects within your scene.

[Best practices of organizing your unity project](https://unity.com/how-to/organizing-your-project)

