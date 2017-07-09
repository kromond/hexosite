---
title: Trash Praxis
date: 2017-07-04 15:20:46
tags: 
	- real-time
	- vr
	- Unreal Engine 4
cover_image: assets/images/CaptureYT_3_coverimg.jpg
---
The initial motivation for this project was to investigate rapid content creation using Unreal Engine 4.  The concept was to create serial VR that could be distributed either as an executable (like a game) or as a 360 render distributed via YouTube.  For the proof of concept a very simple framework was made: it will be like 2 person a podcast with visuals.  The podcast topic was a casual discussion of media and culture between hosts Alfio Leotta and Raqi Syed, both academics in the area of Media studies at Victoria University of Wellington.  The project was undertaken as part of the VUW 'Digital Futures' research initiative.

![img1](costumeWip3.gif) ![img2](scWip.gif)

'Virtual Production' is a film making technique refined through the production of the film 'Avatar' whereby live action performances are captured using various technologies to be reconstructed into digital images of that performance.  This technique is being continually refined as it's used on high budget film productions like 'The Jungle Book', 'War for the Planet of the Apes', etc.

By using motion capture virtual production techniques for this project we  collected an array of data around our 'event'.  Data collected included multichannel audio, reference video, motion capture data, facial capture data all synced in time.  With this data, we can reconstruct the event with computer graphics characters and present the result in multiple formats, allowing us to gage the result against the production effort for each format. 

Here is an example from one of the motion capture sessions, captured with the Gear360

{% iframe https://www.youtube.com/embed/HDHagPLOmwY 640 360 %}

Producing media content for Virtual Reality head mounted displays is not particularly rapid and comes with technical challenges. There are two primary vehicles for content delivery.  One is 360 degree video.  The other is geometry and animation delivered by game engine.  Both have their drawbacks and merits both qualitatively and in terms of production issues. This project proposed to deliver in both formats providing empirical data on viable production methods for VR content by utilizing both vehicles. Here is a very early sample of putting the data onto characters in Unreal Engine 4

{% iframe https://www.youtube.com/embed/lQlDdcQtojE 640 360 %}

The characters are from the Autodesk character builder.  Clearly the lifeless faces are going to be intolroable to watch.  In this next test, the characters were covered with fur and put into a woodland scene.

{% iframe https://www.youtube.com/embed/uwYXBlgDZNg 640 360 %}

Slightly more watchable, however at this point, it's clear to me faces are critical to the success of this piece.

I spent some time looking into ways I could get a facial performance, indluding open source options

{% iframe https://www.youtube.com/embed/n4zpVPKpk7Q 640 360 %}

In the end, I felt I did not have the time to build a facial performance rig.  Instead I used a basic method for jaw motion on the male character and projected video on the female character.  I plan to revisit the facial performance aspect of this project

{% iframe https://www.youtube.com/embed/-QVjepYdkuc 640 360 %}