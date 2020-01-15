---
layout: default
title: "Linear Rail Printer: Beginnings"
youtubeID: TICTYyVr5t8
---
# Linear Rail Printer: Beginnings

The world is running out of reasons to design and build your own 3D printer from scratch. My good friend Joshua [@poofjunior](https://twitter.com/Poofjunior) embarked on that journey with [Jubilee](https://github.com/machineagency/jubilee) with the intent of bringing open-source, open-standard tool changing into the world. That noble goal is already paying off in the form of some ridiculously nice prints and some cool other applications, soon to be shown off at [CHI](https://chi2020.acm.org/)!

My intention for my printer is far less noble. I saw the flying linear rail axis on the RailCore II design, and thought that it would be cool to do that on a much smaller, cheaper printer. I started playing around in Rhino, one thing led to another, and this popped out:

![Earliest screenshot of LRP](https://i.imgur.com/2jXBxUy.png)

It's a pretty cute little printer, running Nema14 steppers for the axes, cheap Chinese linear rail, and the fabricated parts all made of aluminum extruded bar. The rectangle where the bed should be is the size of a Replicator 2 print volume. At this point, I felt like I was mostly done with the design -- of course, I was wrong, but everything did *kinda* work in my head. Just bolt those carriage blocks down and call it good, right?

Uh, no. Suddenly I needed actual t-slot extrusion to mount the bed, the number of carriage blocks doubled on two out of three axes, and a lot of small adjustments happened:

![Less early screenshot of LRP](https://i.imgur.com/o6ATFGg.png)

Looking back, it was actually remarkably close at this point, it just needed a whole lot of fiddling from there to get to a "buildable" state. Most of the gray plates you're seeing are still using a boilerplate 3mm hole diameter for M3 bolts, and since I'm being a doofus and using Rhino for this project, every single one of them had to be gone over and edited to be 3.2mm to clear the bolts. That was a "fun" two hours.

What really attributed to the design feeling complete by this time was the sheer amount of little decisions and fixes that had to be made. Being by far the most complex machine I've constructed, every mounting plate and joint feels like a small journey. It wasn't just mechanical design decisions, though -- I wrestled with the extruder choice for quite a while. At first, I wanted to do something like a Zesty Nimble to keep the weight on the motion platform low. That turned out to be much more trouble than it's worth in this case, and also ridiculously expensive when compared to the E3D Hemera *while also not being nearly as good an extruder*. The weight concern is still valid, but at the point where I am in the project now (collecting parts) it's way easier to get the Hemera given that it has an actual resale value and could very easily be repurposed on a less ridiculous printer design. I'm keeping my eye on the Flex3Drive project's Nema8 version as a nice compromise, but that's in pre-production and I've got a printer to build, so off I go with the Hemera.

Since that point in the project, I've made no large changes to the design -- just adjustments to work with bolts. Oh, and *the bolts*. The total BOM just for bolts came to about $20 on Bolt Depot, and the vast majority is M3. But, the agony of having not designed around the bolts in the first place is a story for the next post. Yeah, you heard me right, this is the first in a series! No ETA for when the next one's coming, though -- but hopefully before my SpeedPAK of linear rail gets to me...
