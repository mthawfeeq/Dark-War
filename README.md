# Dark-War

- Overview: Develop an FPS game from scratch (from animation, to creating weapons and ammo, emulating physics-based effects, along with the execution of AI-based zombie enemies).

- Character: Started with fixing the camera position behind the SWAT officer, setting up the player health and armor (with full regeneration within a couple of seconds), Crouching and Sprinting animations done using Blender along with fine-tuning the exact map where the walk changes to a sprint and then to a run. Fixed bugs pertaining to not being able to run while being crouched (character's movements looked weird before fixing this particular bug). Created a dynamic red gradient that flashes on the screen when the user is being attacked (referred to as the blood splash effect). Implemented a mini map showing a top-facing view fixed on the user's movements, along with an objective, and a game timer (all part of the HUD). 

- Weapons: Adopted AK47 and M4A1 weapons from Adobe's Mixamo with numpad based switching, created dynamic crosshairs (aiming, shooting), reloading ammo by finding it on the map and muzzle flash when fired. 

- Enemies: Zombies with walking, standing, running (with flailing arms) and attacking animations. Movements based off AI, where it automatically tries searching for the user by randomizing movements (if the user is not visible within a set range) and when the user is found, following the user and once within attacking range, the attack animation is played. When the SWAT officer shoots at the zombie and kills him, it exhibits a ragdoll physics-like death. 

