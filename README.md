# Guide to Install Ubuntu on a Windows Computer  


In this guide, I will summarize the steps taken in [TheAlternative.ch](https://thealternative.ch/guides/install.php) to prepare a USB stick to install Ubuntu 20.04 LTS on a Windows PC by freeing you from Windows :)  
This guide is by no means genuine. It is thought to be a patchwork of different guides and hints I've gathered to help my future self install Linux *again* due to __painful__ errors or new PCs.  

## USB Stick preparation  
- Download [Ubuntu 20.04 LTS](https://releases.ubuntu.com/20.04/ubuntu-20.04.4-desktop-amd64.iso) from [here](https://releases.ubuntu.com/20.04/). Select *Desktop Image*.  
- Download [Rufus](https://github.com/pbatard/rufus/releases/download/v3.19/rufus-3.19.exe) from [here](https://rufus.ie/en/). (Rufus will be used for flashing the image on the USB disk.)  
- Launch Rufus. Use default settings. (Partition scheme: MBR, Target System: BIOS or UEFI, File System: FAT32, Cluster Size: 16 KB)
- Select your USB disk. Select the downloaded .iso file.
- Press START. Select Recommended option *Write in ISO Image mode`. It will take a while to flash files in the USB disk.
- Search in internet what key should be used to open BIOS settings/startup device. For Dell it is F12 and for Lenovo it is Enter.
- Restart your computer and during booting tap rapidly on the button that was found in the last step
- Select your USB disk as startup option. This will lead you to the Grub screen, where you should choose Ubuntu. This will start Ubuntu on your PC using the USB disk. This step might take a while.
- Now you have a *Welcome* page open. Select the language on the left bar you would like to proceed with and tap *Install Ubuntu*


## Install Ubuntu 20.04 LTS

## Install useful software  

## Notes for myself  

- Python
- Dart/Flutter, Android Studio, Android Debugger Bridge
- Visual Studio Code  
- GCC, Make, CMake
