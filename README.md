## minecraft-server-control
How to remotely start and turn off a minecraft server via discord. **(In order for it to work, the pc must be on at times when runninng the commands.)**

## downloads
https://github.com/Arvinth-Krishna/Reco-PC-Server
^ This is the setup so you can send commands through discord that the pc can then read. 
(WARNING: I couldn't find a way to disable commands from just the whole bot. I just deleted everything in the module files except __init__.py, abort.py, and launch_module.py)

Copy the download link of the latest [Minecraft version here](https://www.minecraft.net/en-us/download/server/).
^ Download the .Jar to start a multiplayer server

I used this to make the server multiplayer by [Playit.gg](https://playit.gg/)
How to make it multiplayer without port forwarding

AutoHotKey was used to shutdown the server. Download for [AutoHotKey](https://www.autohotkey.com/)

## AutoHotKey to Gracefully turn the Minecraft Server 
You are wondering why I can't just use a .bat file to shutdown the server. A .bat cannot write to a different .bat file. 
If there is, I couldn't figure a way. I just used autohotkey. 
If you use a .bat file to /taskkill, this unfortantely won't save the minecraft server, and/or may cause some server corruption. 


## How to get it working
**First, I will assume that you have already created the discord server with the bot ready to go. 
And also, that your minecraft server is setup. 
If you need a tutorial on how to do everything, then I will link another post.**
Locate the shortcut folder within the Reco folder. 
Then, you want to make a shortcut of the .bat file that starts the minecraft server server and playit-gg.exe.
Move the shortcuts within the shortcut folder within Reco folder. 


