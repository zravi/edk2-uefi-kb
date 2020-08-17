# edk2-uefi-kb


**shell
- To access the UEFI menu, create a bootable USB media:
- Format a USB device in FAT32.
- Create a directory on the USB device:

- /efi/boot/
 
- Copy the file shell.efi to the directory created above. This file is attached to this article in shell.zip.
- Rename the file shell.efi to BOOTX64.efi
- Restart the system and enter the UEFI menu.
- Select the option to Boot from USB.
