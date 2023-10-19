# GTA-LibertySanIV
Fixes for GTA: Liberty San IV<br>
*Tested on a Windows 7 Professional (EN) Virtual Machine with 4GB of RAM and 2 CPU cores.*<br>

***GTA_LIBERTY_SAN.iso** obtained from archive.org*<br>
Everything is included in the .iso, so you will not need a copy of San Andreas.

## 1. Installing the game
```
1.1. -Delete your old GTA:SA User Files from your My Documents
     (C:\Users\[YOUR USERNAME]\Documents\GTA San Andreas User Files\)
          (This is so that incompatible settings won't crash the game)
     -You can add custom music on your User Track Player later in this tutorial
1.2. Mount the GTA_LIBERTY_SAN.iso with PowerISO or similiar software
1.3. Run autorun.exe
1.4. -A window pops up with GTA IV's statue of liberty on the background
     -You're presented with 2 buttons that are either in cyrillic or just say "???"
     -Click on the left one to start the install and just hit next on all steps
     -At the end, check "Launch GTA Liberty San IV"
```

## 2. Starting the game for the first time
```
2.1. If the installer didn't start the game automatically,
          go to the game folder (C:\Program Files (X86)\GTA Liberty San IV)
2.2. Open up GTA_SA.exe
2.3. -The GTA IV intro should play, followed by a black screen
     -Left click anywhere on the screen to get to the menu
     -Press "Start game" on the bottom left
     -Press "New game" to create the GTA San Andreas User Files
     -After a brief loading screen the game **will crash**
     -Press "Close program" or shut down GTA_SA.exe from the task manager (CTRL+SHIFT+ESC)
```

## 3. Patching the game
The game keeps crashing because the included script loader (CLEO) is about a decade old.<br>
Download the newest version of CLEO from [https://cleo.li/](https://cleo.li/)<br>
*(Press the button that says Download for GTA SA)*
```
3.1. Unpack CLEO4.zip's contents inside the game folder where GTA_SA.exe is
3.2. **OPTIONAL** If you want to play User Tracks, you can put them in now.
     (C:\Users\[YOUR USERNAME]\Documents\GTA San Andreas User Files\User Tracks\)
```

**--The game should work now!--**<br>
*The default San Andreas experience on modern hardware is shit.<br>
See below for fixes, notes and **a list of which missions won't work***<br>

-**TOGGLE ON the frame limiter.** <br>
Menu -> Options -> Display Setup -> Advanced -> **Frame limiter (ON)**<br>
*Playing without frame limiter may cause small physics glitches,<br>
but also softlock the game when entering or during cutscenes.*

-**Fix the janky ass mouse.**<br>
*You can fix it manually every time you play or* [Download mousefix.asi from GameModding](https://gamemodding.com/en/gta-san-andreas/others/26842-mouse-fix.html)
```
Manual way:
    -Open up task manager (CTRL+SHIFT+ESC)
    -Find GTA_SA.exe and right click it
    -Click "select affinity" and make sure only CPU 0 is ticked on
Mousefix.asi:
    -On the download page wait 20 seconds and press "download archive with files"
    -Open the downloaded .zip and inside you will find folders with mousefix.asi
    -Put mousefix.asi inside the game folder where GTA_SA.exe is
```

## 4. Gameplay Tips
```
-The red car at the start of the game is really funky so if you can't get in just steal another car.

-The police show up on your map as red triangles/squares even if they're not after you.

-The game **might** have a memory leak. It starts at ~300mb of RAM and steadily rises to atleast ~700mb.
    You can play it fine for about an hour after which it can randomly crash.

-If the game crashes just make sure you fully close the GTA_SA.exe (CTRL+SHIFT+ESC) before you run it again so it doesn't re-crash instantly.
```

## 5. Tested Missions
```
-The missions seem to be one-offs but replayable.
-Once you're done with a mission it won't disappear from the map,
but the marker you walked into turns invisible.
-You can replay missions by walking where the marker used to be.
```
### Portland Island (The one on the right) - GTA IV
<details><summary>R (light blue) - The Cousin's Bellic</summary>
     <pre>
-Drive Roman from the harbor to the GTA 3 safehouse
     </pre>
</details>
<details><summary>B (beige) - No.1</summary>
     <pre>
-Take Brucie racing on Staunton Island
     </pre>
</details>
<details><summary>R (red) - Bleed Out</summary>
     <pre>
-Save Roman from the Albanians at the basketball court
     </pre>
</details>
<details><summary>V (pink) - Clean Getaway [DOESN'T WORK]</summary>
     <pre>
-Crashes immediately after loading
     </pre>
</details>

### Staunton Island (The one in the middle) - GTA IV: The Ballad of Gay Tony
<details><summary>F (pink) - Shadow [DOESN'T WORK]</summary>
     <pre>
-Crashes immediately after loading
     </pre>
</details>
<details><summary>G (purple) - N.O.O.S.E. [KINDA WORKS]</summary>
     <pre>
-Get the "APC" tank
-Warning: The guards ath the APC _WILL_ fuck you up.
-No cops cheat (AEZAKMI), health cheat (HESOYAM) and guns (PROFESSIONALSKIT) very recommended.
-I counted about 8/9 of them outside of the gate and another 8 inside.
-They don't seem to move so you can just snipe them from a safe distance (they can wallbang you through the warehouse)
-The first part of the mission works fine but in the second part you need to drive the APC to the airport where the game will crash.
     </pre>
</details>
<details><summary>Pb (gray) - Replays [DOESN'T WORK]</summary>
     <pre>
-One of the few missions with cutscenes and dialog.
-You're told to "Faind the kane" and "Faind the gands" - crashes at the second checkpoint.
     </pre>
</details>
<details><summary>Rb (cyan) - Sky Dive</summary>
     <pre>
-Skydive to a tall building and kill everyone on the top
-All enemies start firing immediately so you should memorize the cheats for health (HESOYAM) and guns (PROFESSIONALSKIT)
-The enemies can't move so just land behind the little shack on the west side of the roof and snipe everyone one by one.
     </pre>
</details>

### Shoreside Vale (The one on the left) - GTA IV: The Lost and Damned
<details><summary>J (gray) - Ruff Rider</summary>
     <pre>
-The mission from GTA:SA where you steal a truck with Cesar
     </pre>
</details>
<details><summary>J (red) - It's War [UNFINISHED MISSION]</summary>
     <pre>
-Drive to a drug deal, escape before they kill you and drive back to Portland Island
-The checkpoint at Portland Island is broken so this mission is uncompletable
     </pre>
</details>

## 6. More Bootlegs
If you're interested in more weird GTA:SA Bootlegs with custom missions,<br>
I recommend checking out these!:<br>
*(They are way easier to get running! Just put them on a clean Steam copy of GTA:SA and install CLEO 4 if it crashes)*<br>

**GTA: Alien City / GTA Anderius** - Takes place in **Space Russia**.<br>
*By far the biggest Total Conversion mod I've seen*<br>
DL: https://www.moddb.com/mods/grand-theft-auto-anderius<br>
English Subtitles: https://www.gtagarage.com/mods/show.php?id=21074<br>

**GTA: Criminal Russia (Nizhny Novgorod Build)** - Takes place in Russia, 2006<br>
*(This version of Criminal Russia has working sounds AND missions)*<br>
DL: https://libertycity.net/files/gta-san-andreas/93315-gta-kriminalnaja-rossija-beta-3.html <br>

**GTA: Ucrainan SSR** - Takes place in the Soviet Ukraine<br>
DL in description: https://www.youtube.com/watch?v=Mkuad9l-rog<br>

**Russian Theft Auto: Ibutsk City Stories** - Another GTA: Russia, set in the soviet times.<br>
DL: https://www.moddb.com/mods/russian-theft-auto<br>
