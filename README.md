# LostCityAssets
This is an example Lost Cities assets datapack for 1.18+

This can be used as a reference for your own assets. This example does the following:
* Adds a new chest loottable called 'testloot.json'. Use this loottable with a big chance by overriding conditions/chestloot.json
* Replace all parts (levels) of building1 with new parts where there are a lot of chests
* Replace the common palette to have different things in the 'F' palette entry
* Add a new citystyle called 'teststyle'. This citystyle restricts buildings to 'building1'
* Add a new worldstyle called 'testworld'. This worldstyle uses the 'teststyle' citystyle

# How to install
* Get a clone of this repository (using git or download as a zip).
* Make a zip file at the root of this repository (so the directory contains 'data', 'META-INF', and 'pack.mcmeta'. So these three files should be at the root of the zip
* Rename the zip file to jar
* Put the jar file in the mods folder of your modpack or instance

As an alternative you can also download the jar directly from this page (it's a released file)

# How to use
There are two ways to use this datapack. With the first way you just create a normal Lost Cities world. If you do that then you still get all buildings but building1 will have a lot more chests and use different loot. With the second way you create a customized Lost Cities world where you select the 'testworld' worldstyle (you can do that in the top of the Lost Cities customization page). In this case you'll only get building1 in the world
