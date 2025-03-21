Small .config file for linux kernel that is quite minimal and works in qemu wm with intel hardware. I made this just for me so this might not work on other hardware without tweaking.

#### Basic features:

-   Multi-processor support with 12 CPUs max, this can be easily increased
-   LZ4 kernel compression (gzip or xz might be better)
-   Voluntary preemption model
-   1000Hz timer frequency
-   Full ACPI power management
-   Intel graphics with KVM virtualization
-   SATA/PATA disk controllers
-   Standard network hardware (Intel, Realtek, Broadcom)
-   USB controllers, storage, PS/2, input devices
-   IPv4/IPv6 with basic firewall stuff
-   Wireless and wired networking support
-   EXT4 as primary filesystem
-   FAT/VFAT and ISO9660 support
-   Basic sound support (Intel HD)
-   CPU frequency scaling with Intel P-state driver
