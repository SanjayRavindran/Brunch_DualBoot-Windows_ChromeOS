# GrubBrunch_DualBoot

I have made this because I like to have a barebone GRUB as my bootloader. So I have copied the EFI folder from the Full Install disk of the ChromeOS EFI-partition which I have Installed using brunch (https://github.com/sebanc/brunch).

## Usage

When you are make a Dual boot (https://github.com/sebanc/brunch#dual-boot-chromeos-from-your-hdd) of chromeOS with windows then this will be helpful.

## How To Use

- Install the Windows 10 (As of creating this I used Windows 10 build-2004) 
- Then make a partition above 14GB or above (Usage of EXT4 as FileSystem which you can make using live Linux USB is recommended by me) and install ChromeOS by follow the Brunch guide (https://github.com/sebanc/brunch#dual-boot-chromeos-from-your-hdd).
- Create a partion of atleat 10MB in FAT filesytem format for place the above "efi" folder.
- Most of the modern motherboard will be capable of recogonizing this. If you motherboard does not recogonize that just use "efibootmgr" in Linux to fix that(Video Link given below).

## Video links



## Credits
A Huge thanks to
- Google For ChromeOS
- [Brunch Developers](https://github.com/sebanc/brunch "Brunch Developers title")
