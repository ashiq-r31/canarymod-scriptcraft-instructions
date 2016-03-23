##Setting up CanaryMod and Scriptcraft
This the ultimate easy-to-follow guide to get started with CanaryMod and Scriptcraft. 

Thanks to the CanaryMod team and Walter Higgins for their great resources that allow kids to learn to build mods in Minecraft with Javascript code. The origin tutorial to get started with developing mods in Javascript using CanaryMod and Scriptcraft is here: https://github.com/walterhiggins/ScriptCraft/blob/master/docs/YoungPersonsGuideToProgrammingMinecraft.md

However, the tutorial skips over some crucial steps to setup CanaryMod and Scriptcraft that will get almost anybody running into several roadblocks. This is my version that adds a few extra steps to the original installation guide. 

##Installation

1. Download `Java` from the Java website and install it on your computer. This will allow you to run CanaryMod and Scriptcraft.

2. Once installation is complete, open your terminal by searching for `terminal` if you are on Mac or `cmd` if you're on Windows. The terminal is where your CanaryMod server will run while playing Minecraft. Type the command
`java` and hit the return key. If you see the response below, it means Java has been installed successfully in your computer and the terminal can now recognize Java based commands. <img width="827" alt="java" src="https://cloud.githubusercontent.com/assets/7483633/13989096/4ab4ef88-f128-11e5-925c-5b4c0a8bb35b.png">

3. Download CanaryMod from the following link http://scriptcraftjs.org/download/latest/
and Scriptcraft from the following link http://scriptcraftjs.org/download/latest/scriptcraft-3.2.0/. After downloading the files, rename the CanaryMod file as `canary.jar` (Trust me, this will make your life much easier in the future). 

4. Create a folder called `Canary` and copy your `canary.jar` and `scriptcraft.jar` files into the folder. 

5. In your new `Canary` folder, double click your `canary.jar` file. This will initialize all the necessary folders and files to run CanaryMod on your computer. Move your `scriptcraft.jar` file to the `plugins` folder that has been created.

6. In the `Canary` folder, open the `eula.txt` file with any text editor. Find the line that has the value `false` and change it to `true`.

7. Okay, we're almost there! In order to build our mods in peace, we want to configure our world to be flat and play in creative mode as well as not be bothered by creatures. Go to `config/worlds/default` and open `default_NORMAL.cfg` with any text editor and change the following lines as below:
```
world-type=FLAT 
generate-structures=false 
pvp=false 
gamemode=1
spawn-villagers=true
spawn-golems=false
spawn-animals=false
spawn-monsters=false
```




