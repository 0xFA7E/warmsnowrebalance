# warmsnowrebalance
Rebalancing Mod for Warm Snow

This mod adjusts the later difficulties(notably snowstorm and blizzrad(sic) ) to more sane values for HP. Blizzard is now a slightly beefed up heavy snow but the
later stage enemies are significantly toned down so HP bloat is a tad closer to a linear increase instead of the massive bump in vanilla with snowstorm difficulty being
slightly inbetween the two. Chosen values were because it sounded good, and feedback on finetuning is highly welcomed. Other rebalancing effects/mods may come if interest is raised. 


# Installing EZ Mode

If you want minimal hassle installing the mod, simply copy the Assembly-CSharp.dll file into the game's managed data directory
c:\\(path to your SteamLibrary)\steamapps\common\WarmSnow\WarmSnow_Data\Managed\

Overwrite the existing file there or rename the old version if you wish to revert(reverifying the game files in steam will also revert the mod changes). 
Note that this method *WILL* break upon any sort of game update whatsoever. 

# Installing with Melon Loader

Melon Loader is a modding framework/manager for Unity Games and the HP rebalancing mod can be installed with it. To do so follow the instructions at 
https://melonwiki.xyz/#/?id=automated-installation

Once melonloader says it has succeeded, open up the game once so that melonloader can create the necessary folders. You will now see a Mods folder in the WarmSnow game folder
Copy the WarmSnowHPRebalance.dll file to this folder and then launch the game and enjoy!

As a reminder the folder location would be c:\\(path to your SteamLibrary)\steamapps\common\WarmSnow\Mods\
