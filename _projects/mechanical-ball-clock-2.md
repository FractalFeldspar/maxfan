---
layout: page
title: Mechanical Ball Clock 2 (Ongoing)
description: Apr 2023
img: assets/img/mechanical_ball_clock_2.jpg
importance: 1
category: Mechanical
related_publications: false
---


<div class="embed-responsive embed-responsive-16by9 mb-3">
    <iframe width="560" height="315" src="https://www.youtube.com/embed/5c_HX65pFv8?si=cXLboszJ8QVka16d" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</div>

Unlike my first mechanical ball clock, I have designed this clock to have no moving parts except for the steel balls. This clock is not finished, but the timekeeping module (top red), display module (green), and regulator module (bottom red) are close to finished. Some more details about these modules:
<ul>
<li>The timekeeping module’s period is set by the time it takes for a ball to roll down the spiral ramp (around 30 seconds). This period can be adjusted by tilting the entire spiral clockwise or counterclockwise. However, like other clocks based around rolling balls, this clock’s period is not very precise due to rolling resistance and its sensitivity to dust.</li>
<li>The number of balls in the display module represents how much time has passed. Each ball in the top submodule represents 30 seconds and each ball in the bottom submodule represents 5 minutes (ignore the two balls on the far left of each submodule). I don’t show this in the video, but it is possible to toggle the submodule between a 10 ball cycle, 8 ball cycle, 6 ball cycle, and a pass-through mode by altering where the row of balls transition from being near the wall to being away from the wall (when looking from left to right).</li>
<li>The regulator module’s sole purpose is to take in surges of steel balls from the display module and release them one at a time to whatever module comes after it. This ensures that the next module has a predictable input since surges of steel balls can create jams, overflows, and other unintended effects.</li>
</ul>

As a word of warning to anyone attempting to design similar mechanisms (i.e., mechanisms where most/all the moving parts are balls), these mechanisms are deceptively difficult to get right. Since each ball has 6 degrees of freedom, there are many more ways for these mechanisms to malfunction compared to more constrained mechanisms like, say, linkages and gearboxes. Couple this with the effects of friction, dust, vibration, and magnetism on the steel balls and it becomes very easy for a mechanism under development to seem promising but then hit a wall that no amount of incremental iteration can overcome. Most mechanisms I have designed that had similar levels of geometric complexity took around 5 iterations to get right, but each of the three mechanisms in this video took me 80 or more iterations to get right. A mechanism under investigation would get to at most a 95% success rate before factors like friction and vibration made it impossible to improve the success rate even if I made 20 more iterations of that mechanism. (Even subtle things like the amount of skin oil I left on the steel balls while handling them could noticeably affect the success rate.) This would then force me to pivot to a different strategy and investigate a new mechanism.

<div class="embed-responsive embed-responsive-16by9 mb-3">
    <iframe width="560" height="315" src="https://www.youtube.com/embed/wKQSb0pX8GY?si=vyMG-2OIsNtoSb-Z" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</div>
<div class="caption mt-0">
    The design of the display module of the clock took around 80 iterations in total.
</div>

Don’t get me wrong, I believe mechanisms like these are among the most fascinating (and possibly least explored) of all the mechanisms I have encountered, but developing them is unlike any other mechanism I have attempted before. I will have more notes once this clock is done, but for now I would like to note that these types of mechanisms generally function better when they rely on slow, static actions such as a ball sinking and wedging another ball sideways as opposed to momentum-based actions such as a ball gaining speed by rolling down a track and then using its momentum to knock another ball sideways. Minimizing vibration by avoiding sudden vertical drops, sudden direction changes, or high speeds is also essential.

