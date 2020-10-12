# SampSharp-Liberty-City-controller
Well known samp liberty city filterscript converted from pawn to SampSharp controller.

# PLEASE READ
I did convert  Liberty City filterscript for SampSharp but there is one thing you have to do.
Because I don't know how you stream your objects on your server, you'll have to change that 1 thing in your code.
You will find a list and 2 functions named `CreateLC2SAObject` and `AddLC2SASimpleObject`.
As you can see, I call there `new DynamicObject` function which is for my own streamer. Simple replace this function to your own, maybe you use popular Incognito's streamer, you can replace this function to your streamer one and it should work, remember to remove this at line 22 then: `List<GlobalObject> list = new List<GlobalObject>();` 

# What does it do?
Controller in SampSharp in short means that you can include this file in your project solution and this .cs file will be executed without doing anything.
This file was filterscript that added all liberty city objects to your gamemode.

# Requirements:
1. Liberty City map in your models folder
2. SampSharp plugin (more here: sampsharp.net)
3. SA-MP 0.3-DL

# Installation instruction:
Include `LibertyCityController.cs` in your project. Done!
