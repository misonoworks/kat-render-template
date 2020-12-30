# KAT Profile Render Template
 A rendering template for KAT sets, contains 87 keys used on TKLs.
 ![KAT Danmaku](https://i.imgur.com/OaOvgay.jpg)
 
## Included Files
* KAT_TKL_TEMPLATE.blend - The blender project file with all keys and legends set up.
* KAT_UV.png - The default UV map for this template
* kat_UV.svg - An editable 8k UV map file in case you want to change fonts, legends, or add novelties.
* sample.png - A sample render of this template. The keyset is **KAT Danmaku.**

## Usage
This blender file uses a UV map as opposed to shrinkwrapped legends. This enables much broader and easier customization, as well as running much smoother and lowering render times. This is also much lighter on computer performance than shrinkwrapped legends are.

#### Changing Colors
1. Open **KAT_TKL_TEMPLATE.blend**
2. Select a key (there are accents, modifiers, and alphas. Changing the color of one will automatically change the colors of the rest in the group.)
3. Look at the **Node Editor.** 
4. Navigate to the **MixRGB node.**
5. Change your colors to your desired color. There should be two color boxes on the node. One controls legend colors, the other controls cap colors.
6. Colors!


#### Changing Legends
1. Open **kat_UV.svg** with a vector editor of your choice.
2. Import your legends (whether it be novelties or actual legends)
3. Upscale your legends to fit on the positioning squares provided. (*Note: These positioning squares, by default, are white. If you are using a center-snap constraint, centers of legends will automatically snap to the centers of these. Otherwise, to manually position, change the color of these squares to a visible color.)
4. Export your file as kat_UV.png at 8000x8000px.
5. Re-open the project file, and your legends should now be changed.

#### Rendering
1. Navigate to the top of your Blender window
2. Click the **Render** dropdown tab and click **Render Image**
3. Wait a little bit, go get a snack. Maybe eat some chocolate. Or don't, I'm not the boss of you.
4. Gaze upon your beautifully 3D keyset!
In order to get a higher resolution render, click on **Output Properties** below the list of objects in the scene. Raise the value of the % field, this will scale your render according to your aspect ratio. (Ex: a 150% render of 1920x1080 will be 2880x1620)
