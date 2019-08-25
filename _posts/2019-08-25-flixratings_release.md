---
title: "FlixRatings for Netflix: FlixEnhancer Lives On!"
categories:
  - FlixEnhancer
tags:
  - FlixEnhancer
  - FlixRatings
  - Cydia
  - Sileo
  - Updates
  - Netflix
---

I'm excited to announce that in light of the recent 12.4 jailbreak (which is the first for a signed version of iOS in a very long time), I've decided to rebirth an old tweak I worked on years ago: FlixEnhancer for Netflix.

<h2>What's Changing?</h2>
FlixEnhancer originally had 3 features: the ability to skip forward in the player (both on device and when casting to a Chromecast), additional "enhanced" ratings, and the ability to automatically set the Chromecast output audio to "stereo" without having to manually select it.  That third feature was very finicky, hard to maintain, and used by virtually no one except myself.  Therefore, that feature was dropped early on.  The first feature (forward skip) is no longer required, since Netflix decided to add a forward skip option natively.  The second feature (enhanced ratings) is still very relevant today and the reason most people looked into FlixEnhancer.

For that reason, I'm rebranding the tweak as "FlixRatings for Netflix" and focusing on supporting only the enhanced ratings portion of the tweak.  This has been hard to maintain with the constant updates made to the Netflix application, so it takes a considerable amount of time to ensure compatibility.  I should also mention, that the forward skip code will still be included for those who are stuck on older versions of Netflix (e.g. Netflix 9.8.0, which is the last version available for iOS 8, does not have native forward skipping).  Also, the forward skip feature is still available when casting even on the latest version of the application since this is not natively supported by Netflix yet.

The good news about the relaunch: I've revisited the code I was using to match the Netflix video with the enhanced rating and was able to greatly improve the algorithm, resulting in a higher success rate of matches.  That means you'll see less "No enhanced rating available for this title" messages when browsing the app.  However, it should be mentioned that not all titles are able to be automatically matched, so you will still see it from time to time.

<h2>A Note on Repositories</h2>
Since FlixEnhancer was originally hosted as a paid package on BigBoss (i.e. the Cydia Store), I will be doing [exactly what I had done with my other paid tweak, Sleeper,](https://joshuaseltzer.github.io/sleeper/sleeper_repo_change/) by changing repositories to Packix while simultaneously maintaining the BigBoss package.  To summarize this change: the package on BigBoss will be renamed to "FlixRatings for Netflix (Legacy)" to indicate that this is a legacy package and new purchases should be done on the Packix repository.  Both of the packages will continue to receive updates for those who have purchased FlixEnhancer previously (as always, my tweaks will always receive updates free of charge).  If you had purchased the tweak on Cydia, you can also freely move over to the Packix version of the tweak if you'd like but both will be identical in functionality.  However, it's worth noting that the Packix version will likely be updated more quickly than the BigBoss package.

Well, that's enough for me for now.  If you have any questions or would otherwise like to reach out, feel free to use any of the methods of contact on the left part of this page.  As a reminder, FlixRatings for Netflix is supported on all jailbreakable firmwares running iOS 8.0.0 through iOS 12.4, including supporting the legacy versions of Netflix which are required to run on some of those older versions.

[Grab the new FlixRatings for Netflix today on Packix for $0.99!](https://joshuaseltzer.github.io/flixratings/)
