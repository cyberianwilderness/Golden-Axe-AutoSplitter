# Golden-Axe-AutoSplitter
Autospliiter script for Golden Axe (SEGA Mega Drive/Genesis Version)

# Setup Guidance
For this script to work you will need
- [LiveSplit](https://livesplit.org/downloads/)
- [ASL Var Viewer](https://github.com/hawkerm/LiveSplit.ASLVarViewer)
- Kega Fusion 3.64 Emulator
- The game itself!

# Configuring your livesplit
Assuming you have Livesplit, ASL Var Viewer and Kega Fusion all downloaded and working. 
Insert the ASL Var Viewer into the components folder of Livesplit. 
Create your own splits or download them from the [Split-Files folder](/Split-Files/). 
- [Arcade](/Split-Files/Golden%20Axe%20-%20Arcade.lss)
- [Beginner](/Split-Files/Golden%20Axe%20-%20Beginner.lss)
- [Duel](/Split-Files/Golden%20Axe%20-%20The%20Duel.lss)

Note: The Sega CD and beginner Co-Op categories have not been tested with autosplitters, but Beginner splits should work with Beginner Co-Op.

## Adding the auto splitter
> [!TIP]
> Right click on Livesplit  
> Click on Edit Layout  
> Add Button > `Control` > `Scriptable Auto Splitter` (pictured)  

![Adding the splits](/Images/adding-scriptable-auto-splitter.png)

---

> [!TIP]
> Select the `GA-ASL.asl` file wherever you have saved it using the browse button.  
![Inserting autosplitter](/Images/selecting-auto-splitter-script-before.png)

---

> [!TIP]
> Once you have selected it, Livesplit's interface will change  
> You should have the option to select the game mode you are running  
> Arcade mode will be checked by default, as this has the most speedruns and is the most popular category to play  
> If you select more than one option, it will default to Arcade mode (The top option is their for advice)  
> ![Autsplitter Options](/Images/selecting-auto-splitter-script-after.png)

---

> [!TIP]
> On the same menu where you added the autosplitter before  
> Right click on Livesplit  
> Click on Edit Layout  
> Add Button > `Information` > `ASL Var Viewer` (pictured)  
> ![Adding ASL Var Viewer](/Images/Adding-Var-Viewer.png)  

> [!CAUTION]
> If you don't see this option, you need to make sure the ASL Var Viewer components are inside your Livesplit components folder.  

---

> [!TIP]
> To find in-game variables through Livesplit, you need to double click on the ASL Var Viewer you added in the above step.  

![Accessing ASL Var Variables](/Images/edit-layout-interface.png)

---

> [!WARNING]
> In order to access the variables drop down menu, the game must be running. If the game is not running, it will be greyed out.    

> [!TIP]
> In the value label at the top you can provide text that goes along with variable you wish to select.  
> For Golden Axe, if you wish to see a precise timer (to the thousandths) for your speedrun, select the `RTA_DISPLAY` variable (pictured)  

![Finding RTA Display](/Images/Finding-RTA-Variable-On-LiveSplit[Game-must-be-on].png)

---

If it has been successful, your splits should like similar to the following (depending on the category you are playing!). 

![End View](/Images/livesplit-appearance.png)

> [!INFO] Why bother with the RTA timer?
> RTA = **R**eal **T**ime **A**ttack (Basically, how long it takes you to complete the game from the first input to the final input in one sitting)  
> Just to clarify, *it isn't required*.  
> It allows you to accurately time your speedruns, as the livesplit default splitter is not guaranteed to be accurate (when compared to frame counting) and cannot display times down to the thousandths, which you are asked to provide when submitting a run to the [leaderboard](https://www.speedrun.com/golden_axe).