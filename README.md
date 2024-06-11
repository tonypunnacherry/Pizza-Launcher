# Pizza Launcher
This is a planned project that will create a unique Minecraft Java game launcher and potentially an in-game client as well. Currently, organizing different modded instances/versions of the game is pretty challenging (requires you to download the game, open it, install Fabric, open it with Fabric, populate the profile folder, load in the mods, then finally open the game). My goal is to make all of this happen with the click of one button! I wish to save players time in setting up different profiles of the game and help keep settings updated across versions. (Example: 1.8.9 client with mods for legacy PVP or a 1.16.1 client for speedrunning).

## Concept
1. Users will be able to create "profiles" with their favorite versions and mod settings
2. The mods and game options will be easy to update and synchronize between profiles
3. Download, prepare profile, set up mods, and open the game all in one step!
4. Share and use invite links into shared profiles/servers
5. Only Microsoft accounts will be supported

## Example Features
1. Settings like sensitivity/FOV will be easily mapped between versions to provide consistency for combat (i.e. 1.21 sensitivity vs. 1.8 sensitivity)
2. Options will be provided to map sensitivity/FOV accurately from other games, allowing players to transition into the game more easily
3. Select mods will be automatically available to be added. Other mods can easily be supported by the launcher via links from various mod sites
4. The newest version will automatically be downloaded and set up (if you enable this option) as soon as possible

...more to be planned!

## Timeline
Currently, the project will be only be developed privately. There is no timeline for completion or public release (if it happens at all). In the future, I may consider extending this to a full performant Fabric-based client with special mods built-in.

## Considerations
1. **protection from others:** The security of our users will be very important. For now, only a few accounts will be used to test/develop this project. We recognize that tokens can be misused to play the game maliciously on other users account. If we release this to the public, a top priority will be to ensure the security and safety of user tokens.
2. **protection from itself:** The code will be working with files in `.minecraft` to organize mods and prepare new profiles. It will be critical that my code does not accidentally delete or corrupt important files related to the game. Different measures to prevent this from occurring will be implemented. 
