---
title: Dextro is coming to DevUE
tags: [Dextro, DevUE]
style: border
color: info
description: Dextro is coming to DevUE to support you! Read more...
---

# Dextro is coming to DevUE
by DevGames
March 3, 2023



Dextro is coming to DevUE to support you!


Dextro is our own programming language like [Verse](https://dev.epicgames.com/verse). The only difference is that Dextro is based on C++ and therefor allows for more possibilities.



## Using Dextro
To use Dextro in your project, open DevUE and click on "Dextro" in the menu bar on the top. Then select "Create Dextro Class" and choose a template (such as "Dextro Device"). Give the class a name and click "create".



After creating the class, open the Dextro dropdown menu again and select "Dextro Explorer" under your project name. Double-click on it to open it, which will open your preffered IDE (it is recommended to change the preffered IDE to Visual Studio Code in the [Engine Preferences](https://dev.dgames.org/docs/editor/preferences)).



## "Using" Dextro attributes
Each Dextro class uses "using" attributes to access different things like Devices. For a Dextro device, you need to use the following attribute:
```dextro
using { dextro://devnite.com/devices }
```


If you want to use DevNite or UE devices you just need to define them. You can do this by using the following syntax:

```
EliminationFeed : elimination_feed_device()
```

You can find more information on the [Dextro Documentation](https://dev.dgames.org/docs/dextro).
