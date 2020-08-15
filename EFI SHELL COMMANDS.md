EFI SHELL COMMANDS


Shell Boot Commands
==================================================

autoboot     -- View or set autoboot timeout variable
bcfg         -- Displays/modifies the driver/boot configuration
boottest     -- Set/View BootTest bits
clearlogs     -- Clears FPL and SEL logs
dblk         -- Displays the contents of blocks from a block device
lanboot     -- Performs boot over lan from EFI Shell
mount         -- Mounts a file system on a block device
reset         -- Resets the system
tftp         -- Tftp to a bootp/dhcp enabled unix boot server
vol         -- Displays volume information of the file system

Shell  Configuration Commands
==================================================

cpuconfig     -- Deconfigure or reconfigure cpus
date         -- Displays the current date or sets the systemdate
err         -- Displays or changes the error level
esiproc     -- Make an ESI call
errdump     -- View/Clear logs
info         -- Display hardware information
monarch     -- View or set the monarch processor
palproc     -- Make a PAL call
salproc     -- Make a SAL call
time         -- Displays the current time or sets the system time
ver         -- Displays the version information

Shell Device Commands
=================================================

baud         -- Set serial port com settings
connect     -- Binds an EFI driver to a device and starts the driver
devices     -- Displays the devices being managed by EFI drivers
devtree     -- Displays the tree of devices of the EFI Driver Model
disconnect     -- Disconnects one or more drivers from a device
dh         -- Displays the handles in the EFI environment
drivers     -- Displays the list of drivers of the EFI Driver Model
drvcfg         -- Invokes the Driver Configuration Protocol
drvdiag     -- Invokes the Driver Diagnostics Protocol
guid         -- Displays all the GUIDs in the EFI environment
lanaddress     -- Display LAN MAC addresses
load         -- Loads and optionally connected EFI drivers
loadpcirom     -- Loads a PCI Option ROM
map         -- Displays or defines mappings
openinfo     -- Displays the protocols on a handle and the agents
optload     -- Lists all optional ROM-based efi drivers and apps
pci         -- Displays PCI devices or PCI function config space
reconnect     -- Reconnects one or more drivers from a device
unload         -- Unloads a protocol image

Shell Memory Commands
=================================================

default         -- Sets, Resets, or Clears default NVM values
dmpstore     -- Displays all NVRAM variables
dmem         -- Displays the contents of memory
memmap         -- Displays the memory map
mm         -- Displays or modifies MEM/IO/PCI
pdt         -- View or set page deallocation table

Generic Shell Commands
===================================================

alias         -- Displays, creates, or deletes aliases in the EFI shell
attrib         -- Displays or changes the attributes of files or directories
cd         -- Displays or changes the current directory
cls         -- Clears the standard output with an optional background color
comp         -- Compares the contents of two files
cp         -- Copies one or more files/directories to another location
edit         -- Edits an ASCII or UNICODE file in full screen
eficompress     -- Compress a file
efidecompress     -- Compress a file
exit         -- Exits the EFI Shell
help         -- Displays help menus, command list, or verbose help of a command
hexedit     -- Edits with hex mode in full screen
ls         -- Displays a list of files and subdirectories in a directory
mkdir         -- Creates one or more directories
mode         -- Displays or changes the mode of the console output device
mv         -- Moves one or more files/directories to destination
rm         -- Deletes one or more files or directories
set         -- Displays, creates, changes or deletes

EFI environment variables
==================================================

setsize     -- Sets the size of the file
touch         -- Updates time with current time
type         -- Displays the contents of a file
xchar         -- Turn on/off extended character features

Shell Script Commands
====================================================

echo         -- Displays messages or turns command echoing on or off for/endfor -- Executes commands for each item in a set of items
goto         -- Makes batch file execution jump to another location if/endif -- Executes commands in specified conditions
pause         -- Prints a message and suspends for keyboard input
stall         -- Stalls the processor for some microseconds


