--| Call of Chernobyl Relay Chat
--| Version 0.9.3
--| By Thom-Rum
--| https://github.com/Thom-Rum/Call-Of-Chernobyl-Relay-Chat/


An integrated chat client for Call of Chernobyl 1.4.12 or later, with any and all addons.
.NET and Nuget packages have been uplifted, and Gamesurge IRC is now used.
Bug reports and suggestions should be raised in the Github Repository under issues.

Original work was done by TKGP, and all credit and glory goes to them. Uplift to newer dotnet and nuget versions was done by Thom-Rum.



--| Installing CoCRC

1. Install the [.NET framework](https://dotnet.microsoft.com/en-us/download/dotnet-framework/net48) if you don't have it already  
2. Download CoCRC-(latest-version).7z from the Releases section, and use 7zip or another program to unzip CoCRC-(latest-version).7z.
3. Copy the files inside the folder into your Call of Chernobyl directory.

--| Upgrading CoCRC

1. Open Registry Editor in Windows, and go to HKEY_CURRENT_USER -> SOFTWARE -> Chernobyl Relay Chat
2. Delete the Chernobyl Relay Chat folder in Registry Editor.
3. Proceed with normal installation.


--| Usage

Run Chernobyl Relay Chat.exe; the application must be running for in-game chat to work, and you can use it as a standalone client as well.
After connecting, click the Options button to change your name and other settings, then launch CoC.
Once playing, press Enter (by default) to bring up the chat interface and Enter again to send your message, or Escape to close without sending.
You may use text commands from the game or client by starting with a /. Use /commands to see all available commands.


--| Building / Troubleshooting 
Should you need to clone, or fork this repository and revive CRC, I recommend using Visual Studio, with .NET framework 4.8.
One of the most annoying issues I've encountered when working on CRC is that after making changes and committing, Visual Studio will then proceed to build an old version of CRC.
For example, you've just changed the IRC channel from #crc_english to your own test channel, but when you build CRC you find you still connect to the old IRC channel.
To fix this, go to Registry Editor -> HKEY_CURRENT_USER -> SOFTWARE -> Chernobyl Relay Chat. Then delete this folder. In Visual Studio go to Build, and then Clean.

The package GithubUpdate is no longer supported by the owner, and relies on Octokit 0.3.4. Do not try to update Octokit to the latest version, as this can cause errors and crashes.

--| Credits

Chernobyl Relay Chat: TKGP
Chernobyl Relay Chat Rebirth: itsAnchorpoint
CoCRC Testers and family: Tolik_Lucky_Bastard, ElekTrick, Pretov, Pogodemon, Manny, TwistedLoner, Dancher743 and everyone who uses CRC and helped me with testing and keeping the community alive.
GitHub: Octokit
Max Hauser: semver
Mirco Bauer: SmartIrc4Net
nixx quality: GitHubUpdate

av661194, OWL, XMODER: Russian translation

Join us on our Discord channel for announcements and support with CoCRC - https://discord.gg/deJxyjU3vB
