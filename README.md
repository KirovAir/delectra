# delectra
An full uninstaller script for Coolstars' [Electra](https://github.com/coolstar/electra) iOS 11.0 - 11.1.2 jailbreak.

## Why?!
SemiRestore11 is not released yet and I wanted to revert the JB.
I followed all filesystem changes from the jailbreak bootstrap files and electra source code and added those to the unjailbreak.sh script. This should undo everything done by the installer, except the apfs snapshot. (So SemiRestore11 should still work when it comes out.)

!! DO NOT USE THIS IF YOU DON'T KNOW WHAT YOU ARE DOING !!

## How to use?
!! First of all, this has only been tested on MY device. USE AT YOUR OWN RISK !!
1. Uninstall ALL user installed tweaks.
2. Put unjailbreak.sh on your phone. (I'd recommend /electra)
3. SSH into your phone as __root__ and run unjailbreak.sh from this repo:
```
ssh root@192.168.2.123
cd /electra
sh unjailbreak.sh
```
