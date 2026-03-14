FLOOFOS(1)                 System Administration                 FLOOFOS(1)

NAME
    FloofOS – A lightweight, Debian‑based operating system



DESCRIPTION
    FloofOS is a portable, Debian‑derived live and installable operating system designed
    for reliability, hardware compatibility, and ease of deployment.
    It operates entirely from removable media and does not require an
    internal storage device to function.

    The system includes a customized live‑boot architecture, a Cinnamon
    desktop environment, and a curated set of utilities intended for
    general use, troubleshooting, and system recovery.

FEATURES
    • Universal boot support (UEFI and Legacy BIOS)
    • Runs from USB, SSD, or virtualized environments
    • Does not rely on internal drives; boots on failing or missing disks
    • Consistent performance across diverse hardware
    • Self‑contained ISO capable of reproducing identical environments
    • Optional persistence layer for saving user data

OPTIONS
    NONE
FILES
    floofos-floof2025.iso

BUGS
    FloofOS may exhibit reduced performance on extremely old hardware.
    Persistence requires compatible partitioning and may not function
    on all USB devices.

AUTHOR
   FloofyTech

SEE ALSO
    debian-live(7), systemd(1), cinnamon-session(1)
