![img](https://s11.gifyu.com/images/Cuty-od-Dreams-Logo-YellowUP.png)
![img](https://s12.gifyu.com/images/Su3dO.png)

# Guides

- [First Launch With The Collection](#first-launch-with-the-collection)
- [Gameplay](#gameplay)
- [Learning to Troubleshoot](#learning-to-troubleshoot)
- [Troubleshooting](#troubleshooting)
- [Backups](#backups)
- [Other Support](#other-support)
- [Other Guides](#other-guides)

![](https://s12.gifyu.com/images/Cyan-Rule.png)


## First Launch With The Collection

<details>
<summary>First Launch with the Collection</summary>

![img](https://i.imgur.com/wAJUpeU.png)

1) To use CET (Cyber Engine Tweaks) use F11 on your keyboard to bring up the overlay here you will have many overlays that you can use to adjust the mods from the collection and configure them how you like including Cheats, AMM Appearance menu,Vehicle camera and many more.

2) I have added a key bind config file for a few of the mods this is just to get you started you can change it as you like. You will find the key bind list in your main game directory and HERE>⁠Keybinds .

3) On the main menu go to the graphics tab and you will find "texture quality"  Set this to "HIGH".

4) Once in game hold SHIFT and press U to customize the hud settings to suit you. To go to the next widget press the LEFT and RIGHT arrow keys.

6) IF YOU ARE A E3 USER FOLLOW THE PICS BELOW

![img](https://i.imgur.com/wAJUpeU.png)

</details>




## Gameplay


<details>
<summary>Game Difficulty</summary>

![img](https://i.imgur.com/wAJUpeU.png)

You can change the difficulty to suit your style.

1) From the main menu select Mods.

2) Select "RMK MODS"

Use these menus in game to make it Easier or Harder based on your play style.

![img](https://s11.gifyu.com/images/Sciel.png)

If you want to learn more about how these mods work check out the mod page on Nexus [HERE](https://www.nexusmods.com/cyberpunk2077/mods/1712)

![img](https://i.imgur.com/wAJUpeU.png)

</details>


<details>
<summary>Changing the CET keybind</summary>

![img](https://i.imgur.com/wAJUpeU.png)

To change the (CET) Cyber Engine Tweaks Overlay.

Delete bindings.json located in 

```
bin\x64\plugins\cyber_engine_tweaks 
```

and then launch Cyberpunk 2077 to set a new key bind.


**Note** This will also delete any other key bind configuration you have chosen for your mods.

![img](https://i.imgur.com/wAJUpeU.png)

</details>


<details>
<summary>How to use Idle Anywhere</summary>

![img](https://i.imgur.com/wAJUpeU.png)

**1**) Visit V's starting apartment in H10. You only need to do this once to 'activate' the mod.

**2**) Press the Sprint input while the following is true:

- Stood still (not sat, or crouched)
- Not in a moving elevator (probably can't be vehicle surf either)
- Out of combat
- Have empty hands
- Not looking directly up or down
- Not scanning (zooming is okay)

**3**) Press Sprint again to manually hide it.

*NOTE*
The menu will also not work when controlling surveilance systems, in Brain Dances, and shouldn't work in Johnny's memories either.
If you do have/use the option while in conversation with NPCs just be aware that it can sometimes cause NPCs to sound distant/quiet during the animation(s)

![img](https://i.imgur.com/wAJUpeU.png)

</details>


<details>
<summary>Refreshing Night City Interactions</summary>

![img](https://i.imgur.com/wAJUpeU.png)

**1**) Travel to V's first/main apartment in H10
**2**) Find and use the **REBOOT NCI** interaction in the stash room
**3**) Leave the apartment and then walk back in

This resets the mod **Night City Interactions**

![img](https://i.imgur.com/wAJUpeU.png)

</details>





## Learning to Troubleshoot

<details>
<summary>Cyberpunk Mod Troubleshooting</summary>

![img](https://i.imgur.com/wAJUpeU.png)

You can read the wiki [HERE](https://wiki.redmodding.org/cyberpunk-2077-modding/help/users-troubleshooting)

![img](https://i.imgur.com/wAJUpeU.png)

</details>

<details>
<summary>Finding log files</summary>

![img](https://i.imgur.com/wAJUpeU.png)

1) In your main Cyberpunk 2077 game directory you will see a bat file name **FindErrorsBat**

```
GOG>     Drive Letter:\Games\Cyberpunk 2077
Steam>  Drive Letter:\Games\Steam\steamapps\common\Cyberpunk 2077
Epic> Drive Letter:\Epic Games\Cyberpunk 2077
```

2) Double click the file.

3) The script will have created a folder _LOGS in your Cyberpunk directory, which contains a file listing all the errors for you.


![img](https://i.imgur.com/wAJUpeU.png)

</details>


<details>
<summary>Finding and reading log files</summary>

![img](https://i.imgur.com/wAJUpeU.png)

You can read the wiki [HERE](https://wiki.redmodding.org/cyberpunk-2077-modding/for-mod-users/user-guide-troubleshooting/finding-and-reading-log-files)

![img](https://i.imgur.com/wAJUpeU.png)

</details>




## Troubleshooting

<details>
<summary>Cyberclean</summary>

![img](https://i.imgur.com/wAJUpeU.png)

Always double-check Vortex to make sure it uninstalled/installed something properly during an update. If you are having any issues with crashing or mods not loading you can do the following.

MANUAL
1) Purge mods in Vortex

![](https://s11.gifyu.com/images/Purge-Deploiy.jpg)

2) Go to where cyberpunk2077 is installed and delete these 4 folders /**bin** / **engine** / **r6** / **red4ext**

![](https://s12.gifyu.com/images/Cyberclean.jpg)

3) Go to the following location and delete the **"mod"** folder. If you don't see it that's fine.

```
Steam> Drive Letter:\Games\Steam\steamapps\common\Cyberpunk 2077\archive\pc\mod
GOG>   Drive Letter:\Games\Cyberpunk 2077\archive\pc\mod
Epic>  Drive Letter:\Epic Games\Cyberpunk 2077\archive\pc\mod  
```

4) Verify game files inside your launcher.

5) Deploy mods in Vortex.

6) Launch the game and see if the problem is resolved. 

AUTO
1) Purge mods in Vortex

![](https://s11.gifyu.com/images/Purge-Deploiy.jpg)

2) Place the (Cyberclean.bat) file in the main cyberpunk directory you can find it here> https://www.nexusmods.com/cyberpunk2077/mods/8595

```
Steam> Drive Letter:\Games\Steam\steamapps\common\Cyberpunk 2077\archive\pc\mod
GOG>   Drive Letter:\Games\Cyberpunk 2077\archive\pc\mod
Epic>  Drive Letter:\Epic Games\Cyberpunk 2077\archive\pc\mod  
```

3) Double click that bat file.

4) Verify game files inside your launcher.

5) Deploy mods in Vortex.

6) Launch the game and see if the problem is resolved.


![img](https://i.imgur.com/wAJUpeU.png)

</details>


<details>
<summary>Checking for old mods or mods that arnt part of the collection</summary>

![img](https://i.imgur.com/wAJUpeU.png)

We can filter mods in Vortex from a variety of options we are going to use the collections filter this is helpfull to find old mods or mods that are not part of the collection.

1) Open Vortex and on the mods tab in the right hand corner select the settings cog. Now select collection.
 
2) Now you can filter "none" and see the mods that arnt in the collection.

![](https://s11.gifyu.com/images/Su3mn.png)

![img](https://i.imgur.com/wAJUpeU.png)

</details>

## Backups

<details>
<summary>Make a backup save</summary>

![img](https://i.imgur.com/wAJUpeU.png)

Mods for Cyberpunk 2077 are pretty reliable but it's always good to make a backup of your saved file. 

Save files can be found here 

```
C:\Users\Your username\Saved Games\CD Projekt Red\Cyberpunk 2077
```

just copy the contents of this file and place it somewhere on your pc.

![img](https://i.imgur.com/wAJUpeU.png)

</details>

<details>
<summary>Modded Game Backup</summary>

![img](https://i.imgur.com/wAJUpeU.png)

Move game folder before the DLC and any other upgrade.


1) open vortex/mods and purge first so you don't mess up with the files

2) move the game foder where you want it (on the same drive)

3) go to games on vortex, press on the 3 dots on cyberpunk 2077 and then manually set location. find the folder you just moved

4) deploy mods and then go to tools and press on the 3 dots on the side of each tool and press on edit. Then change them to the folder u moved

If you want to upgrade your cyberpunk modded folder. just update the game with steam/gog and copy the steam/gog cyberpunk 2077 game folder to your cyberpunk modded folder. PURGE MODS IN VORTEX FIRST

![img](https://i.imgur.com/wAJUpeU.png)

</details>




## Other Support


<details>
<summary>Live Voice chat support and Remote connection</summary>

![img](https://i.imgur.com/wAJUpeU.png)

I can help you if you are stuck with LIVE Voice chat support and screenshare in the ⁠🔧︱Live VC Support channel in discord

If you are really stuck i can connect to your Pc via a remote connection all you have to do is click the download link it will take you to a software page to download Teamviewer with this tool i can control your pc remotely (while you watch) with a one time use code and password. You can uninstall the program after so you can have peace of mind.

To download Teamviewer click [HERE](https://www.teamviewer.com/en-us/download/windows/?utm_source=google&utm_medium=cpc&utm_campaign=au|b|pr|22|jun|tv-core-download-sn|free|t0|0&utm_content=Download&utm_term=teamviewer%20download&gad=1&gclid=CjwKCAjw9pGjBhB-EiwAa5jl3JtSMlwskHVNVTH2fzvXvtj6wTBD_uhieVL3zYhh38ZYQBQscEv3KRoCZGsQAvD_BwE)
🔧︱Live VC Support in discord

![img](https://i.imgur.com/wAJUpeU.png)

</details>

<details>
<summary>PC Optimizations</summary>

![img](https://i.imgur.com/wAJUpeU.png)

I've been building Pcs for a few years now and have picked up a few tips and tricks along the way. You can also check out my builds on our Discord.

I can connect to your Pc via a remote connection [Team Viewer]() and optimize your Pc for gaming. 

I use a few tools and methods which I will explain here. These tools/programs are lightweight and will not take up many resources in the background. These tools are used widely by the Pc community and are well known.

All links to these tools will be listed below so you can check them out for yourself.

All of this I offer free of charge. The only thing I ask is for you to **Endorse** and support our collections. It really means a lot to us.


### MSI afterburner

This is an overclocking tool but it does much more. With this tool, I can set the following.

1) Custom fan curve this will help with **GPU** temps.

2) Unlock the voltage control on the **GPU** this helps maintain higher clock speeds for the **GPU**.



### RTSS Riva Statistics Tuner

This is a hardware monitoring tool that works alongside **MSI Afterburner**.

1) This allows monitoring of all **GPU** parameters including an **FPS** counter, Temp readings, **FPS** cap and much much more



### ISLC Intelligent Standby List Cleaner

This help to clear out the standby list in Windows in turn freeing up Memory **RAM** the benefits of this tool are fewer stutters in game and maintaining a steady fps.



### Quick CPU

Quick CPU is a program that was designed to fine-tune and monitor important CPU and System parameters such as **CPU** Temperature (Package and Core Temp), **CPU** Performance, Power, Voltage, Current, Core Parking, Frequency Scaling, System Memory, Turbo Boost, C-States, Speed Shift FIVR Control as well as making other adjustments.


### CPU Z & GPU z

These will allow you to identify the GPU and CPU.


### GEEK Uninstaller

This is a great tool for uninstalling programs and removing any traces they leave behind.


### WINDOWS OPTIMIZATION

As well as the tools i can install and configure there are also some optimizations I can perform inside of Windows itself.

These include.

1) Nvidia control panel optimizations

2) Bios optimizations.

3) Power management optimizations.

4) Game-specific optimizations.



### OVERCLOCKING OF THE GPU

I can overclock and stress test your **GPU**.



### As well as all of the above I can.

1) Clear out old unused Windows files taking up space on your System.

2) Run system scans to ensure everything is running as it should be and repair errors.

[MSI afterburner](https://www.msi.com/Landing/afterburner/graphics-cards)

[RTSS Riva Statistics Tuner](https://www.guru3d.com/files-details/rtss-rivatuner-statistics-server-download.html)

[ISLC Intelligent Standby List Cleaner](https://www.wagnardsoft.com/forums/viewtopic.php?t=1256)

[Quick CPU](https://coderbag.com/product/quickcpu)

[CPU Z](https://www.cpuid.com/softwares/cpu-z.html)

[GPU Z](https://www.techpowerup.com/gpuz/)

[GEEK Uninstaller](https://geekuninstaller.com/)

![img](https://i.imgur.com/wAJUpeU.png)

</details>

## Other Guides


<details>
<summary>System Specs</summary>

![img](https://i.imgur.com/wAJUpeU.png)

System specs for the base collection & (Lite) Version

- VRAM> 8GB
- GPU>(see below)
- 1080p> RTX 3060 or RX 6700 XT
- 1440p> RTX 3080 or RX 6800 XT
- RAM> 16GB
- CPU> R5 3600 or i5 9600K
- STORAGE> 12.5GB
- STORAGE TYPE> SSD


System specs for the  4k Graphics Pack

- VRAM> 16GB
- GPU>(see below)
- 1080p> RTX 3080 or RX 6800 XT
- 1440p> RTX 3090 or RX 6900 XT
- RAM> 32GB
- CPU> R5 5600 or i5-12400F
- STORAGE> 28GB
- STORAGE TYPE> SSD

Weak  Hardware

Some crashes are caused by weak hardware. The collection uses alot of RAM this can lead to crashes if the user only has 16gb of RAM installed and they are runnning alot of background programs.

SSD vs HDD

Cyberpunk 2077 needs to be installed on a SSD if its not the following can occur.

- Texture Pop In
- Missing textures
- Texture Loading
- Very Long load times
- Slow Vortex Deployment
- Crashes

![img](https://i.imgur.com/wAJUpeU.png)

</details>


<details>
<summary>Running Cyberpunk 2077 as admin</summary>

![img](https://i.imgur.com/wAJUpeU.png)

1) Go to the following location and find the "cyberpunk2077.exe"

```
Cyberpunk 2077\bin\x64
```

2) Right click the exe and go to "properties"

3) On the compatibility tab check the box for "run this program as administrator" and select "apply" and "ok"

![img](https://s12.gifyu.com/images/SQNWC.jpg)


![img](https://i.imgur.com/wAJUpeU.png)

</details>

<details>
<summary>Random Crashes</summary>

![img](https://i.imgur.com/wAJUpeU.png)

The game may crash here or there its just something we cyberpunks have to deal with. 

But if you are getting constant crashes then there is a issue let us know so we can assist you.

You may find that the game will crash when doing the following. This is due to the game compiling the scripts for all the mods.

1) After the first install of the collection.

2) After a "cyberclean"

3) After a collection update.


![img](https://i.imgur.com/wAJUpeU.png)

</details>

<details>
<summary>Game Patch Versions</summary>

![img](https://i.imgur.com/wAJUpeU.png)

This guide was made by Jack Humbert 

Find your File Version:

1) Locate Cyberpunk2077.exe in your game directory at 

```
bin/x64/Cyberpunk2077.exe
```

2) Right-click and select Properties

3) Select the Details tab

4) Look for File version in the table - it should match one of the numbers below

![img](https://s11.gifyu.com/images/ScieU.png)

![img](https://i.imgur.com/wAJUpeU.png)

</details>

<details>
<summary>How to Downgrade Steam Games</summary>

![img](https://i.imgur.com/wAJUpeU.png)

1) Enable Steam Console
The first thing we'll do is enable the Steam Console. You'll want to have Steam running before proceeding. If you're downloading an older version of a paid game, you'll also want to be logged into an account that owns that game.
In order to enable the Steam Console, follow these steps.

First, hit the Win + R buttons to bring up the Run program. Type in the following string of text and hit enter:
steam://open/console
Steam will automatically open and display a new screen, titled Steam Console. Keep Steam open for now, and let's move over to your web browser for the next step.

2) Find App, Depot, and Manifest ID for Your Game**
The next part of this guide is going to require using SteamDB, or the Steam Database. Head over to the main page of SteamDB and search for the game you're looking to downgrade. We'll use Half-Life 2 as an example.
The first bit of information you'll want to grab is the App ID. Note this down somewhere, then click on the Depots link, found on the side of the page.

We want to note down the ID Number listed against the depot we're after.

What depot are we after? The depot for the base game. Two things that may indicate that the depot is for the base game are the size of the depot, as well as the name. If it's the largest depot, and it's named something like 'Base,' then in all likelihood that's the one we're after.

In our case, that would be Half-Life 2 Base. We should now have an App ID and a Depot ID. For Half-Life 2, we have 220 and 221 so far. Now, click the Depot ID itself. It will take you to yet another page.
Click Manifests on the side. This page is showing all the different updates, as well as how long ago those updates were released. You may need to sign in to SteamDB to see updates older than a year.
This page has the last piece of information we're after. Find the update you're after and note down the Manifest ID. Now we have everything we need.

In our case, that is the App ID 220, the Depot ID 221, and the Manifest ID we'll use is 2285219600326880043.

3) Download Manifest Using Steam Console**
Head back into Steam. The next part is easy. This is where we actually download the older version.

With the Steam Console open, input the following command.

download_depot <AppID> <Depot ID> <Manifest ID>
Again, our example would look something like this.

download_depot 220 221 2285219600326880043
After you hit enter, it may seem like nothing is happening. Steam won't always notify you of the download.

Don't worry, if you've entered the command correctly, Steam will be downloading it silently. You can confirm by checking any network usage. If you're worried about going over your data limit, make sure you know how to limit bandwidth and data usage in Windows.

Eventually, the Steam Console will display a message indicating that the download is done.

As long as you get the message Depot download complete, don't be too concerned with any error messages generated at this point.

Take note of where the download has been placed. There's another step or two involved to get your downgraded game running on Steam.

4) Replace Game Files With Downgraded Files**

Navigate to where Steam has downloaded your files. Keep this window open.

Next, open up the installation directory for your game. This can be done easily by following these steps:

Right-click the game on Steam.
Mouse over Manage.
Click Browse Local Files.
The two directories should look very similar.

From here, it's a matter of replacing the original game files with your newly downloaded version. Either move your original game files to another location for a backup, or outright delete the original files. Anything you delete can be downloaded again later.

Next, paste the files you downloaded from the Steam Console into the installation directory.

You've now downgraded the game files. Next time you launch the game through Steam, it will launch this original version.

![img](https://i.imgur.com/wAJUpeU.png)

</details>


<details>
<summary>Downgrading / Preventing auto-updates</summary>

![img](https://s11.gifyu.com/images/Sgd38.jpg)

Go to the[Cyberpunk Modding WIKI](https://wiki.redmodding.org/cyberpunk-2077-modding/for-mod-users/users-modding-cyberpunk-2077/users-downgrading-preventing-auto-updates) and follow the relevent version of your game.

![img](https://s11.gifyu.com/images/Sgd38.jpg)

</details>

![](https://s12.gifyu.com/images/SuG0u.png)