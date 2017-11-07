---
layout: post
title: "Google Phone Interview"
img: google.jpg # Add image post (optional)
date: 2017-10-18 00:09:00 +0300
description: You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. # Add post description (optional)
tag: [Google, Phone, Interview]
color: orange
---
Given a clock with three button, first one can advance one hour, second one can advance one minute, third one can reset time to 00:00.
Design an api to print the button order of adjust initial time to given time.

```
public List<String> timeAdjust(String initialTime, String targetTime) {
	#List<String> result1: use reset button
	#List<String> result2: do not use reset button
	#return shorter one
}
``` 