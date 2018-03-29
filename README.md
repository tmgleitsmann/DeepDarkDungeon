# DeepDarkDungeon
Cross Platform (best suited for iOS) mobile game where user can select 6 characters to fight 6 monsters. Supports use of consumables, weapons, armor, boots, and rings to modify character attributes.
*Unplayable, but runable on android and uwp.* *Functionality for Defend currently does not exist*

BEFORE YOU DO ANYTHING TO THE FILE, RESTORE YOUR NUGET PACKAGES. This will restore the proper simulators to the solution so you can build and run. 

THERE ARE BUGS! 
- Need to have at least 1 character/ monster in the mock/sql database for the game to work without having a collection population error. 
- Needs the proper nuget packages downloaded! This includes sqlite, sqlite-net, sqlite-net-pcl and Xamarin.Forms
- Images may display in awkward sizes across all platforms. To fix this, height/width requests can be set in .xaml files where images are displayed, or the images themselves in the project can be cropped to different sizes.
- Certain methods should be refactored to be more independent. 
- LevelUp checks needs to factor in multiple level ups. Currently it will only increment level by 1 if check passes.

TO PLAY:
- there are default characters, monsters, and items upon building the game. You can create, read, modify, or delete the attributes of each on their individual pages. 
- Auto Play will run the game until all your characters are dead and display your score. 
- Battle will allow you to pick 6 characters and 6 characters
- When battling click attack and then click on the monster you want to attack. Fight until you can't fight anymore. 
