A little map dev/mod dev utility to help people working with nbt items and tiles.

# Item NBT
To see an Item NBT tag just activate the advanced tooltips by pressing F3+H, the tag will appear inside the tooltip. Longer tags will be presented in an auto scrolling view, the scroll speed can be controlled with SHIFT, to pause scrolling, and ALT, to speed it up. The default scrolling speed and the maximum number of tag lines shown at once can be configured.

 

Tile Entity NBT (Not available in newer versions)
To see a Tile Entity NBT right click with an arrow on the block you're interested in. One or two popup windows will appear, depending on your configuration and what mode (SP/MP/LAN) you're playing.

One window will hold the server-side information (Only if you're playing SP) the other one will show client-side information (Both SP and MP). What windows are shown is configurable.

The client tag will often be a subset of the information contained inside the server one, this is because of how minecraft deals with syncing the tags. In general, it's up to the TE's creator to decide what data gets sent to the client (A modder should remove all the data unecessary to the client, to reduce the network load: this prevents you from seeing all the data if playing on a server).

The windows are separate from the Minecraft window, and should appear in the background, without interrupting your game, and they can be closed without effects on the game. Only one set (Server + Client) will be shown at a time, to prevent flooding your screen with popups: opening a new one will just replace the existing one.



