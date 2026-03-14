FLOOFOS(1)                     System Administration                     FLOOFOS(1)

NAME
floofos - lightweight Debian-based live operating system

SYNOPSIS
floofos [bootable live environment]

DESCRIPTION
FloofOS is a portable, Debian-derived operating system designed for
reliability, hardware compatibility, and easy deployment. The system
can run entirely from removable media and does not require installation
to an internal storage device.

   FloofOS uses a customized Debian live-boot environment and provides
   the Cinnamon desktop environment along with a curated set of tools for
   general computing, troubleshooting, and system recovery tasks.

   The operating system may be run directly from USB drives, external SSDs,
   or within virtual machines. A persistence layer may optionally be used
   to retain user files and configuration between sessions.

FEATURES
• UEFI and legacy BIOS boot compatibility
• Portable live environment
• Operates without internal storage
• Consistent environment across hardware platforms
• Reproducible ISO-based system images
• Optional persistent storage support

FILES
floofos-floof2025.iso
Bootable FloofOS distribution image.

BUGS
Performance may be reduced on extremely old hardware.
Persistence requires compatible partition layouts and may not function
correctly on all USB devices.

AUTHOR
FloofyTech

SEE ALSO
debian-live(7), live-boot(7), systemd(1), cinnamon-session(1)
