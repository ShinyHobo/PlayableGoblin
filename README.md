# PlayableGoblin
Mod for Baldur's Gate 3 that allows you to play as a goblinoid.

Candor compatible.

To install this mod manually, extract and copy the .pak file into your \Documents\Larian Studios\Baldur's Gate 3\Mods folder, then update your desired profile's modsettings.lsx file, using notepad or something similar, by adding the following node:

<node id="ModuleShortDesc">
    ﻿<attribute id="Folder" type="LSWString" value="PlayableGoblin"/>
    <attribute id="MD5" type="LSString" value=""/>
    <attribute id="Name" type="FixedString" value="PlayableGoblin"/>
    <attribute id="UUID" type="FixedString" value="d551044c-30ed-43c8-a615-453b2a099808"/>
    <attribute id="Version" type="int32" value="1"/>
</node>

If this is your first mod installed like this, please ensure the node goes after the closing tag (<node/>) of the Gustav "mod", or else it won't work. Finally, make the modsettings.lsx file readonly, or else the game might overwrite it, and you'll lose all your hardwork!