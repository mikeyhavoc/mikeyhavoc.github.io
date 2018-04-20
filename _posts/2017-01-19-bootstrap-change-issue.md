---
layout: post
title: Bootstrap Change Issue
author: Michael Williams
date: 2017-01-19 10:11:15 -0500
---
# Bootstrap Convert Issue

Changing from Bootstrap v.3.3.7 to v.4.0.0 beta-3 has been a task in its own but has not been as hard as it looked. It has had a few small tweaks, but in all it has streamlined things far more than making things more difficult so I have gone ahead and went for it.

## Header Section

Within the header section I have had to make minimal changes, only to the class 'col-xs-12' to a col-12 which is a flex-box class for a whole column instead of the original xs-12. 

## Nav changes

Now the navigation was a large change but it streamlined things within it far more. I reduced the code size by half in doing so. I had to change almost all the classes, and way I was using the nav but to reduce the code it was worth it. I wanted to change this section to a better looking navigation in my web site anyways, so I was doing myself a favor when I was doing the conversion honestly. Having a chance to rework the code and incrementally change the look all at the same time. The next _goal_ for this area is to get a class of active on the chosen button. Then to pick it up with a class of 'sr-only' too. But that is further down the road. As of now I have a hidden search box functionality at the end of the navigation form waiting to be incrementally added in.

## Small Changes

Most of the other changes in the layout are small. I am now using the class 'btn-outline-danger' instead of 'btn-danger' for buttons they are outlined in red instead of colored in red. Then when hoved on they fill up with the color. I am implementing col-12 often instead of col-xs-12 since the last mentioned is decremented now.