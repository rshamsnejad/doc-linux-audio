# Linux Audio Guide
#### Created by Robin SHAMSNEJAD

## Introduction

##### An attempt at writing some kind of "Linux audio bible"

This project starts from a frustration of mine. I am passionate both about music and audio technology, and about computers. This gradually led me to dive into trying to use professional audio under a GNU/Linux system.

Now in 2020, after a lot of trial and error, I am starting to know where to look when I need to do some out-of-the-ordinary audio operation under GNU/Linux. And by out-of-the-ordinary, I mean anything beyond what is used by most computer users ; which is most of the time a pair of speakers and a microphone input. This case, along with other common ones, are most of the time working out-of-the-box as of today.

##### This guide is intended to dive deeper than what is needed to "make common cases just work".

When dealing with surround sound, it can add a layer of complexity, but by Googling around, it's not that difficult to set up.  
But when dealing with a professional audio environment, where you would use audio interfaces with, say, 64 MADI I/O ? And you want to split these I/Os for several purposes ?  

##### This is when the fun stuff starts.

The documentation on the various building blocks of GNU/Linux audio is widely inconsistent. When you need to do "exotic" things, some are well-made, others are outdated or lack clarity. I often find myself Googling several times the same keywords to a solution for a problem I have, because I can't remember if it was in the docs for this or that. Let's try to fix that.

## Goals

### Gather and sort existing documentation

It can be either online or paper, though most will likely be online. Then, each source will be assigned a quality level, for example : "Good as it is and well-maintainted", "Usable but contains some outdated information", etc. This will later help to focus the work.

The following topics shall be considered :

* Audio basics
  * Acoustics
  * Human perception
* Audio technology
  * Analog audio
  * Digital audio
  * Audio effects
  * Audio chain concepts
  * Consumer audio products
  * Professional audio products
* Audio in computing
  * Audio hardware
  * Audio production software
  * Networked audio
  * Audio codecs
* Audio technology in GNU/Linux
  * ALSA / Linux kernel
  * PulseAudio
  * JACK
  * Audio frameworks

### Maps

Create visual maps of typical audio chains, and document them. The goal here would be the give the ability to find out how to act at a glance, when something needs to be done.
