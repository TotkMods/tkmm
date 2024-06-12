# Settings

 If you click on the three lines near the top left of the window, the navigation sidebar will expand to show the names of each tab. Click on the **Settings** tab, which is represented by the cogwheel icon.

![Image of TKMM's Common Settings page before a valid game dump has been shown.](../../../images/Setup_03_CommonSettings_DumpInvalid.png)


For all users, whether you plan to use TKMM to package mods or to merge mods to play with them, you will need to specify your game dump location. In the **Common** settings category, shown in the above image, choose the folder that contains a full romfs dump of Tears of the Kingdom. This is the folder that contains many other directories, such as a `Model` folder, a `Pack` folder, a `TexToGo` folder, and many others. If your dump is valid, the vertical line on the left side of the **Game Path** box will switch from red to green, as shown below:

![Image of TKMM's Common Settings page before a valid game dump has been shown.](../../../images/Setup_03_CommonSettings_DumpValid.png)

---

## Important Note Regarding Game Versions

The version of your game dump is the version that TKMM will export mods for. For example, if your game dump is from v1.1.2 of TOTK, then TKMM's merged mod folder will be compatible with v1.1.2. TKMM's merging system is version agnostic, meaning that regardless of the game version a mod was made for, TKMM can export it to the version of your game dump.

---

Next, select the **Merging** tab. Here is an image of this tab, followed by a description of each of the options:

![Image of TKMM's Merging Settings page](../../../images/Setup_04_MergingSettings.png)


1. Merged Mod Output Folder

This is where you can choose the output path for your mods when you merge them. When you merge mods, the contents of this folder will be deleted, so it's recommended to create a new folder for this.

2. Target Language

If you are using a mod that edits the localization files found in the **Mals** folder in the romfs, there is a chance that it doesn't support all languages. If the language entry for a given string does not exist for a given language, it will appear in game as *MsgNotFound*. If you choose your target language, TKMM is able to automatically move a mod's localization edits to the file for your language, removing the *MsgNotFound* issues.

3. Use Ryujinx

By enabling this option, merging your mods will automatically export a copy of your Merged Mod Output Folder to the default mods path for Ryujinx. This is a quality of life option that mitigates the need for you to move your merged export to the emulator's mods folder yourself.

4. Use Japanese Citrus Fruit

By enabling this option, merging your mods will automatically export a copy of your Merged Mod Output Folder to the default mods path for Japanese Citrus Fruit. This is a quality of life option that mitigates the need for you to move your merged export to the emulator's mods folder yourself.