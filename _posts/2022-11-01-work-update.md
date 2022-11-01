---
layout: post
title: "Work update"
categories: cambridge
squareimage: /sabbaticaldiary/images/2022-11-01-square.jpg
---
<img src="/sabbaticaldiary/images/2022-11-01.jpg" alt="programming code" class="center">

It's the start of a new month!

Last month my focus was on doing the layout of a molecule. This was a much bigger challenge than I had anticipated! I have now dealt with rendering the drawing of molecules with single carbon-carbon / carbon-hydrogen bonds and am now working towards rendering the drawing of molecules with multiple carbon-carbon bonds. For example, here is an ethene molecule that was drawn simply by joining the bonds:

<img src="/sabbaticaldiary/images/2022-11-01-2.jpg" alt="ethene before layout" class="center">

And here is the same molecule re-drawn showing the right bond angle between the hydrogen and carbon atoms (the double bond is at the moment on top of each other):

<img src="/sabbaticaldiary/images/2022-11-01-3.jpg" alt="ethene after layout" class="center">

Eventually, I also want to incorporate oxygen and nitrogen atoms in the programme.

Key things I have learnt are:
* using geometry, especially working with vectors, in my programme;
* creating a new class to store vectors. 