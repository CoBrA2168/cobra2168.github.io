---
title: "Free Tweak Release: CarPlayHideLabels"
categories:
  - General
tags:
  - CarPlayHideLabels
  - Cydia
  - Updates
  - iOS13
---

Since I began using CarPlay when I got a new vehicle last year, it's always bugged me that the home screen grid of icons had the app name labels.  I've had these hidden on my phone for years now, either using my own hooks or third party tweaks.  I've always ignored the fact that my CarPlay icons still had the labels.

Enter Canvas: a new tweak by leftyfl1p (the creator of CarBridge) which allows you to change the CarPlay wallpaper.  Once I got this installed and picked a cool background, it was finally time to get rid of those labels once and for all.  I was able to easily do it on iOS 12 and earlier versions since all of the CarPlay-specific code was well-documented and lived within SpringBoard (using the "Stark" prefix in most cases).  However, with iOS 13, all of the CarPlay code had moved out of SpringBoard.  Through various debugging measures on my iPhone SE running [checkra1n](https://checkra.in), I learned that all CarPlay-related code is now contained in it's own application, which lives at */System/Library/CoreServices/CarPlay.app*.  While it makes a lot of sense pulling it out of SpringBoard, it took me a bit longer to figure this out and determine which hooks were needed to hide those pesky labels on iOS 13.  But once that piece of the puzzle was solved, hiding them on iOS 13 was just as trivial as on iOS 12 and earlier.  Thus, my tweak CarPlayHideLabels supports all versions of CarPlay (from iOS 7.1 to iOS 13).

The move to putting CarPlay contained in it's own application should make it a lot easier to create a tweak to run CarPlay directly on a device.  I suspect someone smarter than me will come along one day and release a tweak to do just that.

[This tweak is open source, check it out!](https://github.com/joshuaseltzer/CarPlayHideLabels)

[Feel free to comment on this release on the Reddit release post here!](https://www.reddit.com/r/jailbreak/comments/e3zedj/release_carplayhidelabels_hide_the_app_icon/)