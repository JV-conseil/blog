---
title: "iOS 17.4: Now Playing not working on Apple Watch ⌚"
date: "2024-04-30T18:13:39+01:00"
categories: ["iwatch", "watchOS"]
tags: ["iwatch", "watchOS"]     # TAG names should always be lowercase
---

<!-- markdownlint-disable MD001 MD033 MD053 -->
# iOS 17.4: Now Playing not working on Apple Watch ⌚

[![Become a sponsor to JV-conseil](https://img.shields.io/static/v1?label=Sponsor&message=%E2%9D%A4&logo=GitHub&color=%23fe8e86)](https://github.com/sponsors/JV-conseil "Become a sponsor to JV-conseil")
[![Follow JV conseil on StackOverflow](https://img.shields.io/stackexchange/stackoverflow/r/2477854)](https://stackoverflow.com/users/2477854/jv-conseil "Follow JV conseil on StackOverflow")
[![Follow JV conseil on LinkedIn](https://img.shields.io/badge/LinkedIn-blue?logo=linkedin)](https://www.linkedin.com/in/vieillefont/ "Follow JV conseil on LinkedIn")
[![Follow JVconseil on Twitter](https://img.shields.io/twitter/follow/JVconseil.svg?style=social&logo=twitter)](https://twitter.com/JVconseil "Follow JVconseil on Twitter")
[![Follow JVconseil on Mastodon](https://img.shields.io/mastodon/follow/110950122046692405)](https://mastodon.social/@JVconseil "Follow JVconseil on Mastodon")
[![Follow JV conseil on GitHub](https://img.shields.io/github/followers/JV-conseil?label=JV-conseil&style=social)](https://github.com/JV-conseil "Follow JV conseil on GitHub")

<!--
![Now Playing on Apple Watch not working since Apple iOS 17 4](https://gist.github.com/assets/8126807/ee09230f-d099-43ee-9332-f93a59b05dd0)
-->

<img src="https://gist.github.com/assets/8126807/ee09230f-d099-43ee-9332-f93a59b05dd0" align="right" width="50%" alt="Now Playing on Apple Watch not working since Apple iOS 17.4">

**Since I updated my Apple iPhone 14 Pro Max to [iOS 17.4][ios-1741], I can no longer control the audio playback from my [Apple Watch Series 2][apple-watch-serie-2] with the [Now Playing][watchos-now-playing] app.**

| [Apple Watch Series 2][apple-watch-serie-2]                                     | Apple iPhone 14 Pro Max                                                                                                                                                         |
| ------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Model A1758                                                                     | Model A2894                                                                                                                                                                     |
| [watchOS 6.3](https://support.apple.com/en-us/118388 "About watchOS 6 Updates") | ~~iOS 17.4~~<br>~~[iOS 17.4.1][ios-1741]<br>[iOS 17.5][ios-175]<br>[iOS 17.6][ios-176]<br>[iOS 17.7][ios-177]<br>[iOS 18.0][ios-18]~~<br>[iOS 18.2][ios-182] :white_check_mark: |
| 14 Dec 2020                                                                     | 07 Mar 2024                                                                                                                                                                     |

The **[Now Playing][watchos-now-playing]** app _should let_ you control audio playback on Apple Watch, iPhone, and other devices.

Since March 7th, 2024, the [Now Playing][watchos-now-playing] app on my [Apple Watch Series 2][apple-watch-serie-2] displays an endless spinning wheel demonstrating that it cannot connect to my iPhone 14.

### Failed Troubleshooting Attempts 🙅

1. Switching off the [Apple Watch Series 2][apple-watch-serie-2] and the Apple iPhone 14 Pro Max did not solve the problem.
2. [Forcing](https://www.verizon.com/support/knowledge-base-220564/ "Apple Watch - Force-Quit Apps") the [Now Playing][watchos-now-playing] app to quit did not solve the problem.
3. Toggling the **Auto-Launch Audio Apps** option OFF and then back ON, in the Watch app on the iPhone, under Settings > General > Wake Screen did not solve the problem.
4. [Deleting](https://www.myhealthyapple.com/now-playing-app-not-working-on-apple-watch-lets-fix-it/ "Delete and re-install the Now Playing app") and re-installing the Now Playing app did not solve the problem.
5. [Unpairing](https://support.apple.com/en-us/108372 "Unpairing your Apple Watch restores it to its factory settings") the [Apple Watch Series 2][apple-watch-serie-2] and restoring it to its factory settings did not solve the problem.

### Some Online Bug Reports 🐛

1. [Now playing on Apple Watch not working after update](https://discussions.apple.com/thread/254765567?sortBy=newest_first#260320368022 "Now playing on Apple Watch not working after update")
2. [Apple Watch’s Now Playing Issue](https://discussions.apple.com/thread/252833238?sortBy=newest_first "Apple Watch’s Now Playing Issue")
3. [Now Playing State Not Updating on Apple Watch](https://forums.developer.apple.com/forums/thread/728212 "NowPlaying State Not Updating on Apple Watch")
4. [Apple watch crown does not regulate volume in Now Playing after update](https://developer.apple.com/forums/thread/747224 "Apple watch crown does not regulate volume in Now Playing after update")
5. [Now playing Apple Watch 3 series not working after watchos 5 update. What to do?](https://discussions.apple.com/thread/8554444?sortBy=newest_first "Now playing Apple Watch 3 series not working after watchos 5 update. What to do?")
6. [Now playing on Apple Watch not working after update](https://discussions.apple.com/thread/254765567?&sortBy=newest_first "Now playing on Apple Watch not working after update")
7. ["Now Playing" App Not Working on Apple Watch](https://discussions.apple.com/thread/252650881?sortBy=newest_first "Now Playing App Not Working on Apple Watch")
8. [“Now playing” not working](https://www.reddit.com/r/iphone/comments/1bctibt/now_playing_not_working/)
9. [My Apple Watch running watchOS 6.3 no longer displays my iPhone in the 'Now Playing'](https://twitter.com/andersofsydney/status/1772182546635243523 "My Apple Watch running watchOS 6.3 no longer displays my iPhone in the 'Now Playing'")
10. [Now Playing app stopped working on Apple Watch ⌚ after upgrading iPhone to iOS 17.4 ⁉️](https://apple.stackexchange.com/q/471485/96921 "Now Playing app stopped working on Apple Watch ⌚ after upgrading iPhone to iOS 17.4 ⁉️")
11. [iOS 17.4: Now Playing not working on Apple Watch](https://gist.github.com/JV-conseil/55b94bcb5f5e79084d786476a956718f "iOS 17.4: Now Playing not working on Apple Watch")

### _Update March 21, 2024_

The release of [iOS 17.4.1][ios-1741] on March 21, 2024 did not solve the problem 🙅🏻

### _Update May 13, 2024_

The release of [iOS 17.5][ios-175] on May 13, 2024 did not solve the problem 🙅🏻

### _..._

### _Update December 12, 2024_

The release of [iOS 18.2][ios-182] on December 12, 2024 solved the problem 279 days after initial report ✅

<!-- links -->

[apple-watch-serie-2]: https://support.apple.com/en-us/112022
[ios-1741]: https://support.apple.com/en-us/118723#a1741
[ios-175]: https://support.apple.com/en-us/118723#a175
[ios-176]: https://support.apple.com/en-us/118723#a176
[ios-177]: https://support.apple.com/en-us/118723#a177
[ios-18]: https://support.apple.com/en-us/121161#a18
[ios-182]: https://support.apple.com/en-us/121161#a182
[watchos-now-playing]: https://support.apple.com/guide/watch/now-playing-apd4ea5db227/6.0/watchos/6.0
