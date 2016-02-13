---
layout: post
title:  "Setup steps for Windows"
date:   2016-01-23 11:10:35 +0000
categories: minecraft setup
---

To start setting things up for your windows machine you need to have already installed Minecraft. This is a very important step as at our location in the library you will not be able do this due the the firewall restrictions there.

The source/inspiration for these instructions can be found [here](http://www.instructables.com/id/Python-coding-for-Minecraft/?ALLSTEPS) copied and updated for the coding clubs needs.

We need to download and install the following, check below for more details:

	1, Minecraft
	2, Python
	3, Code editor
	4, Minecraft Forge
	5, Download demo scripts and the Mods required
	6, Check everything is setup
    
    
### 1, Install Minecraft
As mentioned above, this should be completed prior to attending a session. You can do this from the [Minecraft Website](https://minecraft.net/).


### 2, Install Python
To install Python goto the [website](https://www.python.org/downloads/) and click on the "Download Python 2.7.11". The installer should be the same as any other that you have seen before, click through the steps and once finished you are done.


### 3, Install a code editor
We are installing a code editor as this has advantages over a plain text editor or a tool like microsoft word. The main one being your can see the colour of the code, so you know its correct and you can open multiple files at once. There are many to choose from but we recommend one of the following:

[Brackets](http://brackets.io/)

[Atom](https://atom.io/)

[Sublime Text](http://www.sublimetext.com/)

All should be easy to setup, just download the installer for your platform and follow the instructions.


### 4, Install Minecraft Forge
To install Minecraft Forge download [here](/files/forge-1.8.9-11.15.1.1722-installer-win) or goto the website [here](http://files.minecraftforge.net/). We are downloading the files for 1.8 version of Minecraft. This is not the latest version but its the one that works with our python code.

The installer should appear, select "install client". Once it has finished, run minecraft and where the profile box appears you should now be able to select "forge" as an option.


### 5, Download demo scripts and the Mod
Now we need to download and install the Mod that we will use and the demo scripts from [here](/files/python2-scripts.zip) and the Mod [here](/files/RaspberryJamMod.jar) or goto the original website [here](https://github.com/arpruss/raspberryjammod/releases). We want to download the **"python2-scripts.zip"** and the **"RaspberryJam-Mod-0.08.jar"**, the links to download can be found under the title **"0.52"** the latest version of the Mod.

We need to add a mods folder, do that by using the start menu and clicking run. Type the following in the box:

	%appdata%\.minecraft

Now create folder called **"mods"**.

Now put the **"RaspberryJam-Mod-0.08.jar"** in the mods folder. Now unzip the **"python2-scripts.zip"** and you will see a folder called **"mcpipy"** copy this into the **"./minecraft"** folder not the **"mods"** folder.


### 6, Check setup
Now to test everything, run Minecraft if you have not already. Create a new world and then save and exit before closing.

Now this time when you run Minecraft select **"forge"** under the profile and click play.

Load or create a new world. Press the **"/"** forward slash key and this brings up the chat console. Type the following:

	python donut

And if everything is setup a very large glass donut should appear above your head.

To run any python scripts remember type **"python"** first. Now you are ready to go.


