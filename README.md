#GAMBACORD SERVER TUTORIAL
## Client(just playing)
What you'll need is the SkyFactory 4 modpack which you can get from CurseForge and then add mixin 0.7-0.8  and simple voice chat mod to the mod.
Step one: install Skyfactory 4 (Recommend doing this from the curseforge launcher) 
>https://www.curseforge.com/minecraft/modpacks/skyfactory-4
Step two: download mixin and voice chat mods 
>https://www.curseforge.com/minecraft/mc-mods/simple-voice-chat/files/6787103
>https://modrinth.com/mod/mixincompat?version=1.12.2
Step three: copy the mixin and voice chat file to the mods folder in skyfactory
>(easiest way to get to the mods folder is clicking the right clicking the skyfactory icon if you are in my modpacks or if you are in the skyfactory tab just click the 3 dots at the header -> open folder. In file explorer open the "mods" folder and paste the files there.)
Step four: open the game and join a server

## Server(creating the server for everyone to play)

Before creating a server ask anyone if they had started a server themselves
Step one(first time only): create a github account and download git (if you dont have one already)
Step two(first time only): create a folder somewhere where you'd want to keep the server locally
Step three(first time only): Open the folder -> right click open git bash here then use these commands one by one
> git config --global user.name "John Doe" (change John Doe to your username)
> git config --global user.email johndoe@example.com (change johndoe@example.com to your email)
> git clone https://github.com/hextick/GambaCord_SkyFactory_4.git
Step four(first time only): open the folder GambaCord_SkyFactory_4 and open wrapper.bat using a text editor change
>set LOCAL_DIR=C:\Users\User\Documents\MinecraftServerSkyFactory
to 
>set LOCAL_DIR="C:\...\GambaCord_SkyFactory_4"
change "C:\...\GambaCord_SkyFactory_4" acordingly to where your folder is
Step five: Run wrapper.bat to check if your server works open your minecraft client and connect to localhost:25565
>after testing in the command prompt type "/stop" to properly stop the server
Step six(first time only): For the server to be able for people to join find a tutorial on how to port forward(this is specific to your router so can't really I tell you)
> if you've done this part ask someone in #mc-talk to test if it works
After all is done you can copy "wrapper.bat" to anywhere in your pc it'll work fine(i think) and run the server using that
