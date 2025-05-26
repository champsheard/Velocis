---
title: "Velocis"
author: "Euwain Sheard"
description: "Ultra Fast CoreXY auto ejecting 3d Printer"
created_at: "2025-05-24"
---


# Project Velocis

**Author: Euwain Sheard**

**Description Ultra Fast CoreXY auto ejecting 3d Printer**

**Total time spent: *8.5h***

## May 24 (Day 1): Started CADing and Part Sourcing

I started by looking at various parts and how they would fit into my project. This is what I decided on so far

| Part    | Price |
| -------- | ------- |
| Phaetus RAPIDO HOTEND  | $80    |
| Octopus Pro | $70    |
| Orbiter v2.5 | $50 |

I might change this later, but I like these parts

Now to Cad! I have taken inspiration from the [Voron Trident](https://vorondesign.com/voron_trident) for the design of the frame and triple lead screw z axis

### Picture of the cad

<img src="img/CAD%20Frame.png" width="500px">

I am, however, having trouble with the extrusion files I found...

**Time spent: 2h**

## Day 1 Part 2

I worked on the Cad some more. I fixed the extrusion problems by uses [these](https://www.printables.com/model/312162-2020-2040-3030-3060-aluminum-extrusions/files) files instead. However this meant that I had to redesign the frame. When I redesigned the frame I decided to change some of the extrusion lengths. Now instead of 370, and 500, I shortened the extrusions to 350 and 450. I also modeled some of the x, and z gantry. I also organized some of the components, mainly the extrusions, into folders. I am going to use a mixture of Fusion 360's internal and external component options.

### Updated Picture of Cad
<img src="img/CAD Frame 2.png" width="500px">

<br/>

**Time spent: 1.5h**

## May 25 (Day 2): Cad

I started today by finishing CADing the basic frame, and looking at various linear rails. I found [these](https://www.aliexpress.us/item/2251832586981749.html?spm=2114.12010612.8148356.4.46a27cbep2UDWu&gatewayAdapt=glo2usa4itemAdapt) on the Voron sourcing guide for my y axis, but I am going to shop around for better prices. I am going to attach the Linear rails on the bottom of the aluminum extrusions, so I can install a cable chain later. 

I haven't CADed the linear rails yet, maybe I'll do that later today.

### Picture of Cad

<img src="img/CAD Frame 3.png" width="500px">

<br/>

**Time spent: 1.5h**

## Day 2 Part 2: Cad

I started by finding models of the linear rails I am going to use. I am going with **MGN9H** for the y axis, which is what I am designing. I have no idea how this is all going to fit into the budget. 

Then I started to CAD. I first modified the length of the files I found from 390 mm to 300 to use them in my design. Then I imported them and attached them to my frame with joints. Then I imported the carriages into the design and used a sliding joint to attach them to the rail. It took me a little time to figure out, but in the end I got it. I then imported another aluminum extrusion to work as my x axis. 

###  Pictures of Cad

Added X axis extrusion

<img src="img/Cad Frame 4.png" width="500px">

<br/>

One of the linear rails

<img src="img/Linear Rails.png" width="1000px">

<br/>

**Time spent 1.5h** 


## Day 3 (May 26): Tried to Cad and looked up corexy kinamatics

Today I started to Cad the connectors between the x axis gantry and the y axis linear rails, and completed this only to find out that one of the linear rails was not in the right place. Then I spend way to long only to not figure it out. This problem is really frustrating. I have looked at all the joints and sketches and what not, but couldn't find the error. 

I decided to take a break and further my knowledge of corexy kinamatics. I have a basic understanding but want to learn more about it I found [this](https://corexy.com/theory.html) really useful website that explains it.

I don't have any pictures of Cad for the moment, I am still working on the error 😔

## Day 3 Part 2: Fixed error

I took a break for a bit to work on another project, after I came back to Fusion I had an idea to delete the sketch and look at the joint which was broken, and then undo it and fix the joint. This didn't work, but I was able to remake the sketch and that fixed it!.

Now I can finally work on connecting the extrusions!

I added an simple part to connect the extrusion to the linear rail, I still need to make the other one and add belt paths.

### Pictures of Cad

<img src="img/Linear Rail Connectors.png" width="500px">

<br/>

**Time spent 2h** 
















