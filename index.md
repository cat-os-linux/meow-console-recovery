# Cat OS Meow Console Recovery download

Coming Soon!

## Requirements to Recover the system

`OS: Windows 10, Mac OS, Chrome OS 
Apps: Rufus or Chrome Recovery Utility
Removable Devices: Meow Expansion Card (has a MicroSD Card Port for Recovery), SD Card, USB Drive, MicroSD Card.`

## Meow Portable Recovery Requirements

`OS: Windows 10, Mac OS, Chrome OS, Linux Fedora based Distros, Linux Debian and Ubuntu based distros
Apps: Rufus, Chrome Recovery Utility, or Cat OS Recovery Tool
Removable Devices: Same as Meow Classic, Expansion Card and USB Devices are not supported

How to recover Meow Portable

Step 1: Start the Cat OS Recovery Tool (ONLY ON WINDOWS 10, LINUX FEDORA BASED DISTROS, AND LINUX UBUNTU AND DEBIAN BASED DISTROS)
Step 1 on Mac: Download the Cat OS Recovery Terminal and run `./MeowPortable_Terminal.sh` Which requires the drivers for Mac. See [here](https://github.com/cat-os-linux/meow-console-recovery/wiki/Mac-Drivers)
Step 2: Go to (username)>My Cat OS Devices>Portable Consoles
Step 3: Click **Meow Portable (mpclassic-modelair)** also known as Meow Portable Revision 0 (The Pre-revision models)
Step 4: It'll show 4 options. Recover to Ubuntu Touch (enables touchscreen, not recommended), Recover to Ubuntu (enables touch, recommended for debugging your games), Recover to Air OS aka Meow Portable 1 OS (recommended, enables touch), Recover to Leopard OS aka Meow Classic OS (recommended for testing Meow Portable Compatibility, touchscreen is disabled by default on games can be enabled via updates to game, enabled by default on the Menu and default Meow OS compatible apps)
Steps 3 and 4 on Mac: Type down devices and you'll see the same device from Step 3 (Windows, Linux) and then type mpclassic-modelair and then the same 4 options from Step 4 (Windows, Linux)
Step 5: Click **Recover to Air OS (complete data and hardware reset, data is saved to the cloud to access it later)** and click **Yes**
Step 5 on Mac: Type air-os-recovery and press enter and When you see a prompt Are you sure that you want to Recover Air OS onto your mpclassic-modelair?: Type Y

I'd recommend recovery if you screwed with the firmware or software or if your Meow Portable was bricked by the latest update. If it says _Could not recover Error Code: XX_ that means something screwed up.`

### The Error Codes (Meow Portable Only)

`00: Something on our side screwed up and the Recovery Image servers went down.
01: You have a 7GB or under, MicroSD Card or SD Card
02: Your device isn't in Recovery Mode. Press **A + Power Button + Vol Up** and you'll see that Recovery Mode was enabled! You should see Plug your device into your computer or Insert an SD Card or MicroSD Card, if you didn't mean to end up here. Press Power button, for more recovery options like Unlocking the firmware press X
03: Your device has a Different BIOS and Firmware and Can't find recovery mode! What did you do? DELETE THE DANG AIR OS PARTITONS!?!?!
04: Your device's (number between 1 to 16)GB Hard Drive or Soild State Drive isn't supported, Please get one thats at least 1TB as recovery is 16GB on the SSD and HD. For SD Cards and MicroSD Cards, The files are added onto that and will do the same process.
05: This is not a supported image of Ubuntu. Your Device supports 16.04+
06: We found a critical bug in your system, it may not recover if you continue recovery. It'll probably brick itself. Please wait for an update and refer to the manual
07: Device is bricked fully, I'd recommend to get a new one.
08: unknown-error What? HOW DID AN UNKNOWN ERROR GET HERE!?!?! Are you using a USB-C Cable to recover this thing or a B to C dongle? As we don't support dongles.
09: Your USB has been unplugged during the process, your Meow Portable may have been bricked. It's rare though.
10: How did you screw up that badly that you used an illegal image. I got eyes on you now. I scan every image.`

#### (C)Cat OS 2018-2020

