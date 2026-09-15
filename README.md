# Nous Racing

A starting point for a Nous community racing game. Actual textured character animations are included—download them and build from here.

## Download the steering animations

| Animation | Editable Blender file | Game/interchange file |
|---|---|---|
| Turn left | [Teknium_Steer_Left.blend](assets/Teknium_Steer_Left.blend) | [Teknium_Steer_Left.glb](assets/Teknium_Steer_Left.glb) |
| Turn right | [Teknium_Steer_Right.blend](assets/Teknium_Steer_Right.blend) | [Teknium_Steer_Right.glb](assets/Teknium_Steer_Right.glb) |

Use **Download raw file** on an asset's GitHub page, or download the whole repository with **Code → Download ZIP**.

Both versions include Mike's rigged Teknium character, its embedded **4096×4096 color texture**, and a visible steering-wheel guide. No separate texture download is needed.

### Use them

- **Blender:** open either `.blend` in Blender 5.2 or newer and press **Space**. The character and wheel have separate named Actions.
- **Game engine:** import the corresponding `.glb`. Each file contains one combined `Animation` clip with skeletal character motion and wheel rotation. Skin weights and the texture are embedded.
- Each turn starts centered, turns **25°**, holds, and returns to center. Timing is **121 frames at 30 FPS**, with four seconds between the first and last key.

These are simple starter animations, not a finished driving game. The hand grip is approximate, and seating/wheel placement will need fitting to the chosen car. The mesh's existing rig and weights are retained. GLB skin data includes all influences; an engine may apply its own influence limit.

### About this version

These downloadable turns are newly authored from the character's rest rig, including a fresh seated pose and finger poses. They do not contain the downloaded Driving Action or other stock animation clips. They are standalone alternatives to the earlier local motion studies, rather than identical exports of those studies.

## Other starting motions

For getting in/out of the car, a driving idle, and honking gestures, the original reference clip names are **Entering Car**, **Exiting Car**, **Driving**, and **Honking Horn** on [Mixamo](https://www.mixamo.com/). Obtain those directly under their own terms; they are not included here. The steering downloads above work on their own.

## Credit and reuse

Teknium character and texture by **Mike (123mikeyd)**, from the [Teknium 3D Model](https://github.com/123mikeyd/teknium-3d-model) release. The character is licensed under **CC BY 4.0**; see [LICENSE](LICENSE). These new steering assets are shared under the same license.

Suggested credit: **“Teknium / Nous Racing starter animations by Mike (123mikeyd), CC BY 4.0.”**

## Take it from here

Build on it, make it your own, and have fun. Fork this repo or open a pull request when you have something to share.

Good luck, everyone! 🏁

—Mike
