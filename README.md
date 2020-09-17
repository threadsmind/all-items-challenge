# all-items-challenge
 "All Items Challenge" is a Windows 10 Bedrock Minecraft server-side mod that uses the beta scripting API to allow players to track when they collect a new item for the first time.

 ## How Do I use this?
 1. Download the `all-items-challenge.pack` file from the pack folder.
 2. Double-click on the file.
 3. Minecraft (Windows 10 edition) should open with a toast notification at the top saying that it is importing the behavior pack.
 4. Once the import completes you will receive another toast notification.
 5. Create a new world.
 6. Scroll down in the world options and activate "experimental gameplay" & "cheats".
 7. On the left-hand side of the screen, scroll down to "Behavior Packs" and click on it.
 8. Click on "My Packs".
 9. Click on "All Items Challenge".
 10. Click on "Activate".

 ## FAQs
 * Q: Can I use this mod on Java Minecraft?
 * A: No. The Scripting API is Mojang's beta solution for mods in the Bedrock version of Minecraft only.

 * Q: How do I check which items I still need?
 * A: At the moment... the only option is to run `/tag @s list` and find the tag that starts with "itemList". As I wanted this mod to work cross-platform with a Windows-hosted game, there is no client-side modded data. In the future I will release a client-side companion mod with a GUI display that you can use in singleplayer or with other Windows 10 players.

 * Q: Can I use this on another console version of Bedrock Minecraft? (XBox, Playstation, Switch, mobile...)
 * A: Not directly. At the moment, due to security concerns with other consoles, scripting is only available on Windows 10. HOWEVER if a Windows 10 player hosts a world with this mod active, players from other consoles can join and play with the mod.

 * Q: Why do I need to activate cheats & experimental gameplay?
 * A: At the moment this is a requirement for using any behavior packs with scripts. It's not ideal, but as long as you're playing with people you know or trust, it should be fine.

 * Q: Does this mod persist data?
 * A: Yes. As long as you do not clear player tags, your item data will remain until you delete your world.
