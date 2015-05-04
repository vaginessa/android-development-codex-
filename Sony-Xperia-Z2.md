## Backup TA Partition DRM Keys

The TA Partition contains the DRM keys for your device, needed to utilize the proprietary Bravia Engine and camera optimization. You must make a backup: If you lose these, you will not be able to use these features.

## Rooting Android 5.0.2

http://forum.xda-developers.com/xperia-z2/development/stock-d6502-23-1-0-726-complete-guide-t3085893

## FTF Flashing for Rooted Phones

My Sony Xperia Z2 was already rooted (but still has locked bootloader engaged). I wanted to update to Android 5.0.2, but it now requires a special update method to retain root privileges.

1. Install [XZDualRecovery](http://forum.xda-developers.com/showthread.php?t=2785598).
2. Find an FTF for your device on [this XDA Thread.](http://forum.xda-developers.com/showthread.php?t=2759934)
  * You can use different customizations as long as the Model ID is the same (ex. on D6503, unbranded UK on branded phone, Hong Kong on Taiwan phone). Though if you do this, it might be advantageous to backup and wipe the phone first so you have a fresh start.
3. [Modify the FTF](http://forum.xda-developers.com/xperia-z2/general/4-4-4-creating-rooted-update-package-t2933155) to add root privileges, and prevent it from overwriting TA and PARTITION.