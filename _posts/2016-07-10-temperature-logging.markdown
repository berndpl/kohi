---
layout: post
title:  Temperature Logging
date:   2016-07-10 20:47:45 +0100
categories: Background
---

After a sheer endless research for temperature probes and logging systems I decided on the following setup.

### Temperature

I am setting up a Raspberry Pi as temperature server connecting 2 probes via the Phidget USB board.

* Raspberry Pi 1, Model B
* Phidget 1048, USB Temperature Module
* Stick Probe for beans temperature
* Cable Probe for environment temperature

### Logging

The Phidget can be directly connected to a computer for use with Artisan or via the Raspberry Pi acting as server to Roastmaster on iOS. Having a Laptop-less system is appealing but it comes with the additional complexity of a Raspberry Pi as server. I will try both.

* [Artisan](https://github.com/artisan-roaster-scope/artisan)
* [Roastmaster](https://itunes.apple.com/us/app/roastmaster/id375526217?mt=8) for iOS

My goal is to have a two probe system to log roast curves for better understanding of the roast process and reproduceability.
