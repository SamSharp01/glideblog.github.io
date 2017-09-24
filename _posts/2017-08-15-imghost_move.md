---
layout: post
title:  "Moving the Screenshot server + SSL"
date:   2017-08-15 00:24:00 +0100
categories: glideservers websites
---
The [GlideServers screenshot server](https://github.com/GlideServers/ShareX-Server), has been running since the 4th September, a total of 345 days.
In that time we have accumulated 2823 screenshots, using 27GB space. (there are lots of videos too).

It started running on the SSD node (link to come to GS blog), but as space is a premium, I decided to move it when I migrated the nodes.

### Why move it?

* I wanted to use it to run some of the images that the main website used, however it required SSL to be enabled or else the website would not be green.
* With the moving of the SSD node (insert link to GS blog), the node would have slightly less storage on, so I could free up some by moving this to the HDD node.

### Result

* Now the website is green! Wohoo ![Greencap](http://i.imgur.com/6GyeIso.png)
* Images on the website will be served from here, so less file duplication.

### Can I use it?

Yes! You will need ShareX, but this is easy to configure, and I plan to write a wiki page in the ShareX repo.
If you send me a message via e-mail (at the bottom), I can show you how to do this, and use our key to login.
