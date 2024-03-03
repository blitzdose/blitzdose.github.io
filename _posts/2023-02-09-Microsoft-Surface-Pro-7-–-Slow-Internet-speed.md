---
title: Microsoft Surface Pro 7 – Slow Internet speed
date: 2023-02-09 12:00:00 +0100
categories: [Quick Fix, Network]
tags: [surface, microsoft, slow internet]
toc: false
---

**Quick Fix if you don’t want to read the full story:** Change the setting in your router to prioritize the network traffic coming from your Surface.

Today I want to share my experience with my Surface Pro 7 and its insanely slow internet speed. I have an ISP that gives me a connection speed of 500 Mbit/s download and 50 Mbit/s upload. I got this speed on any network device, except my Surface. There I was limited to around 25 Mbit/s download and upload. Many guides suggested that I should try installing a different driver, updating my drivers, or changing some options in the “Advanced” Tab for the interface adapter. But guess what: None of this helped 🙂

I also noticed, that all the other people having this issue only mentioned the WiFi connection. I had this problem with WiFi as well as a wired connection with a generic USB to RJ45 Adapter from Amazon. Even stranger was the fact, that the issue only applied to the surface when it was in my home network. At university, I got the full speed (Still kinda slow but that was not the problem with my Surface). So the issue has to do something with my home network? But all the other devices are working fine…

Another weird behavior I noticed was, that the Surface had an excellent connection to my home NAS. Full 1 GBit/s even over WiFi. So the slow speed only occurred to traffic that left my home network.

After some more troubleshooting, I decided to fully reset my Surface. Got a recovery USB ready and reinstalled the whole thing and guess what: It still featured the same problem.

So finally I took a look at my home network. I’m running a FritzBox at home (after way too much trouble with the router from my ISP) and took a look if maybe I could find something that would indicate why my Surface is so slow. I found not much and the only option I could activate for the Surface was “Prioritize this device”. This option is normally used when the connection to the outside world is maxed out and you want packets from a specific device to have priority. My network is definitely not at its maximum but I thought I give it a shot. And BOOM! I got the full 500 Mbit/s on my Surface! Nice! But wait? Why? Why must the device be prioritized to get full speed? I honestly have absolutely no idea. It doesn’t make sense to me at all. But I’m happy that everything works fine and I hope you can fix your problem too if you have the same issue. If you have any idea why this is working please let me know.

See you next time

Christian
