---
title: Booting into Hekate
description: A guide designed to get you started with yuzu quickly.
---

## Table of Contents

* [Introduction](../../index.md)
* [Prerequisites](../1-prerequisites/index.md)
* [Preparing the microSD Card](../2-prepare-sd-card/index.md)
* [Booting into RCM](../3-boot-to-rcm/index.md)
* **Booting into Hekate**
* [Dumping Decryption Keys](../5-dump-keys/index.md)
* [Backing up Switch NAND](../6-nand-backup/index.md)
* [Dumping System Update Firmware](../7-dump-firmware/index.md)
* [Dumping Games](../8-dump-games/index.md)
* [Dumping Save Files](../9-dump-saves/index.md)
* [Rebooting the Switch Back to its Original State](../10-reboot-to-stock/index.md)
* [Running yuzu](11-running-yuzu/index.md)
* [Mounting the microSD card to your computer in Hekate](../hekate-ums/index.md)

## Booting into Hekate

We will now boot your Nintendo Switch into Hekate, a custom bootloader.

1. Extract the `hekate_ctcaer_X.X.X.bin` file from the `hekate_ctcaer_X.X.X_Nyx_X.X.X.zip` file you downloaded from the prerequisites to any accessible directory on your computer.
2. Run TegraRcmGUI. In the `Payload` tab of TegraRcmGUI, click on the folder icon and navigate to the `hekate_ctcaer_X.X.X.bin` file you extracted earlier.
3. Click on `Inject Payload` and your Switch will boot into the Hekate menu.
