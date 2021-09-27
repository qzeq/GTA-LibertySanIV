# GTA-LibertySanIV
Fixes for GTA: Liberty San IV <br>
*Tested on a Win7 Professional VM with 4GB of RAM and 4 CPU cores.* <br>

## 1. Installing the game
```
1.1. Mount the GTA_LIBERTY_SAN.iso with PowerISO or similiar software
1.2. Run autorun.exe
1.3. A window pops up with GTA IV's statue of liberty on the background
     You're presented with 2 buttons that are either in cyrillic or just say "???"
     Click on the left one to start the install and just hit next on all steps
1.4. If you played GTA:SA before on this Windows install then delete your
     old GTA San Andreas User Files from your My Documents
     (C:\Users\[YOUR USERNAME]\Documents\GTA San Andreas User Files\)
     This is so that old game data such as the settings won't mess anything up
     (You can add User Track Player stuff later on in this tutorial)
```

## 2. Starting the game for the first time
```
2.1. Go to the game folder (C:\Program Files (X86)\GTA Liberty San IV)
2.2. Open up GTA_SA.exe
2.3. The GTA IV intro should play, followed by a black screen
     Left click anywhere on the screen to get to the menu
     Start a new game to create the GTA San Andreas User Files
     After a brief loading screen the game **will crash**
     Shut down GTA_SA.exe from the task manager (CTRL+SHIFT+ESC)
```

## 3. Patching the game
Download the newest version of CLEO from https://cleo.li
(Press the button that says Download for GTA SA)
```
3.1. Unpack CLEO4.zip's contents inside the same folder where GTA_SA.exe is
3.2. **OPTIONAL** if you want to play User Tracks, you can put them in now
     (C:\Users\[YOUR USERNAME]\Documents\GTA San Andreas User Files\User Tracks\)
```

**The game should work now!** <br>
Vanilla GTA:SA has a fucked up mouse so sometimes you can't control the camera <br>
See below for fixes, notes and **a list of which missions won't work** <br>

You'll can fix the mouse manually every time you play or [Download mousefix.asi from GameModding](https://gamemodding.com/en/gta-san-andreas/others/26842-mouse-fix.html)
```
Manual way:
    Open up task manager (CTRL+SHIFT+ESC)
    Find GTA_SA.exe and right click it
    Click "select affinity" and make sure only CPU 0 is ticked on
Mousefix.asi:
    On the download page wait 20 seconds and press "download archive with files"
    Open the downloaded .zip and inside you will find folders with mousefix.asi
    Put mousefix.asi to the same folder where GTA_SA.exe is
```

## 4. Gameplay Tips
```
The police show up on your map as red squares even if they're not after you.

The game **might** have a RAM memory leak. It starts at ~300mb of ram and steadily rises to atleast ~700mb.
    You can play it fine for about an hour after which it can randomly crash.
```

## 5. Tested Missions
```
The missions seem to be one-offs but replayable.
Once you're done with a mission it won't disappear from the map
but the marker you walked into disappears.
You can replay missions by walking where the marker used to be.
```
### Portland Island (The one on the right) - GTA IV
<details><summary>R (light blue) - The Cousin's Bellic</summary>
  <pre>
    Drive Roman from the harbor to the GTA 3 safehouse
  </pre>
</details>
<details><summary>B (beige) - No.1</summary>
  <pre>
    Take Brucie racing on Staunton Island
  </pre>
</details>
<details><summary>R (red) - Bleed Out</summary>
  <pre>
    Save Roman from the Albanians at the basketball court
  </pre>
</details>
<details><summary>V (pink) - Clean Getaway [DOESN'T WORK]</summary>
  <pre>
    Crashes immediately after loading
  </pre>
</details>

### Staunton Island (The one in the middle) - GTA IV: The Ballad of Gay Tony
<details><summary>F (pink) - Shadow [DOESN'T WORK]</summary>
  <pre>
  Crashes immediately after loading
  </pre>
</details>
<details><summary>G (purple) - N.O.O.S.E. [KINDA WORKS]</summary>
  <pre>
    Get the "APC" tank
    Warning: The guards ath the APC _WILL_ fuck you up.
    No cops cheat (AEZAKMI), health cheat (HESOYAM) and guns (PROFESSIONALSKIT) very recommended.
    I counted about 8/9 of them outside of the gate and another 8 inside.
    They don't seem to move so you can just snipe them from a safe distance (they can wallbang you through the warehouse)
    The first part of the mission works fine but in the second part you need to drive the APC to the airport where the game will crash.
  </pre>
</details>
<details><summary>Pb (gray) - Replays [DOESN'T WORK]</summary>
  <pre>
    One of the few missions with cutscenes and dialog.
    You're told to "Faind the kane" and "Faind the gands" - crashes at the second checkpoint.
  </pre>
</details>
<details><summary>Rb (cyan) - Sky Dive</summary>
  <pre>
  Skydive to a tall building and kill everyone on the top
  All enemies start firing immediately so the health cheat (HESOYAM) and guns (PROFESSIONALSKIT) very recommended.
  The enemies can't move so just land behind the little shack on the west side of the roof and snipe everyone one by one.
  </pre>
</details>

### Shoreside Vale (The one on the left) - GTA IV: The Lost And Damned
<details><summary>J (gray) - Ruff Rider</summary>
  <pre>
  The mission from GTA:SA where you steal a truck with Cesar
  </pre>
</details>
<details><summary>J (red) - It's War [UNFINISHED MISSION]</summary>
  <pre>
  Drive to a drug deal, escape before they kill you and drive back to Portland Island
  (the checkpoint at Portland Island is broken so this mission is uncompletable)
  </pre>
</details>

## 6. More Bootlegs
Thanks for taking the time to read this! Have fun playing GTA: Liberty San IV<br>
If you're more interested in weird Russian GTA:SA Bootlegs with custom missions,<br>
I recommend checking out these!:<br>
<br>
**GTA: Alien City / GTA Anderius** - Takes place in **Space Russia**. By far the biggest Russian Total Conversion mod I've seen <br>
DL: https://www.moddb.com/mods/grand-theft-auto-anderius <br>
English Subtitles: https://www.gtagarage.com/mods/show.php?id=21074 <br>
<br>
**GTA: Criminal Russia (Nizhny Novgorod Build)** - Takes place in Russia, 2006 *(this version has working sounds AND missions)* <br>
DL: https://libertycity.net/files/gta-san-andreas/93315-gta-kriminalnaja-rossija-beta-3.html <br>
<br>
**GTA: Ucrainan SSR** - Takes place in the Soviet Ukraine <br>
DL in description: https://www.youtube.com/watch?v=Mkuad9l-rog <br>
<br>
**Russian Theft Auto: Ibutsk City Stories** - Another GTA: Russia, set in the soviet times. <br>
DL: https://www.moddb.com/mods/russian-theft-auto <br>
*(they are way easier to get running, just unzip them on a clean copy of GTA:SA and install CLEO 4 if it crashes)*
