# Hackintosh Configuration for Lenovo Thinkpad P50
> "I think you guys should study more and do more research." ———— The man who changed China.

<img align="right" src="https://github.com/Errrneist/Hackintosh-Thinkpad-P50/blob/master/img/monterey.png" alt="Critter" width="250">

#### Developer: [@Errrneist](https://www.tonymacx86.com/members/errrneist.1550861/)
#### Don't forget to star this project if you like it!
#### *Fork* this project to your own repository to make changes.

## Introduction
* This config is tested on macOS 12.2.1.
* This is a custom hackintosh configuration of Lenovo Thinkpad P50.
* Note that ths machine I used for macOS 12.2.1 is different than the one I used for 10.12.4.
* Newest Release: [RELEASE](https://github.com/wu-hongjun/Hackintosh-Thinkpad-P50/releases)

## Machine Configuration
* Intel i7-6820HQ 2.70Hz 4C8T
* 24GB DDR4 2133MHZ ECC SODIMM
* Intel HD Graphics 530 2048MB
* NVIDIA Quadro M1000M 2GB GDDR5 (Disabled)
* FHD 1080P 15' FlexView Screen
* 720P WebCam with Indicator Light
* Sandisk SD8TN8U256G1001 256G SATA SSD

## Instructions
### Before Everything
* To make life easier, you'll want to have another mac with you. 
  * You can do it without another mac, but that'll be complicated.
  * The main idea is simple, make a macOS installer usb drive and copy the EFI folder to the EFI partition of the USB drive.

### Make USB Drive
* First, download macOS 12 (Or later, but no promises if it still works) from Apple App Store.
* Then, follow [How to create a bootable installer for macOS](https://support.apple.com/en-us/HT201372) to create a macOS installer drive.
  * Essentially, go to Disk Utility - View - Show All Devices
  * Find your USB drive, right click, Erase.
  * <img width="806" alt="image" src="https://user-images.githubusercontent.com/27667864/157503018-83d94ca1-8242-49f2-9f08-7ee50cf52ebc.png">
  * Go to terminal, run `sudo /Applications/Install\ macOS\ Monterey.app/Contents/Resources/createinstallmedia --volume /Volumes/MyVolume`.
  * ![image](https://user-images.githubusercontent.com/27667864/157503150-a58185b1-0ac7-417f-8864-ff034210d1db.png)
  * Done! You have a bootable USB Drive with macOS installer.

### Install
* With the drive plugged in, boot the machine while pressing F12 many times until you see the boot selection screen.
* Select boot from your USB drive.
* OpenCore should launch, and select Install macOS.
* Install macOS as normal.
* If you have the exact same configuration as my system, everything should be working.

## Warning
* I do not have time to help others debug your system since I am not there, it's not my system, and I am not getting paid for it.
* If you run into bugs or cannot boot, it is always great to consult [TonyMacX86](https://www.tonymacx86.com).
* Running into issues is one of the must-haves to have a complete hackintosh experience. Enjoy ;)
* Use this configuration on your own risk as I am not responsibile for damaging anyone's system.

## Donate
* Donating to this project is optional as the intention of this project is build on each other's work and benefit everyone. 
* However, if you would like to buy me a coffee, you can do that using QR codes (WechatPay/AliPay or Venmo).
<img align="middle" src="https://github.com/Errrneist/Hackintosh-Razer-Blade-Advanced/blob/master/IMG/donate.png" alt="donate" width="800">

#### Happy hackintoshing!
### Errrneist.
