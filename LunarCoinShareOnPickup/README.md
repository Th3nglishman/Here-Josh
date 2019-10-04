#LunarCoinShareOnPickup

	**Main Function:**
	╔══════════════════════════════════════════════════════════════════════╗
	║When one player in the lobby picks up a Lunar Coin, each player in the║ 
	║lobby will receive a Lunar Coin.                                      ║
	║                                                                      ║                                 
	║No more hate and envy against the person who grabs them the quickest. ║                                                                
	╚══════════════════════════════════════════════════════════════════════╝
	
	**Secondary Functions:**
	╔════════════════════════════════════════════════════════════════════════════════════════╗
	║Change the Lunar Coin amount that each player receives when a Lunar Coin gets picked up.║
	║Change the Lunar Coin amount that the person who picks up the Lunar Coin receives	     ║
	║(The shared and unshared amount of Lunar Coins stack, so the unshared part just gives   ║
	║extra Lunar Coins to the player who picks up the Lunar Coin)          					 ║             
	╚════════════════════════════════════════════════════════════════════════════════════════╝
	
	Working in singleplayer and multiplayer
	Fully configurable via config file.
	
#Config
	
	To change values in the config you have to start the game once with
	the .dll inserted so the config file gets generated.
	
![config](https://www.bilder-upload.eu/upload/1a7f58-1557822078.png) 

#Installation
	
   Drop the LunarCoinShareOnPickup.dll into \BepInEx\Plugins\
   
#BugReport
	
   To report bugs pls message me via the offical modding discord.
   My username is dan8991iel.

#Patchnotes
	v 2.0.0
		Fixed a bug which stopped players from picking up lunar coins if another player is dead.
		Updated the dependencies in the manifest
	v 1.5.0	
		Added:
			Config to change the Lunar Coin shared and unshared amount.
	v 1.0.0
