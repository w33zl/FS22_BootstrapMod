# Bootstrap Mod for Farming Simulator 22

This is a "mod bootstrap"/blueprint/base template for Farming Simulator 22 (FS19) mods. Use this as a base for new mods to get you started quickly. The package also contains a CHECKLIST readme file which helps you ensure that you have covered at least all the basic steps needed to complete your mod. 

## Instructions

### Step 1
1. Download the [latest version](https://github.com/w33zl/FS22_BootstrapMod/releases/latest) from GitHub
2. Extract the contents of the archive
3. Copy the folder `FS22_BootstrapMod` to your mods folder
4. Rename the folder to your desired mod name accordingly to Giant's guidelines, e.g. `FS22_MyModName`
5. Follow the steps in the CHECKLIST.md file 
6. Have fun!

### Step 2
* A) If your mod contains script - rename all references to the variable `YourModNameHere` in the LUA file and rename the LUA file itself (`YOURMOD_RENAME_THIS_FILE.lua`)
* B) If your mod ***does not*** contains script - remove all references in the `<extraSourceFiles>` section of your modDesc.xml


## Like the work I do?
I love to hear you feedback so please check out my [Facebook](https://www.facebook.com/w33zl). If you want to support me you can become my [Patron](https://www.patreon.com/wzlmodding) or buy me a [Ko-fi](https://ko-fi.com/w33zl) :heart:

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/X8X0BB65P) [![Support me on Patreon](https://img.shields.io/endpoint.svg?url=https%3A%2F%2Fshieldsio-patreon.vercel.app%2Fapi%3Fusername%3Dwzlmodding%3F%26type%3Dpatrons&style=for-the-badge)](https://patreon.com/wzlmodding?)

## Tips

### Weezl's Mod Library
A basic version of the library "WeezlModLibrary" is included in the bootstrap mod. This contains some quality of life utility classes that makes it easier to get started and developing your script based mod. See [FS22_WeezlsModLib](https://github.com/w33zl/FS22_WeezlsModLib) (GitHub) for more details and latest version.

### Creating a mod icon
Paint.NET is a free and capable image edititing tool similar to Photoshop that is fully sufficient for creating the mod icon/thumbnail. In the bootstrap package there is a Paint.NET template provided that has the correct dimensions and background for a valid ModHub thumbnail image.

You can also easily add text and/or icons in tools like PowerPoint and just copy-paste them into Paint.NET, which is a quick and easy method for creating your mod thumbnail. If you are creating a vehicle/equipment mod you can simply drag-and-drop the store icon into modIcon.pdn template in Paint.NET to create your icon, quickly and easily.




