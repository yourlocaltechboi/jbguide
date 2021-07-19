# Beginner's Guide to iOS Jailbreaking
> A guide by Anden Wieseler

So you’ve asked for my help in jailbreaking your iPhone, iPad, or iPod touch? Do you just want to learn about it?

Wonderful choice!

This document is a guide for how to do it both safely, and without error. If you just want to learn, feel free to read the first two sections and their subsections :) !

**A few notes before we begin:**
* **_If this is your first time jailbreaking, make sure to follow these instructions precisely to prevent unforeseen issues that could arise_**
* **_If you jailbreak your phone, you agree that your warranty (if any), will be void, and some repair centers may refuse to service your phone if it is jailbroken (see the section about repairing your phone for more info)_**
* **_I, Anden Wieseler, cannot be held liable for any issues that arise from jailbreaking any device from the use of this guide, any of the methods mentioned, or any of the software or hardware required. Your device is your responsibility. While I may provide some support, you jailbreak your phone at your own risk, and any fees or legal repurcussions are your responsibility as well._**
* **_I cannot guarantee that all information contained in this document is without error. Should technical error arise from false information, I cannot and will not be held accountable. By continuing, you accept full responsibility for any errors that may arise. If you see an error in this document that you can fix, feel free to edit this document on GitHub and send in a PR!_**

* **_This guide has not been updated in a while, however as of July of 2021, the steps required to jailbreak remain similar. Please substitute the jailbreak tools and tweaks mentioned in this guide with their modern counterparts. In terms of Jailbreaks, this is Taurine and unc0ver (semi-untethered), and checkra1n (semi-tehtered)._**

If you agree to these terms, let's move forward! 


## Section I: Introduction to Jailbreaking

### Section I-a: What is a jailbreak?

A jailbreak refers to exploiting a vulnerabilty in iOS/iPadOS code that allows for access to parts of the system that Apple usually wouldnt allow, and allows users to install different 3rd party programs and binaries from outside of the Apple App Store.

Jailbreaks are based on exploited vulnerabilities in the operating system itself. These vulnerabilities are found by iOS security researchers who report the bugs to Apple, to help make iOS and iPadOS more secure.

### Section I-b: What is the purpose of a jailbreak?

iOS Jailbreaking has a couple different purposes.

Typically, users will jailbreak their devices to customize their devices in a way that stock iOS won't allow. In fact, many jailbreak tweaks go on to become real features in future iOS and iPadOS updates (even though Apple won't admit that).

### Section I-c: Is it safe to do?

Jailbreaking an iOS device, in itself, is typically safe. What you do with your jailbreak will determine if your device stays secure. Typically this means only installing trusted repos and tweaks, and changing the root password on your device, so hackers have a harder time of trying to hack your phone and stealing your data. Think of it like any other computer.

### Section I-d: Is it legal?

As of right now, yes. Jailbreaking was deemed legal in a DMCA exemption in 2009 and has been renewed since.

**Note that piracy, even when done using a jailbreak, is still illegal**

### Section I-e: So you've talked about so-called "tweaks" and "repos". What are they?

When you jailbreak your device, a new application is installed; a package manager. On most modern jailbreaks, this package manager is called Cydia (which literally means "worm in the apple"). Think of this like your jailbreak app store. There's something different about this app store though. You can get your apps (Tweaks in this case) from many different sources. These are called repositories (or repos for short). Inside these repositories are tweaks. Tweaks are 3rd party binaries made by developers that change parts of the system to do different things. Some are free, and some you have to pay for, just like any other software.

## Section II: Types of jailbreaks

So you know what a jailbreak is, but now you're probably wondering, "how do you do it?"

Well, there are different types of jailbreaks. Different types of jailbreaks are applied in different ways. See the table below.

Type of Jailbreak|What it means
---|---
Untethered|This type of jailbreak is usually executed from a computer, but your jailbreak will stay applied betweeen device reboots; **This type of jailbreak is not that common anymore**.
Psuedo-untethered|This type of jailbreak involves sideloading an app to your device, and applying the jailbreak from the app, then installing a package that will allow you to run the jailbreak every time the device is booted, giving the illusion of an untethered jailbreak; **This type of jailbreak is not very common**.
Tethered|This type of jailbreak involves installing custom firmware to the device, and using a computer to boot the phone; **This type of jailbreak is not very common anymore**.
Semi-tethered|This type of jailbreak requires a computer to boot the device jailbroken, but the device will run unjailbroken just fine without a computer. **There are currently semi-tethered jailbreaks availible**
Semi-untethered|**This is the most common jailbreak type nowadays, and there are semi-untethered jailbreaks availible.** This type of jailbreak involves sideloading an app to the device and applying the jailbreak from the app. The jailbreak is unapplied if the device is rebooted, in which case the user can rejailbreak from the app.

## Section III: Picking your jailbreak tool

For the purposes of this guide, I will assume you are on iOS 13. Read through the jailbreak tools below, and pick which one you want to use.

**_Note: Not all devices are currently jailbreakable. If your device is not jailbreakable, make sure to turn off Automatic Updates in settings and DO NOT update your iOS version. Wait for a jailbreak to be released for the version you are already on. That's the jailbreak rule of thumb._**

checkra1n|unc0ver
---|---
Semi-tethered|Semi-untethered
Supports the iPhone 5s (A7 chip) up to the iPhone X (A11 chip)|Supports the iPhone 5s (A7 chip) up to the latest generation of iPhones (at the time of writing, this is the iPhone 11 series, A13 chip)
Supports iOS/iPadOS versions 12.3 and up|Supports iOS/iPadOS versions 11.0-13.3 (excluding 12.3-12.3.2 and 12.4.2-12.4.5)
Supports macOS and Linux|Requires AltStore, Which supports Windows 10 and macOS 10.14.4+
Actively Developed|Actively Developed

Decided which tool you want to use? Great.

## Section IV: Downloading your jailbreak tool.

Before you get started, you will need the following:

* A computer with the required OS installed (see above), and an account with administrator privileges
* Your iOS/iPadOS device (for best results, have the battery above 50%)
* A charging cable that supports data transfer
* A network connection

For checkra1n users, go to https://checkra.in, and download the latest version of checkra1n

**_Note: Linux users, skip this part. I will explain how to run checkra1n on Debian based distros in the next section_**

For unc0ver users:
* If you dont have it installed already, install iTunes from https://www.apple.com/itunes

**_Note: Windows users: make sure you download the Win32 version, not the Microsoft Store version_**

**_Note: macOS Catalina users: iTunes was removed from macOS Catalina. Just skip this step._**

* Go to https://altstore.io to download and install AltServer on your machine.

## Section V: Installing your jailbreak tool

Congrats if you've made it this far! Now things are gonna get real, so make sure to pay attention, and read all of the side notes!

### Section V-a: Installing checkra1n

For simplicity, I will split this up into macOS and Linux parts. If you are using unc0ver, feel free to skip this part!

#### Section V-a1: Installing checkra1n on macOS

On macOS, all you have to do is open the DMG file you got from the checkra1n website, and drag it into your Applications folder. Easy!

#### Section V-a2: Installing checkra1n on Linux

Linux users, due to the vastness of possibilities for the linux community, I cannot cover all of you in this document. I will only be writing out the steps for Debian based distros.

Okay. Let's open the terminal.

First, run `sudo apt get update && sudo apt-get upgrade` to make sure tat your packages are up to date.

Next, run `echo "deb https://assets.checkra.in/debian/" | sudo tee -a /etc/apt/sources.list` to add the checkra1n APT repo

Then, add the public key: `sudo apt-key adv --fetch-keys https://assets.checkra.in/debian/archive.key`

Then, run `sudo apt-get update` to refresh your package lists

and Finally, run `sudo apt-get install checkra1n` to install the checkra1n application.

### Section V-b: Installing unc0ver

Unc0ver installation is similar for both macOS and Windows.

1. Install AltServer on your computer using the instructions at https://altstore.io/faq
2. Once AltStore is installed on your device, leave the device plugged into the computer.
3. Open Safari on your device, and go to https://unc0ver.dev, and download the latest version. It will automatically put it in your downloads folder.
4. Open AltStore on your device, and sign in. 
5. On the "My Apps" page, tap the plus ("+")
6. Select the unc0ver application file
7. Wait for unc0ver to install

**_Note: You will have to refresh unc0ver once every 7 days to keep it running. You can do this by connecting your phone to your computer, starting AltServer, opening AltStore on the device, and pressing refresh on the "My Apps" page._**

## Section VI: Jailbreaking for the first time :)

YAY! It's almost time to jailbreak your phone for the first time! This is where you really need to focus. Have patience! You can do it!

### Section VI-a: Jailbreaking on checkra1n

To jailbreak using checkra1n:

1. Open the Checkra1n app on your computer
2. Plug in your device.
3. Press start
4. Follow the instructions to place the device in DFU mode
5. Wait for the device to reboot.
6. Once the device has booted, open the new checkra1n app on the device.
7. Install Cydia from the checkra1n mobile app
8. Verify that Cydia has installed by opening Cydia from the home screen
9. TA-DA! you are now officially the owner of a device jailbroken using checkra1n!

**_Note: you will have to redo all of these steps every time your device reboots in order to keep your jailbreak applied!_**

Skip to the next section for info about what to do next!

### Section VI-b: Jailbreaking on unc0ver

To apply the unc0ver jailbreak:

1. Make sure your device is unplugged from the computer
2. Open unc0ver
3. Press Jailbreak at the bottom
4. It will give a message saying that the system snapshot has been renamed. Allow the device to reboot.
5. Once the device has rebooted, open the unc0ver app
6. Press the Jailbreak button at the bottom again
7. Wait for the jailbreak to apply. This may take up to a minute in some cases
8. Allow the device to respring
9. Open Cydia to verify that the jailbreak was complete
10. TA-DA! You are now the proud owner of a device jailbroken using unc0ver!

**_Note: You will have to open the unc0ver app and re-jailbreak every time the device restarts_**

Read on to find out what to do next!

## Section VII: Post-install notes

Congratulations! You jailbroke your first device! That wasnt so bad, was it?

Just a few things to keep in mind:

* Make sure that you DO NOT under ANY CIRCUMSTANCES update your iOS version without properly removing your jailbreak first. Instructions for how to do this can be found below.

* Unc0ver users: remember to refresh your apps once every 7 days!

* Remember to re-apply your jailbreak after every reboot!

## Section VIII: What to do next

### Section VIII-a: Repos, Tweaks, and Themes, oh my!

Whats the point of jailbreaking your device if you don't install anything right?

Here are my reccomended tweaks to get started. You don't need to install any of the ones you don't want. They're just good ones to start with.

Tweak Name|Developer|Repo|Price
---|---|---|---
SnowBoard|SparkDev|sparkdev.me|Free
HomePlus Beta|Kritanta|repo.openpack.io|Free
Xen HTML|Matchstic|repo.packix.com|Free
XenInfo|JunesiPhone|junesiphone.com/supersecret|Free
Complications|Ben Giannis|repo.packix.com|$1.99
Axon|Nepeta & Baw Appie|repo.rpgfarm.com|Free
Jellyfish|Justin Proulx & Ayden Panhuyzen|repo.dynastic.co|$1.99
Prysm|LaughingQuoll|repo.packix.com|$3.49
Ultrasound|Ayden Panhuyzen|repo.dynastic.co|$1.99

**To add a source to Cydia:**

1. Open Cydia
2. Go to the sources page
3. Hit the edit button
4. Hit the add button
5. Enter the URL of the repo that you want to add, and hit "Add Source"

**_Note that tweak compatibility varies from device to device. Especially with iPads._**

## Section IX: Removing your jailbreak safely

Leaving so soon? Sad day. Anywho, follow these steps to safely remove your jailbreak from your device.

### Section IX-a: Removing the checkra1n jailbreak

To remove the checkra1n jailbreak:

1. Make sure you are jailbroken
2. Open the checkra1n app on your device
3. Press the restore system button
4. Wait for the process to complete
5. Reboot your device

### Section IX-b: Removing the unc0ver jailbreak

To remove the unc0ver jailbreak:

1. Reboot into a non-jailbroken state
2. Open the unc0ver app
3. Go to the settings menu
4. Flip the switch that says "Restore RootFS" on
5. Return to the main screen
6. Press the "Restore RootFS" button at the bottom
7. A notice will pop up saying that the filesystem will be restored. Allow this and continue
8. Once the process is complete, you will be asked to reboot your device. Allow this as well.
9. Once the device is rebooted, delete the unc0ver and AltStore apps.

## Section X: What to do if your phone needs repair

Whoops! You damaged your jailbroken device. Don't worry, we've been there.

Let's figure out our options.

If this describes your device|try this
---|---
My touchscreen still works, and I can open my jailbreak app from the home screen|Open the jailbreak app and remove your jailbreak using the steps above before sending your device in for repair
My touchscreen does NOT work, and/or I cannot open my jailbreak app|You will have to either reset the device via DFU mode in iTunes, or send in the device as-is and risk either a refusal of service or having your device returned wiped and updated to the latest version of iOS (potentially unjailbreakable).

**_Note to users under warranty: If you send in your device as-is, and Apple or your Repair Specialist discovers that your device is jailbroken, they might repair it, but you might have to pay out-of-warranty fees, as a jailbreak voids your warranty_**

## Section XI: Conclusion

If you read all of this, thank you for sticking with me!

If you are jailbroken and need support for your jailbroken device r/jailbreak on Reddit is a great resource.

To learn more about using tweaks to customize the look of your device, check out r/iOSThemes on Reddit as well.

If you found an error in this document, feel free to edit it and send in a PR on GitHub!

Thanks once again!

Anden out.
