---
title: Preparing the microSD Card
description: A guide designed to get you started with yuzu quickly.
---

## Table of Contents

* [Introduction](../../index.md)
* [Prerequisites](../1-prerequisites/index.md)
* **Preparing the microSD Card**
* [Booting into RCM](../3-boot-to-rcm/index.md)
* [Booting into Hekate](../4-boot-to-hekate/index.md)
* [Dumping Decryption Keys](../5-dump-keys/index.md)
* [Backing up Switch NAND](../6-nand-backup/index.md)
* [Dumping System Update Firmware](../7-dump-firmware/index.md)
* [Dumping Games](../8-dump-games/index.md)
* [Dumping Save Files](../9-dump-saves/index.md)
* [Rebooting the Switch Back to its Original State](../10-reboot-to-stock/index.md)
* [Running yuzu](11-running-yuzu/index.md)
* [Mounting the microSD card to your computer in Hekate](../hekate-ums/index.md)

## Preparing the microSD Card

We will now prepare the microSD card.

1. Extract the contents inside the `atmosphere-X.X.X-master-XXXXXXXX+hbl-X.X.X+hbmenu-X.X.X.zip` and `hekate_ctcaer_X.X.X_Nyx_X.X.X.zip` files into the root of your microSD card. Just drag and drop the contents, do not create any new folders.
2. Rename the `hekate_ctcaer_X.X.X.bin` file to `reboot_payload.bin` and move it into the `atmosphere` folder. Replace the file when prompted.
3. Place the `fusee-primary.bin`, `Lockpick_RCM.bin` and `TegraExplorer.bin` files into the `payloads` folder, which is inside the `bootloader` folder in your microSD card.
4. Create a folder named `nxdumptool` within the `switch` folder of your SD card and place the `nxdumptool.nro` file inside it.
5. Once done, eject the microSD card and insert it into your Nintendo Switch.

{{< imgs
    "./sd_template.png|Your SD card should look like this."
>}}
