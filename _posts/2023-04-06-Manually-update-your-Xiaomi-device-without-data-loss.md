---
title: Manually update your Xiaomi device without data loss
date: 2023-04-06 12:00:00 +0100
categories: [Guide, Smartphone]
tags: [xiaomi, update, how to]
toc: false
---

**Quick Fix if you don’t want to read the full story:** Jump [here](#how-to)

# Some background story

It already happened to me twice. My trusty Xiaomi Redmi Note 9 Pro (EU Version) got a new update and something didn’t work anymore. I got a problem, where the phone will crash sometimes when an App is using some GPS. Because I use a lot of public transportation here in Germany and also some Apps like Snapchat this crash happens at least twice a day. I could reduce it a bit by removing the permission to use the GPS functionality for these apps but this wasn’t the ultimate solution.

So I tried the obvious: Contact support, give feedback, generate logs to see if I’m intelligent enough to find out what the problem is and search on Google but nothing helped me. The only solution I could find was “Go ahead and reset your phone. The update broke something”.

But without a proper backup solution and the bootloader not being unlocked (which would have made it possible to do better backups) I really didn’t want to do that. There is so much stuff on my phone and I do not have the patience right now to set everything up again.

What was my solution then? Just wait. Wait and hope, that Xiaomi will release an update very soon that fixes the problem. Weeks passed, months passed but nothing happened. My phone was on Version 13.0.2.0 EU Stable and didn’t get any update.

After some time I remembered an app, which told me if my phone will get the MIUI 13 update and even listed all the updates and current versions for pretty much every Xiaomi phone. So I gave it a try and what did I see? The latest MIUI stable version for the EU region was 13.0.5.0. So there WAS an update for my device but I just didn’t get it. Why? I still have no idea. I thought maybe some waiting list but in the meanwhile, there was already version 13.0.4.0 and I didn’t get any of them.

The app also provides download links to the updates but I still didn’t want to reset my phone for that. And I thought this was mandatory but it turned out to be NOT!

It is possible and super easy to install downloaded updates on Xiaomi phones without the need for a reset. (For a “how to” jump to here). So I downloaded the latest version 13.0.5.0 as the “OTA” version. (This means it only contains the changes for the update and is published directly to the phones “Over the air”). I went to the settings to install the update and BOOM! It didn’t work :). I always got a “ROM package error” and that was it. But I also noticed that in the app there was a note that this version can only be applied to version 13.0.4.0 but as you might remember I had 13.0.2.0 and unfortunately there was no OTA version for 13.0.4.0 available. Just “Recovery” and “Fastboot” (I will not go into detail here but basically these are full system images of the MIUI system).

Again I didn’t want to go any further because I thought that this might reset my phone because the setting for installing downloaded updates is usually only used for OTA updates. After some time and no other option, I just took the risk of my phone being completely factory reset. I downloaded the recovery image, selected it for installation, and clicked on “YES, Install”. The phone turned off, the update got installed and it turned back on. I had the fear of my phone is like brand new all the time in my head but then: I saw my lock screen, my apps, and all my data. Everything was there. It was like installing a genuine update directly from the settings. Amazing! But I was only on version 13.0.4.0. So I tried to install the OTA version of 13.0.5.0 which I downloaded before and this one worked too. I successfully updated my phone to the newest version with updates manually downloaded from Xiaomi’s servers. And this only took about 5 minutes.

I had all this fear, all these thoughts because usually you cannot simply download a system image and install it without any hassle. For this, I didn’t even need a PC. Great job Xiaomi!

# How To
**_Disclaimer: This process will NOT delete ANY user data or installed apps. BUT just like with any ordinary update, there can happen unexpected things that could lead to data loss. You have been warned!_**

The secret sauce to all this is this amazing App: [MIUI Downloader](https://play.google.com/store/apps/details?id=com.famametric.miui)

It lets you really easily see the newest version, download it, and even get some information about upcoming updates.

## 1. Download the system image
1. Open the app
2. Choose your phone from the list
3. Choose the “MIUI Stable” tile
4. Select the version of your phone. For that, you can compare the letters in the version number with the ones in your system settings under “About phone” > MIUI version
5. Download the OTA or Recovery version you want. (You can choose the “Older Versions” button to download (obviously) older versions)
6. After the download is finished, move the downloaded ZIP file to your internal storage. It is not allowed to keep it inside the Downloads folder or in any other folder at all.

| --------------------------------------------- | --------------------------------------------- | --------------------------------------------- | --------------------------------------------- |
| ![Desktop View](/assets/img/2023-04-06/1.png) | ![Desktop View](/assets/img/2023-04-06/2.png) | ![Desktop View](/assets/img/2023-04-06/3.png) | ![Desktop View](/assets/img/2023-04-06/4.png) |

## 2. Activate additional features
In order to see the option in the next step, you have to enable “additional features”

1. Open your system settings
2. Go to “About phone” > The big MIUI version tile in the top left corner
3. Now click several times on the big number in the middle of the screen. After some time you will see a success message

| --------------------------------------------- | --------------------------------------------- | --------------------------------------------- |
| ![Desktop View](/assets/img/2023-04-06/5.png) | ![Desktop View](/assets/img/2023-04-06/6.png) | ![Desktop View](/assets/img/2023-04-06/7.png) |

## 3. Install the update
1. On the same screen click on the three dots
2. Select “Choose update package”
3. Select the downloaded ZIP file.
4. Wait for the verification and click “Install”

| --------------------------------------------- | --------------------------------------------- | ---------------------------------------------- |
| ![Desktop View](/assets/img/2023-04-06/8.png) | ![Desktop View](/assets/img/2023-04-06/9.png) | ![Desktop View](/assets/img/2023-04-06/10.png) |

## 4. Be happy
Thats it. That’s all you need to do. Now just wait for the update to finish and you will get the new features and bug fixes. Enjoy!