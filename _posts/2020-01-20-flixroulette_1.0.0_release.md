---
title: "Another Freebie: FlixRoulette for Netflix!"
categories:
  - General
tags:
  - FlixRoulette
  - Netflix
  - Cydia
  - Updates
  - iOS13
---

One request I frequently got when creating [FlixRatings for Netflix](https://joshuaseltzer.github.io/flixratings/) was the ability to "shuffle" your favorite show on the Netflix application for iOS.  It was an interesting idea, and I knew it was something I could easily implement since I had already conducted a lot of research on the inner-workings of the Netflix app.

Adding a button to the UI initially I thought would be very simple.  First I was able to inject a custom view into the bar of buttons that already exist when viewing the description of a movie/show.  It started as a simple, gray button that worked as a placeholder.  A few hours later I was able to find the data model object which included all of the specific identifiers for all of the shows for a given title.  Simply calling a few random number generators made it easy enough to just pick a random one!

Going back to the UI proved to be a bit of a challenge.   wanted it to look native, so I picked an icon and settled on the "Shuffle" text.  Getting everything lined up with the other icons that already exist took a lot more effort than I had initially imagined.  In summary, Netflix is using a [UIStackView](https://developer.apple.com/documentation/uikit/uistackview), which is a newer UIKit object that I wasn't familiar with.  Well, it was introduced in iOS 9, but I haven't done enough iOS development in recent years to ever come across it or use it in my workflow.

Overall it was a fun challenge, and it was a great way to really learn how UIStackView objects behave.

[Feel free to comment on this release on the Reddit release post here.](https://www.reddit.com/r/jailbreak/comments/erez0b/release_flixroulette_for_netflix_shuffle_episodes/)

[Alternatively, grab it directly from the BigBoss repository using your favorite package manager.](http://cydia.saurik.com/package/com.joshuaseltzer.flixroulette/)