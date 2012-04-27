---
layout: post
title: Setting the vision
---

# Setting the vision for Truestack

I do love building things on the web.
I've worked on a few projects in my day, and many times keeping a site or product running smoothly can feel like holding back the ocean.  Every time you feel like you are making some sort of progress, you get hit with a new issue to face.

Over time, the code begins to 'rot' - methods that are long unused stay in the codebase, because no one wants to take the time to find out if they are being used.  Sometimes, things you think are being used are never used.  Or being used in ways you never imagined.

## Tools
Most areas of development have some processes to help in fighting back against regressions.

* Functional / Unit tests help catch regressions
* Integration tests and staging servers can help too
* But these all treat the app as a black box, living in it's own safe happy place
* The world is not a happy place

* We need tools which will help us watch our precious baby as he or she ventures into the wide wild world.
* Can't do true regression testing on a non-production application.
* You need to know how it actually is performing, and how people are actually using it (or not)

+ You need to not only know how you are performing now, but how has that changed over time?  Is the method you profiled and optimized last year -- staying optimized?
+ Is the action you think being used, actually used?
+ Where are the methods no one is using? Can I just remove them?

+ And lastly - there is no use to tell me an action takes X milliseconds.  It's a number.  Humans need differential data.
+ Instead, tell me that since the last deploy, Action X is taking 5% more time than it used to be.

## What else?
+ We want to know a few other things...
+ When all indicators start to tell me things are getting slow, I need to decide when it is *too* slow.  But what then?
+ Truestack helps you by giving you a few starting points.  If the overall site is slow -- we'll point you at methods to optimize that are used everywhere and take a bit of time.
+ If you only want to optimize a specific action, we'll show you the things which make up the slow response time (from controller, model, helpers, views, to browser rendering).

## Conclusion
Truestack wants to be the helper for your app. The butler, the one looking out for you. Like the assistant coach.

Truestack watches your app, tracking how long things take, and lets you know how things are changing over time, as you deploy and update your app.  When things get too slow, truestack is there with all the data to point you in the most effective direction so you can speed that sucker up and get rolling again.
