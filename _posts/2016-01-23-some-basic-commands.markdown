---
layout: post
title:  "Some basic commands"
date:   2016-01-23 14:00:35 +0000
categories: minecraft setup
---

## Some basic commands
Remember Minecraft is a three dimentional world. I will write a post about what this means in more detail. But when you are starting out you are at position zero (0, 0, 0), and we put blocks in the world starting from your position.

Later on you can change this starting position but for now we do it from your players position.

We get your position and store it in a variable by using the following command:

    playerPosition = mc.player.getPos()

This uses the **mc** variable that we have set in the "first python script" example.

As we work in three dimentions, we can now get the x, y and z axis from this **playerPosition**.

    playerPosition.x #players x-axis position
    playerPosition.y #players y-axis position
    playerPosition.z #players z-axis position
    
Now if we want to put or change a block in the world we select it by using the three dimentional cordinates, then set the block type. In Minecraft there are loads of block types, lets use one of the most popular ones the diamond block. In our python code we call that:

    DIAMOND_ORE
    
The Mod has set these blocks to be certain names already. If you open the file **/mcpi/block.py** you can see all of the types listed, thats in the **mcpi** folder which should be in the code editor window.

Back in your first script try adding the following:

    playerPosition = mc.player.getPos()
    mc.setBlock(playerPos.x, playerPos.y-1, playerPos.z, DIAMOND_ORE)
    
The new command here is the **setBlock** command. This places 1 block in the world. Before I said the **player.getPost()** function gets a set of cordinates based on your position.

In the code I want you to try above we are using the x, y and z axis of your players position.

Try add the code and when you run the script you should see a diamond block appear below your player.

So that adds one block at a time, if you do something like the following. You can add a range of blocks.
    
    mc.setBlocks(playerPos.x, playerPos.y-1, playerPos.z, playerPos.x+10, playerPos.y-1, playerPos.z+10, DIAMOND_ORE)
    
Now if you run this script in Minecraft you should draw a floor of diamond blocks.

For anyone wanting to find out loads of commands checkout this [page](http://www.stuffaboutcode.com/p/minecraft-api-reference.html) for a reference.
