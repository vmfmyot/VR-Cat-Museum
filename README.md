
# VR Cat Museum

Virtual Reality cat museum developped in 4 week, as a final project for a Fundamentals of eXtended Reality class.
## Authors

This project was made by [Sidonie Minodier](https://github.com/shidowe), [Victoria Myot](https://github.com/vmfmyot) and [Gleda Uisetiawan](https://www.linkedin.com/in/gledaui/), 1st year HCI Master students at Paris-Saclay University.
## Project Description

This project aims to stimulate an interactive virtual museum visit. The objective of such VR-based visits is to enrich
and enhance visitors' experience during museum exhibitions or excursions. In addition, VR makes it
possible for visitors to explore inaccessible, hard-to-reach places, and to recreate sites and artefacts
that were destroyed long ago. Interactive exhibits designed for both adults and children can further
support learning by providing engaging ways to discover the history of an artifact or a ruin.
\
\
Our museum is cat-themed, and consists in 3 rooms :
- An egyptian/antique-themed exhibition
- A modern art exhibition
- A main room to display skeletons and other decorations

## Tools

This project was developped on the Unity Game Engine, using an HTC Vive Cosmos 2 headset. \
\
Our museum layout was designed and built using the SweetHome3D software. However, the rest of our 3D assets were all found online and are free-of-use. Credits will be given further below.


## Implemented features and groupmembers contributions

We mostly worked on the project on-site in order to gain access to the hardware, so most features were implemented as a group.

### _3D museum layout_
**Gleda**\
We made a very basic sketch of the overall layout during a brainstorming session. Then, Gleda modelled the entire museum in SweetHome3D, and added textures and assets before exporting it to the main scene.

### _Colliders and physics_
**Sidonie**\
Colliders and physics were added to all our 3D objects to ensure a smooth and realistic VR experience.

### _Ambiant lighting_
**Gleda**\
When the player gets close to an artifact or a painting in the Antique and Modern rooms, ambiant lights appear to set focus on it. Consequently, getting away from said artifact will turn the corresponding light off. This scripted behavior was implemented with the help of collision events.

### _3D artifacts and assets_
**Victoria**\
Exhibitions themes were decided as a group. Then, all 3D assets were gathered, imported into the project, resized and placed in their spots by Victoria.

### _Virtual navigation_
**Sidonie**\
Player can use the joystick to move around the museum (glyding metaphor). It is advised to use both joysticks when playing: to move, use the left joystick, and to point at things use the right one.

### _Spatial audio_
**Gleda**\
Each room has their own background music that fits the theme of the exhibition. When moving from one room to the other, the audio changes accordingly.

### _Ray casting manipulation of objects_
**Sidonie and Victoria**\
Some objects, such as Information Panels for each artifacts and the Puzzle Minigame are interactable through ray casting. Ray casting works better using the right joystick.

### _Puzzle minigame_
**Sidonie**\
Our museum contains a small puzzle minigame with grabbable pieces. Unfortunately, because of time constraints, we didn't have time to complete it.

### _Information panels_
**Gleda and Victoria**\
Each artifact has a scrollable canvas that displays information with a 3D TextMeshPro. Artifacts descriptions was gathered by Gleda, and Victoria added the information panels to each artifact in the museum.

### _Timer_
**Victoria and Sidonie**\
We added a timer to count down the time spent in the museum. This timer UI is always visible to the player. The UI canvas was made by Sidonie, and the scripting was handled by Victoria. For some reason, it doesn't show in our demonstration videos (screen recordings in game mode), but it is visible in the headset at all times.


### _Project report_
The README.md was written by **Victoria**.

## Video demonstration

embed video in git TODOOOOOOO



##  Challenges encountered

We encountered several challenges during this project, mostly from our interaction setup.
- **Hardware issues :** it took us a week to set up the headset with our Unity project. Furthermore, until the last class we still had an issue with our **controllers**, where they would immediately get deactivated in game-mode even tho they were activated in editing scene.
- **Movement integration :** we had quite some difficulties adding movement in-game. At first, we tried to add teleportation points, but ended up scrapping it as we managed to implement gliding movements. Even tho we reused the prepared assets from the Demo Scenes, it never worked the same way in our project. Additionally, sometimes our movement setup would randomly switch to teleportation for a single game test.
- **Ray casting :** this issue is also part of our interaction set. We had a lot of difficulties making our ray casting appear, especially because it was in conflict with our movements.
- **Camera falling** : whenever we try grabbing objects, our camera falls to the ground.

## Credits

Add all credit links for the images and 3D assets
