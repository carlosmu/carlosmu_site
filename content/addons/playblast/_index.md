---
title: "Playblast"
date: 2021-05-08T18:33:25-03:00
draft: false
---

![featured.png]({{< base-url >}}img/addons/playblast/featured.png#fullsize)

## Motivation

When animating a shot, usually is needed to make a playblast video to know that everything is fine, especially regarding of timing. But blender doesn't handle the final render output and the opengl-render output separately. For this reason it is likely that you are constantly changing the parameters for each case. To solve this problem I have created this addon. 

![demo.gif]({{< base-url >}}img/addons/playblast/demo.gif#fullsize)

## How does this addon help you? 

This addon will allow you to define a default behavior to perform playblasts quickly, without worrying about a lot of unnecessary settings every time. 
Usage

Simply configure the behavior that suits your needs only once, in the addon preferences. The rest is just the touch of a button whenever you need it.

![button.png]({{< base-url >}}img/addons/playblast/button.png#fullsize)

## Available for download

[![gumroad-logo.png]({{< base-url >}}img/addons/gumroad-logo.png#thumbnail)](https://gumroad.com/l/playblast)
[![blender-market-logo.png]({{< base-url >}}img/addons/blender-market-logo.png#thumbnail)](https://blendermarket.com/products/playblast)
[![github-logo.png]({{< base-url >}}img/addons/github-logo.png#thumbnail)](https://github.com/carlosmu/playblast)

## Installation

1. Download the zip file.

2. Go to Edit > Preferences > Addons > Install. And select the zip file on your computer.

3. Activate the addon with the checkbox.

4. Modify the addon preferences as needed.

5. Save the preferences.

## Addon Preferences

This addon has a lot of preferences. This will allow you not to have to configure the output, format, codecs, resolution, etc, every time. Enjoy it!

To see the details of each option go to the documentation subpage.

![playblast_preferences.png]({{< base-url >}}img/addons/playblast/playblast_preferences.png#fullsize)
![playblast_prefs.gif]({{< base-url >}}img/addons/playblast/playblast_prefs.gif#fullsize)

## Known Issues:

1. At least in the initial version you can't cancel rendering. Please save your file always, and wait patiently for the task to finish.
2. The h264 codec requires you to work with resolutions divisible by 2 Pay attention to your resolution in width and height. Anyway if the resolution does not match I have automated a solution! :D (only when "resize method" preference is active).
3. Currently Blender's internal player has some problems with audio playback. If you experience this type of problem, I recommend setting up an external player, such as VLC, which is free and open source (https://www.videolan.org).

## Setting up an external player 

![custom_player.png]({{< base-url >}}img/addons/playblast/custom_player.png#fullsize)