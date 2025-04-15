# Exercise: Make Your Diorama interactive

- Open your diorama scene (e.g., "DioramaSession4.unity").
- Add a playable character:
	- Install the "Starter Assets – Third Person Controller" from the Unity Asset Store.
	- Drag and drop the NestedParentArmature_Unpack.prefab into your scene.
	- Position the character at a visible starting point.
	- Deactivate the existing Main Camera (the prefab includes its own).
	- Press Play to test the movement (keyboard & mouse).
- (Optional) Replace the default character:
	- Download a Mixamo character and import the .fbx with T-Pose into Unity.
	- Replace the model inside the prefab as shown in the tutorial.
	- Make sure the new character avatar is assigned correctly.
- Add a simple dialogue interaction:
	- Install the Dialogue System by HeneGames from the Asset Store.
	- Drag the Dialogue UI prefab into your scene (this adds the visual interface).
	- Add a Dialogue 3D prefab to the scene (this will trigger the dialogue).
	- Position the trigger near an object, such as a statue, tree, or bench.
	- Add at least 3 sentences to the dialogue and optionally assign a character name and audio clips.
	- Adjust the trigger to start automatically or require a key press.
- Organize your hierarchy:
	- Create Empty GameObjects for Player, Dialogue, and Triggers.
	- Keep your scene tidy and easy to navigate.

## Test your scene:

- Press Play.
- Walk to the dialogue trigger and confirm the system activates.
- Check for any missing references, errors, or camera issues.

[Back to the overview](readme.md)
