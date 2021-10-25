# Blender-GenshinPBR
Shader for Blender attempting to make use of Genshin Impact's PBR environment textures.

## Preview
![Preview](/preview/preview1.png)
![Preview](/preview/preview2.png)

## Usage
1. Download the shader [here](https://github.com/Festivize/Blender-GenshinPBR/releases/download/v1.0/GenshinPBR.v1.0.blend).
2. Append the material *GenshinPBR* OR nodetree *GenshinPBR version number* to your project.
3. Plug the textures to their respective slots **if applicable.**

## Notes
Unfortunately, Blender does not have an efficient way of implementing parallax occlusion mapping in EEVEE. The height maps are intended to be used as such. However, you can always use it as an actual displacement map. I will be updating this if ever POM will be implemented.

## Special Thanks
Fallenleader - for the calculations. I merely implemented it into Blender.
