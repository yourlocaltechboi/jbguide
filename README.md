# Beginner's Guide to iOS Jailbreaking
> A guide by Anden Wieseler

So you’ve asked for my help in jailbreaking your iPhone, iPad, or iPod touch? Do you just want to learn about it?

Wonderful choice!

This document is a guide for how to do it both safely, and without error. If you just want to learn, feel free to read the first two sections and their subsections :) !

**A few notes before we begin:**
* **_If this is your first time jailbreaking, make sure to follow these instructions precisely to prevent unforeseen issues that could arise_**
* **_If you jailbreak your phone, you agree that your warranty (if any), will be void, and some repair centers may refuse to service your phone if it is jailbroken (see the section about repairing your phone for more info)_**
* **_I, Anden Wieseler, cannot be held liable for any issues that arise from jailbreaking any device from the use of this guide, any of the methods mentioned, or any of the software or hardware required. Your device is your responsibility. While I may provide some support, you jailbreak your phone at your own risk, and any fees or legal action is your responsibility as well._**

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
Supports the iPhone 5s (A5 chip) up to the iPhone X (A11 chip)|Supports the iPhone 5 (A5 chip) up to the latest generation of iPhones (at the time of writing, this is the iPhone 11 series, A13 chip)
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

**_Note: Linux users, skip this part. I will explain how to run checkra1n on Ubuntu based distros in the next section_**

For unc0ver users:
* If you dont have it installed already, install iTunes from https://www.apple.com/itunes

**_Note: Windows users: make sure you download the Win32 version, not the Microsoft Store version_**

**_Note: macOS Catalina users: iTunes was removed from macOS Catalina. Just skip this step._**

* Go to https://altstore.io to download and install AltServer on your machine.
* Go to https://unc0ver.dev and download the latest version of unc0ver. For easy access, save it to your Downloads folder.

## Section V: Installing your jailbreak tool

Congrats if you've made it this far! Now things are gonna get real, so make sure to pay attention, and read all of the side notes!

### Section V-a: Installing checkra1n

For simplicity, I will split this up into macOS and Linux parts. If you are using unc0ver, feel free to skip this part!

#### Section V-a1: Installing checkra1n on macOS

On macOS, all you have to do is open the DMG file you got from the checkra1n website, and drag it into your Applications folder. Easy!

#### Section V-a2: Installing checkra1n on Linux

Linux users, due to the vastness of possibilities for the linux community, I cannot cover all of you in this document. I will only be writing out the steps for Debian based distros.

On Ubuntu, open the terminal.

First, run `sudo apt get update && sudo apt-get upgrade` to make sure tat your packages are up to date.

Next, run `echo "deb https://assets.checkra.in/debian/" | sudo tee -a /etc/apt/sources.list` to add the checkra1n APT repo

Then, add the public key: `sudo apt-key adv --fetch-keys https://assets.checkra.in/debian/archive.key`

Then, run `sudo apt-get update` to refresh your package lists

and Finally, run `sudo apt-get install checkra1n` to install the checkra1n application.
