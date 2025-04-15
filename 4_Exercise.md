# Exercise: Bring Your Diorama to Life with Animation, Audio, and Video

- Open your diorama scene from the previous sessions (e.g., "DioramaSession3.unity").
- Add at least one animation to a GameObject in your scene:
	- Open Window → Animation → Animation.
	- Select a GameObject (e.g., a cube, door, light, or camera).
	- Create a new Animation Clip and animate at least one property (e.g., position, scale, rotation, visibility).
	- Disable "Loop Time" if you want the animation to play only once.
- Add a sound effect or background music:
	- Import an audio file (e.g., MP3 or WAV) into the Assets folder.
	- Create an Audio Source (GameObject → Audio → Audio Source).
	- Assign the sound and enable Play on Awake or trigger it via animation.
	- Optionally: Use spatial audio to attach sound to a specific object.
- (Optional) Include a video element:
	- Import a .mp4 video file.
	- Create a Quad to act as a screen.
	- Drag and drop the video onto the Quad to auto-attach the Video Player component.
	- Scale the Quad according to the video’s aspect ratio (e.g., 16:9).
	- Adjust the Audio Output Mode to use an Audio Source if needed.
- Organize your hierarchy:
	- Group animated elements, audio, and video objects into labeled Empty GameObjects (e.g., Animations, Sound, Media).
- Test in Play Mode:
	- Press Play and observe how animation, audio, and video contribute to the scene.

[Back to the overview](readme.md)