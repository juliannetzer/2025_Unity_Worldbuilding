# Exercise Session 3: Refining the diorama

- Open your Diorama scene from the previous sessions (e.g., "DioramaSession2.unity").
- Set up the lighting in your scene:
	- Add a Directional Light to simulate sunlight.
	- Add a Point Light or Spotlight to highlight a specific object or area.
	- Adjust shadow settings (e.g., Soft Shadows, intensity, color) for each light.
- Add a Skybox to define the background and ambient lighting:
	- Download a skybox from one of the online ressources.
	- Import it and assign it in Window → Rendering → Lighting → Skybox Material.
- Adjust the Main Camera to frame your diorama:
	- Select the camera and use "Align to View" to match the Scene View.
	- Adjust field of view.
- Add a Global Volume for post-processing effects: (if it is not in your scene yet)
	- Go to GameObject → Volume → Global Volume.
	- Add overrides such as:
		- Color Adjustments for brightness/contrast
		- Film Grain or Lens Distortion for atmosphere
		- Experiment with Lift, Gamma, Gain to fine-tune the scene's tone.
- Test in Game View:
	- Press Play to preview how the scene looks from the player’s perspective.
	- Adjust as needed — remember changes made during Play Mode will not be saved!


Bonus:
- Create day/night lighting variations by duplicating and modifying the scene.
- Create multiple camera perspectives.

[Back to the overview](readme.md)