---
title: Dumping Decryption Keys
description: A guide designed to get you started with yuzu quickly.
---

## Table of Contents

* [Introduction](/quickstart/)
* [Prerequisites](/quickstart/prerequisites/)
* [Preparing the microSD Card](/quickstart/prepare-sd-card/)
* [Booting into RCM](/quickstart/boot-to-rcm/)
* [Booting into Hekate](/quickstart/boot-to-hekate/)
* [**Dumping Decryption Keys**](/quickstart/dump-keys/)
* [Backing up Switch NAND](/quickstart/nand-backup/)
* [Dumping System Update Firmware](/quickstart/dump-firmware/)
* [Dumping Games](/quickstart/dump-games/)
* [Dumping Save Files](/quickstart/dump-saves/)
* [Rebooting the Switch Back to its Original State](/quickstart/reboot-to-stock/)
* [Running yuzu](/quickstart/running-yuzu/)
* [Mounting the microSD card to your computer in Hekate](/quickstart/hekate-ums/)
## Dumping Decryption Keys

We will now dump your `prod.keys` and `title.keys` for decryption of your game files.

1. Boot your Nintendo Switch into [RCM mode](#booting-into-rcm) (steps 2c. to 2f.) and make sure it is connected to your computer.
2. Boot into [Hekate](#booting-into-hekate) (steps 3b. to 3c.)
3. When it has successfully booted into the Hekate menu, tap on `Payloads`. This will show a list of payloads.
4. Tap on `Lockpick_RCM.bin` in the list of payloads.
5. After Lockpick_RCM has successfully booted, press the power button to select `Dump from SysNAND`. 
6. It will automatically boot to sept and start deriving the keys. Wait for it to finish deriving the keys.
7. After Lockpick_RCM has finished deriving the keys, please make note of the location of the key files. Default is: `sd:/switch/prod.keys` and `sd:/switch/title.keys`.
8. Press any button to return to the menu, then navigate with the VOL+/VOL- buttons to highlight and select `Payloads...` by pressing the power button.
9. Select `reboot_payload.bin` from the list of payloads. You should now be booted back into Hekate.
10. [Mount the SD card to your computer in Hekate](#mounting-the-microsd-card-to-your-computer-in-hekate) (steps 4a. to 4c.)
11. Navigate to your SD card drive and copy both `prod.keys` and `title.keys` to the `%YUZU_DIR%/keys` directory.
12. Once you're done copying, [safely eject the SD card drive in your computer and return to the Hekate Home menu.](#mounting-the-microsd-card-to-your-computer-in-hekate) (steps 5a. to 5b.)
