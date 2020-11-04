# Arch Linux Install
Install Script for Arch Linux in UEFI Mode

1. Visit the arch linux download page: https://www.archlinux.org/download/.
2. Download the .iso image.

## Virtual Machine - for VirtualBox
1. Install VirtualBox or another VM software of your choice.
2. Open VirtualBox
3. Click New
    * Name: Arch Linux*
    * Memory Size: 4096
    * Check **Create a vitural hard disk now**
    * Hard Disk Type: **VDI**
    * Storage on physical hard disk: **Dynamical Allocated**
    * File allocation and size: I choose 10 GB
    * Click **Create**
4. Choose the VirtualMachine and click **Settings**
5. Under System:
    * Choose __Enable EFI (special OSes Only)__
6. Under Storage:
    * Click Disk with the plus icon next to *Controllor: SATA*
7. Click Ok
8. You can now start the virtual machine and follow the commands in install_files/install.sh to install arch linux.
