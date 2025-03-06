---
title: "Wangan Midnight Maximum Tune 5 on PC with TeknoParrot"
date: 2021-03-28
categories:
- Tutorials
keywords:
- tutorials
- emulation
autoThumbnailImage: true
thumbnailImagePosition: "left"
coverImage: //i.imgur.com/kdhh8hA.png
metaAlignment: center
---
After so many years, you can actually play modern arcade titles on PC with TeknoParrot such as Initial D, Blaze Blue, Raiden III and more. In this article, i am going to show how to use TeknoParrot to play one of my favourite arcade titles, Wangan Midnight Maximum Tune 5.
{{< alert info >}}
Latest update: 28th March 2021

Last article: 19th January 2020

This post has been updated to the latest version of TeknoParrot and Wangan Terminal.
{{< /alert >}}
<!--more-->

---
# What is TeknoParrot?

[TeknoParrot](https://teknoparrot.com/) developed by Teknogods (Well-renowned with their Call Of Duty emulators), allows you to run "selected" modern arcade titles on your own PC. Additionally, it has full support for keyboard and mouse, gamepads, steering wheels and joysticks.

While TeknoParrot is a closed-source project, they also released 2 opensource project called "[OpenParrot](https://github.com/teknogods/OpenParrot)" and "[TeknoParrotUI](https://github.com/teknogods/TeknoParrotUI)", open-source version of TeknoParrot and GUI for both project, respectively.

{{< adsense-inarticle >}}

Support Teknogods through [Patreon](https://www.patreon.com/Teknogods) and gain access to the latest version of TeknoParrot weeks earlier than the public.

[Official Website](https://teknoparrot.com/)

[Official Forum](https://forum.teknogods.com/viewforum.php?f=83)

[Wiki](https://wiki.teknoparrot.com/)

---
# How to use TeknoParrot to play WMMT5?
### Requirements:
* Latest [TeknoParrot](https://teknoparrot.com/)
* [WMMT5 Update 5 Jp Clean Dump](https://drive.google.com/file/d/1Ns9bUKdgb-KrUqTs49mVZGqJhXvaVs54/view)[[MEGA mirror](https://ouo.io/bnhnVY)]
* [WMMT5 English Mod v4 - tattoohanz](https://drive.google.com/file/d/1vGL8O9uYwCSQj0eR-eOCpKRgX5sKFQQS/view)
* [7zip](https://www.7-zip.org/) or similar
* [DirectX End-User Runtimes (June 2010)](https://www.microsoft.com/en-au/download/details.aspx?id=8109)
* [Visual C++ Redistributable Runtimes All-in-One](https://m.majorgeeks.com/files/details/visual_c_runtime_installer.html)

* Keyboard/Gamepad/Steering Wheel (If you use DualShock controllers, you need may need [DS4Windows](http://ds4windows.com/))

### Extras:
* [WMMT5 Resolution Patch](https://github.com/Nezarn/WMMT5ResPatcher/releases/)
* [Wangan Terminal Project 2.0](https://mega.nz/#!azBFiIqL!7bmXOI0w5ZbkGmhpWEtujTyocih7yygZkrNM8-sartI)[[Homepage](https://wanganterminalproject.wordpress.com/)]

To begin with, download all the required files under "**Requirements**". Install both **DirectX End-User Runtimes (June 2010)** and **Visual C++ Redistributable Runtimes All-in-One** before starting.

English translation provided by tattoohanz are based on international release of WMMT5. If you like his work, you can donate through his paypal account.

### Step 1:
Extract **TeknoParrot** and your downloaded **WMMT5 Japanese Dump** to your preferred location.
{{< image classes="fancybox" src="https://i.imgur.com/15VG151.png" thumbnail="https://i.imgur.com/15VG151.png" >}}

### Step 2:
Extract **WMMT5 English Mod v4** to WMMT5 installation directory and replace all files (data_jp).

### Step 3:
Open your **TeknoParrot folder** and run **TeknoParrotUi.exe**. **TeknoParrot Updater** may run on start. Please do allow TeknoParrot to update before proceeding. You may need to restart TeknoParrot after updating.
{{< image classes="fancybox" src="https://i.imgur.com/ZLRNr45.png" thumbnail="https://i.imgur.com/ZLRNr45.png" title="Click on TeknoParrotUI.exe" >}}

### Step 4:
Once the update is done, a window will inform you that no games are set up. Click **Yes**, scroll downwards and **add WMMT5**.
{{< image classes="fancybox" src="https://i.imgur.com/9LgTV7k.png" thumbnail="https://i.imgur.com/9LgTV7k.png" title="Yes all the way!" >}}
{{< image classes="fancybox" src="https://i.imgur.com/iy5Zcsg.png" thumbnail="https://i.imgur.com/iy5Zcsg.png" title="Add WMMT5" >}}

### Step 5:
Next, Click on "**Game Settings**". Under Game Executable, select browser to "**wmn5r.exe**". Additionally, tick the necessary settings. You can also setup your in-game with **General-CustomName**. Finally, click **Save Settings**.

* X-Input = Allows use of Xbox 360 controllers. You can try set it to default.

* WhiteScreenFix = May fixed the game problem when you tried to Alt+Tab. 

* Keyboard/button for axis = Allows usage of keyboard.

* Skipmovies = NEVER FUCKING ENABLE THIS. It will break the game.

* TerminalEmulator = Has to be enabled for singleplayer usage.

{{< image classes="fancybox" src="https://i.imgur.com/jHdiNtf.png" thumbnail="https://i.imgur.com/jHdiNtf.png" >}}

### Step 6:
After that, click on **Controller Setup** to setup your bindings. Don't forget to click **save settings**.
{{< image classes="fancybox" src="https://i.imgur.com/rkthclx.png" thumbnail="https://i.imgur.com/rkthclx.png" title="Above are my bindings for WMMT5 with Xbox 360 controller" >}}

### Step 7:
Finally, you can start the game!
{{< image classes="fancybox" src="https://i.imgur.com/SQAXrAG.jpg" thumbnail="https://i.imgur.com/SQAXrAG.jpg" title="Mainmenu Eng translated!" >}}
{{< image classes="fancybox" src="https://i.imgur.com/cDRo6T8.jpg" thumbnail="https://i.imgur.com/cDRo6T8.jpg" title="Even the stories are translated" >}}

---
# Extras:
### 1. How to improve the game graphics?
If you are using an Nvidia graphics card, follow the settings below. Else, lookup similar guides for AMD.

1. Right click anywhere in your desktop and select **NVIDIA Control Panel** 
{{< image classes="fancybox" src="https://i.imgur.com/OdbKJTw.png" thumbnail="https://i.imgur.com/OdbKJTw.png" >}}
 
2. Go to **Program Settings**, click Add and choose **wmn5r.exe**
{{< image classes="fancybox" src="https://i.imgur.com/GyB045j.png" thumbnail="https://i.imgur.com/GyB045j.png" >}}
3. Be sure to choose "High-performance NVIDIA processor" as your preferred graphics processor.
{{< image classes="fancybox" src="https://i.imgur.com/t70rJBz.png" thumbnail="https://i.imgur.com/t70rJBz.png" >}} 
4. Under Specify the settings for this program, select the following: 

> **Anisotropic filtering** : 16x

> **Antialiasing - FXAA** : On

> **Antialiasing - Mode** : Enhance the application setting

> **Antialiasing - Setting** : 32x CSAA

> **Texture filtering - Quality** : High Quality

### 2. How to use Wangan Terminal Project 2.0?
Online features not longer work. Enabling offline mode is required.

1. Extract the contents of **Wangan Terminal Project 2.0** to your preferred location.
2. Follow this [video tutorial](https://streamable.com/2av249) to setup offline mode.
3. Launch **Wangan Terminal Project 2.0** and wait for the update to complete as the files are huge.
{{< image classes="fancybox" src="https://i.imgur.com/va8sqaD.png" thumbnail="https://i.imgur.com/va8sqaD.png" >}}
4. Setup **Game Path**
{{< image classes="fancybox" src="https://i.imgur.com/1umJan2.png" thumbnail="https://i.imgur.com/1umJan2.png" >}}
5. Once done, you can do anything you like!
{{< image classes="fancybox" src="https://i.imgur.com/uWp7cf3.png" thumbnail="https://i.imgur.com/uWp7cf3.png" >}}

If the Terminal crashes after selecting your WMMT5 directory or on start, delete all the videos inside "Video" folder.

[Dress-up Parts](https://soarsmedia.blogspot.com)

### 3. How to play WMMT5 Multiplayer?
[TeknoGods WMMT5 LAN networking tutorial](https://teknogods.github.io/compatibility/WMMT5.htm)
{{< image classes="fancybox" src="https://i.imgur.com/YORKfKs.png" thumbnail="https://i.imgur.com/YORKfKs.png" title="Click to zoom" >}}

### 4. Game is lagging as fuck.
Try reducing game resolution with WMMT5 resolution patcher.

1. Download **WMMT 5 Resolution Patch** and extract it into your **WMMT5 dump**.
{{< image classes="fancybox" src="https://i.imgur.com/FWO9p2M.png" thumbnail="https://i.imgur.com/FWO9p2M.png" title="Headover to github and download" >}}
{{< image classes="fancybox" src="https://i.imgur.com/YTfOyQl.png" thumbnail="https://i.imgur.com/YTfOyQl.png" title="Extract it to your dump" >}}

2. Run **WMMT 5 Resolution Patcher.exe** and browse into your WMMT5 dump to select **wmn5r.exe**. A window will popup which allows you to lower your **screen resolution** (Mine is 2560x1080). Once done, click **apply**.
{{< image classes="fancybox" src="https://i.imgur.com/ObHnrXi.png" thumbnail="https://i.imgur.com/ObHnrXi.png" title="Easy peezy!" >}}
{{< image classes="fancybox" src="https://i.imgur.com/Lrny22O.png" thumbnail="https://i.imgur.com/Lrny22O.png" title="Select your monitor resolution" >}}

---
# WMMT5 Frequently asked questions (FAQs)

### 1. Help, my game is running slow despite having a good Nvidia graphic card.
This is possibly due to your system using Integrated graphics by default. To fix this, do the following: 

1. Right click anywhere in your desktop and select **NVIDIA Control Panel** 
{{< image classes="fancybox" src="https://i.imgur.com/OdbKJTw.png" thumbnail="https://i.imgur.com/OdbKJTw.png" >}}
 
2. Go to **Program Settings**, click Add and choose **wmn5r.exe**
{{< image classes="fancybox" src="https://i.imgur.com/GyB045j.png" thumbnail="https://i.imgur.com/GyB045j.png" >}}
3. Be sure to choose "High-performance NVIDIA processor" as your preferred graphics processor.
{{< image classes="fancybox" src="https://i.imgur.com/t70rJBz.png" thumbnail="https://i.imgur.com/t70rJBz.png" >}} 

### 2. How do i save my car if there is no Banapassport?
At the end of a race, there will be a selection to either continue the game or not. Selecting "No" will save your car progress. 

Cars are saved inside your WMMT5 dump directory at "OpenParrot_Cars" based on their CarIDs. Do use Wangan Terminal Project 2.0 for dress-up.

### 3. Why does the story start from the last progress?
Despite using other cars, the game progression will always be the last completed mission. This is due to the Story mode being saved in a single file, located inside WMMT5 dump directory as "openprogress.sav".

To restart Story mode, delete "openprogress.sav".

### 4. Where is Ghost mode?
Currently, there is no Ghost mode because a banapassport emulation or similar is required. However, progress has been made to enable Ghost mode. For further progress, do check out [WMMT5 Online Ghost Project](http://derole.co.uk/wmmt5ghostbattle/).

### 4. I still need help.
Do join [Wangan Midnight Emulation Discord Server](https://discord.gg/r3nbd4x) for support.

---
# Credits
I give my sincere thanks to:

* [Teknogods](https://teknogods.com) for developing TeknoParrot

* [tattohanz](http://www.emuline.org/profile/6436-tattoohanz/) for English Patch

* [Derole123](https://wanganterminalproject.wordpress.com/) for Wangan Terminal Project

* [WME Discord](https://discord.gg/r3nbd4x) for tutorial update

{{< adsense-inarticle >}}
