<h1>This document will highlight some key information, please read over it all before attempting to deploy your server.</h1>
<br>
Once imported the best/default ports to open in your Pterodactyl Node & Modem are,
<br>
	- <stong>Port 7777 UDP</strong> - Pavlov Server
	- <stong>Port 8177 UDP</strong> - Pavlov Listen
	
When you create your server make sure you uncheck the "Start Server when Installed" as the install does not create a basic config,
To create a basic config navigate to your servers "File Management" and goto 'Pavlov/Saved/Config/LinuxServer/'.
Create a new plain text file in this directory with the "New File" button and at the top box after the 'LinuxServer/' type 'Game.ini',
Paste the following example Game.ini from bellow:
<br>
		[/Script/Pavlov.DedicatedServer]
		bEnabled=true
		ServerName=Just Another Pavlov Community Server
		MaxPlayers=25
		bSecured=true
		Password=1234
		MapRotation=(MapId="UGC1668673188")
		MapRotation=(MapId="datacenter", GameMode="SND")
		MapRotation=(MapId="sand", GameMode="DM")
		MapRotation=(MapId="bridge", GameMode="TDM")
<br>
Alternatively as recommended by the official installation guide use an application called "<a href="https://github.com/ToasterUwU/Pavlov-Game.ini-Creator">Game.ini-Creator</a>",
To generate a Game.ini for you.

<i>(Credit to Kubi#8194 for the initial code, however there was some bugs I fixed and parts I rewrote)</i>


<p align="center">
	RyanTheTide - Socials
</p>

<p align="center">
   <a href="https://discordapp.com/users/623410683689566208/">
   <img src="https://img.shields.io/badge/Discord-%232C2F33.svg?logo=discord" alt="Discord">
   </a>
   <a href="https://twitter.com/RyanTheTide">
   <img src="https://img.shields.io/badge/Twitter-%23657786.svg?logo=twitter" alt="Twitter">
   </a>
   <a href="https://www.reddit.com/user/ryanthetide/">
   <img src="https://img.shields.io/badge/Reddit-%23cee3f8.svg?logo=reddit" alt="Reddit">
   </a>
</p>