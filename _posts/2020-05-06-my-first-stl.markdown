---
layout: post
title: "My first 3D print design"
date: 2020-05-06 23:44:00 -0400
categories: blog
tags: 3d-printing
---
I recently purchased a 3D printer, the 
[Monoprice MP Delta Mini](https://www.monoprice.com/product?p_id=21666). The 
price was right, and with the current COVID-19 situation I can't exactly use 
the one at my friendly local makerspace. Since this is my first 3D printer, I'm
not exactly qualified to write a review, but I will say that the build area is
more limiting than I thought it would be. I have to resize nearly everything
I download, and my apartment is filling up with tiny, tiny things that I've
printed. I've already got my eye on upgrading to larger printers and resin
printers.

So this post is about my first attempt at designing something to 3D print. It
fits everything I wanted to do. It's small, it fixes a problem I have right 
now, and it's simple.

# The Problem

I have too many Amiibos for my mantle. Just look at all the little guys! When
you throw in my Sonic figurines and other random mantle knick-knacks, I've run
out of space. I don't have many Amiibos on my list right now, in fact none, so 
the win here is for less clutter rather than more stuff.

![Many minis](/assets/images/amiibostandmkii/many-minis.jpg)

# The Solution

A little shelf to stack the Amiibos would be great! Just one on top of the 
other will almost double my space on the mantle. All the various Amiibo stands
I found on [Thingiverse](https://www.thingiverse.com/) and 
[Cults](https://cults3d.com/) were all too large or complex for my purposes, 
though hence this first foray into 3D print design.

And here's Amiibo Stand Mk. II! Printed with 25% infill, tetrahedral pattern,
with luminous green glow-in-the-dark PLA. 
![mk-ii](/assets/images/amiibostandmkii/amiibostandmkii.jpg)

Mk. I snapped almost immediately after I printed it while I was trying to clean
up the little stray bits of filament, so I didn't even get a picture of it. It
wasn't worth printing again. Mk. II adds little supports, but I've already 
identified a couple of issues that warrant a Mk. III. I don't have any actual
engineering chops other than software engineering chops, so I'm guessing with
the structural features.

Did I say guessing? I meant I'm using an agile process, iterating quickly.

# The Tools

I decided to go with [OpenSCAD](https://www.openscad.org/) for this project, 
which bills itself as "The Programmers Solid 3D CAD Modeller," which is just 
right up my alley. Even though I worked in CAD as a software engineer for 
several years, I never quite got the knack of actually *using* the software.
Being able to code up my shapes suits me just fine, as I think the print
process has enough room for error without the GUI introducing more.

As a language OpenSCAD is, eh, it's ok from what I've seen of it so far. The
vaguely C-esque syntax is harmless. Although it does vaguely remind me of
[GAP](https://www.gap-system.org/index.html), which leaves a bad taste in my
mouth. My experience is that this sort of DSL has little frictions and pain
points all over the place. I'm interested to see what they are in OpenSCAD as
I explore further and push boundaries.

# The Code

Feel free to grab the OpenSCAD code on 
[my GitHub](https://github.com/ZSarver/amiibo-stand), or the print-ready final
product [on Thingiverse](https://www.thingiverse.com/thing:4350357) and [on Cults.](https://cults3d.com/en/3d-model/game/simple-amiibo-stand)