FOR BRAWLCRATE, after importing things:

- some textures had been downscaled on v1.0b, they may not be the same resolution as the ones in Textures folder or in the Blender model.
	> e.g: downscale tex0 floor_detail9 to 512x1024 (its original 2048 res crashes the game)
- duplicate materials for backrooms wall, ceiling and carpet, depending on how many extra lightmaps are used
for them.

--------------------

Bugfixes have been done over the blend file with postshading stage + easyReplace materials set up.
They need to be passed onto level0.blend as well in the future if a new version is released
 and new lightmaps have to be baked.

If you don't have to generate new lightmaps and want to do minor fixes,
 you can just work over the postshading stage on level0_postshading_easyR+bugfixes.blend.
 Just remember the material names have been changed for the EasyReplace script for BrawlCrate. 
