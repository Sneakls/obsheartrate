# obsheartrate
Webbased Heart Rate Overlays for OBS etc

I recently got a heartrate monitor (MOOFIT HR8 on Amazon) to use it on me and my wifes streams (twitch.tv/Sneakls and twitch.tv/AnimeQueen87).

So I've created a couple of overlays for use in OBS (Browser Source) and just wish to share them, enjoy!


---------------------------------------------------------------------------------------------------------------

To set this up, the only way that I know for now is to use the following software:

**XAMPP** (Local webserver with Apache & PHP) - https://sourceforge.net/projects/xampp/

**HeartRate** by jlennox (This software reads the heartrate) - https://github.com/jlennox/HeartRate



---------------------------------------------------------------------------------------------------------------
---------------------------------------------------------------------------------------------------------------
---------------------------------------------------------------------------------------------------------------

**XAMPP**

After installing (to C:\xampp as suggested by the installer, preferably) and starting the software you need to start the software to get into the control panel and **Start** the **Apache** module.

----

**HeartRate**

Start the software then either rightclick the icon in the system tray or inside the programs window itself, select "Set heart rate file..."

Set it to save as **heartrate.txt** in **C:\xampp\htdocs**


---------------------------------------------------------------------------------------------------------------
---------------------------------------------------------------------------------------------------------------
---------------------------------------------------------------------------------------------------------------

Download gamespecific zipfile and extract the contents to **C:\xampp\htdocs**

In OBS add a new Browser Source

As URL enter: http://127.0.0.1/_SPECIFIC_GAME_OVERLAY_.php (for example http://127.0.0.1/phasmophobia-insanity.php)

Width & Height: 1200 (use ALT+Left Click to crop the browser source as you wish later)

**CLEAR "Custom CSS"**

Check "**Shutdown source when not visible**" and "**Refresh browser when scene becomes active**"

Click **OK**


**NOTE:** You will need to do this for each of the different overlays you want.

---------------------------------------------------------------------------------------------------------------
---------------------------------------------------------------------------------------------------------------
---------------------------------------------------------------------------------------------------------------

More will come! :)

For any donations > https://ko-fi.com/sneakls
