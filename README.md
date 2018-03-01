# delectra
An uninstaller script for Coolstars' [Electra](https://github.com/coolstar/electra) iOS 11.0 - 11.1.2 jailbreak.
Please read everything in this readme before you do anything!

[Dowload link](https://dbr.ee/AIUe)
or
[Download from repo](https://raw.githubusercontent.com/KirovAir/delectra/master/unjailbreak.sh)

## Why?!
SemiRestore11 is not released yet and I wanted to revert the JB. (b10 was a lot more stable for me)
I followed all filesystem changes from the jailbreak bootstrap files and electra source code and added those to the unjailbreak.sh script. This should undo everything done by the installer, __except the APFS snapshot.__ (So SemiRestore11 should still work when it comes out.)

!! DO NOT USE THIS IF YOU DON'T KNOW WHAT YOU ARE DOING !!
This is not recommended by Coolstar or even myself.

## How to use?
!! First of all, this has only been tested on MY device. USE AT YOUR OWN RISK !!
1. Uninstall ALL user installed tweaks.
2. Put unjailbreak.sh on your phone. (I'd recommend putting it in /electra so it will be removed by itself)
3. SSH into your phone as __root__ and run unjailbreak.sh from this repo:
```
cd /electra
sh unjailbreak.sh
```
4. Wait until the device reboots and then reboot again.

## My tweaks are not working on the betas anymore?!
This was an issue when you used an older version of this script. This is fixed now.
1. SSH into your phone as __root__ and run:
```
mkdir /Library/Frameworks/
```
2. Reboot and re-jailbreak with a beta electra version and it should be fixed.

## User reports
After a night of reports coming in there is someone on a iPhone 6s that reported it bootlooped his device. He was on iOS 11.1.2 after a futurerestore from 10.1.1. 
I need to investigate what the issue is, but simply avoid this if you have futurerestored to be sure.

Wait for SemiRestore to avoid any risk at all since I can _NOT_ guarantee a successful uninstall. Every system is different after multiple tweak installations so make sure you remove every tweak you have installed to be as stock as possible.
