# persistent-usb
Simple bash script to create a persistent USB from a live Debian (and derivates) ISO.

This will probably work with all live ISOs with Grub2 that are configured to boot with the 'quiet splash' or 'splash quiet' arguments.

persistent-usb will check if these arguments exist and quits when not found.

Dependencies: fdisk, parted, coreutils, e2fsprogs, util-linux

Usage: persistent-usb [path-to-iso]