---
layout: post
title:  "Coding Your first Python script"
date:   2016-01-23 14:00:35 +0000
categories: minecraft setup
---

## Coding your first Python script
To write your first script open your code editor of choice. Then the best thing to do is to work in the scripts folder you created before. The code editor will have an option like **"file -> open folder"** use that and browse to the Minecraft folder.

This will be different depending on which operating system you have. To find the folder again do the following:

#### On Windows:
Click on the start menu and clicking run. Type the following in the box:

	%appdata%\.minecraft\mcpipy

#### On OSX (Apple):
Opening finder, use the go command, select **"go to folder"** and type the following:

    ~/Library/Application Support/minecraft/mcpipy
    
The folder we are looking for should appear. Make a note of that folder path and go back to the code editor and use the **"file -> open folder"** option to browse to it.

Now the code editor should have a section on screen where the folder is and you can probably see lots of files. Add a new file and call it something you can remember maybe **myFirstScript.py** and make sure it is saved in the mcpipy folder. It should also appear in the code editor with the rest of the files.

## First lines of code.
All the coding we will be doing is in Python. The first line of code should always be:

    from mc import *
    
This is the python way of loading all the functions and libraries we need to run.

The next line should be the following:

    mc = Minecraft()
    
This sets a local variable called **"mc"** and connects to Minecraft for us.

The last line should be:

    mc.postToChat("Hello world!")
    
So we call our variable **"mc"** which connects to Minecraft. Then it uses the **postToChat** function which puts the string **"Hello world!"** into the Minecraft chat.

You can also set the string as a variable by doing the following:

    chatString = "Hello world!"
    
Then change the **postToChat** function to be the following:

    mc.postToChat(chatString)
    
## Running the code
Now start Minecraft then remember to select **forge** as the user profile. Once you have loaded a world try typing the following in the Minecraft console. You get to the chat console by pressing the **"/"** forward slash button.

    python myFirstScript.py
    
You should see **"Hello world!"** appear in on screen.


