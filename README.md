# Genshin Impact PBR environment shader for Blender
Shader for Blender attempting to make use of Genshin Impact's PBR environment textures.

## Preview
![Preview](/preview/preview1.png)
![Preview](/preview/preview2.png)

## Usage
1. Download the shader [here](https://github.com/Festivize/Blender-GenshinPBR/releases/).
2. Append the material *GenshinPBR* OR nodetree *GenshinPBR* to your project.
3. Plug the textures to their respective slots **if applicable.**

## Milestones
- [x] Shader for materials utilizing the SMBE texture
- [ ] Shader for materials utilizing the LSAB texture (mostly plants)
- [ ] Use the height texture for POM *(impossible atm, the shader only uses it for the height input on the Bump node)*

## Notes
Unfortunately, Blender does not have an efficient way of implementing parallax occlusion mapping in EEVEE. The height maps are intended to be used as such. However, you can always use it as an actual displacement map or like in the shader, use it as a height map for the Bump node. I will be updating this once POM is ever implemented.

## Special thanks
Fallenleader - for the calculations. I merely implemented it into Blender.
