# tarballs

mkusb is a tool to create USB boot drives and also to wipe and/or restore USB drives (after they are used as boot drives).
mkusb helps you identify the target device so that the operation will be safe.

This repository contains tarballs with parts of the mkusb system.
-----------------------------------------------------------------

### Install via PPA

The most convenient way to manage mkusb is via a PPA at Launchpad,

    sudo add-apt-repository universe  # only for standard Ubuntu live

    sudo add-apt-repository ppa:mkusb/ppa  # and press Enter
    sudo apt update
    sudo apt install mkusb usb-pack-efi

This works well in Ubuntu and the Ubuntu family flavours. It is somewhat more complicated with Debian according to this link

https://help.ubuntu.com/community/mkusb/install-to-debian

### Install via tarball

In other linux distros and if you do not like PPA repositories, you can install mkusb via the tarballs that you find here.

- Download a tarball and check the md5sum

- Extract the content from the tarball

- In the extracted directory you will find an installer shellscript,
  that can both install the content of the tarball and remove it.

See the instructions

- for mkusb version previously 12 now 25 alias dus, the main version:
  https://help.ubuntu.com/community/mkusb/gui/tarball

- for mkusb-plug, a new version with a plug-in method to identify the target device:
  https://help.ubuntu.com/community/mkusb/plug

- for an experimental GUI interface 'eXtra Safe CLoner' for xorriso-dd-target:
  https://help.ubuntu.com/community/mkusb/xscl

- for mkusb-nox, the old text mode version upgraded to work well for iso-testing 2022:
  [mkusb-nox: For Servers and Shell Environments](https://help.ubuntu.com/community/mkusb/#mkusb-nox:_For_Servers_and_Shell_Environments)
