---
title: Booting into RCM
description: A guide designed to get you started with yuzu quickly.
---

## Table of Contents

* [Introduction](../../index.md)
* [Prerequisites](../1-prerequisites/index.md)
* [Preparing the microSD Card](../2-prepare-sd-card/index.md)
* **Booting into RCM**
* [Booting into Hekate](../4-boot-to-hekate/index.md)
* [Dumping Decryption Keys](../5-dump-keys/index.md)
* [Backing up Switch NAND](../6-nand-backup/index.md)
* [Dumping System Update Firmware](../7-dump-firmware/index.md)
* [Dumping Games](../8-dump-games/index.md)
* [Dumping Save Files](../9-dump-saves/index.md)
* [Rebooting the Switch Back to its Original State](../10-reboot-to-stock/index.md)
* [Running yuzu](11-running-yuzu/index.md)
* [Mounting the microSD card to your computer in Hekate](../hekate-ums/index.md)

## Booting into RCM

We will now boot your Nintendo Switch into RCM mode.

1. Run the TegraRcmGUI installer you downloaded from the prerequisites, and after installation, start the program. 
2. In the `Settings` tab, click on `Install Driver` which will install the drivers necessary for your computer to interface with your Nintendo Switch. 
3. After the drivers have been installed, plug your Nintendo Switch into your computer.
4. Power off your Switch while it is still connected to your computer.
5. Insert your RCM jig into the right joy-con slot, make sure it is seated securely at the base, and then press VOL+ and Power buttons at the same time. Nothing should happen on your Switch; if the switch starts to turn on normally, go back to the beginning of step 2d and try again.
6. If you see the Nintendo Switch icon in the lower left corner flash green and state `RCM O.K.`, your switch has successfully entered RCM mode.
