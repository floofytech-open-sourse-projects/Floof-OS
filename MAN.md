.TH FLOOFOS 7 "March 2026" "FloofyTech" "Miscellaneous Information"

.SH NAME
floofos - lightweight Debian-based operating system

.SH SYNOPSIS
.B floofos
[bootable live environment]

.SH DESCRIPTION
FloofOS is a Debian-derived operating system designed for reliability,
hardware compatibility, and ease of deployment. The system can run
entirely from removable media and does not require installation to an
internal storage device.

FloofOS uses a customized boot environment and provides the Cinnamon
desktop environment along with a curated set of tools for general
computing, troubleshooting, and system recovery tasks.

The operating system may be run directly from USB drives, external or
internal storage devices, or within virtual machines. A persistence
layer may optionally be used to retain user files and configuration
between sessions.

.SH FEATURES
.IP (bu 2
UEFI and legacy BIOS boot compatibility
.IP (bu 2
Portable live environment
.IP (bu 2
Operates without internal storage
.IP (bu 2
Consistent environment across hardware platforms
.IP (bu 2
Reproducible ISO-based system images
.IP (bu 2
Optional persistent storage support

.SH FILES
.B floofos-floof2025.iso
Bootable FloofOS distribution image.

.SH BUGS
Performance may be reduced on extremely old hardware.
Persistence requires compatible partition layouts and may not function
correctly on all USB devices.

.SH AUTHOR
FloofyTech

.SH SEE ALSO
.BR debian-live (7),
.BR live-boot (7),
.BR systemd (1),
.BR cinnamon-session (1)
