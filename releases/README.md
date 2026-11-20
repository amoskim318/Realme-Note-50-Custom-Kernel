# Driver Release Artifact

File: `8188eu.ko`

This is the stripped RTL8188EUS kernel module tested on the Realme Note 50.

Architecture: AArch64
Device: Realme Note 50 (RMX3834)
USB adapter: RTL8188EUS (VID:PID 0bda:8179)

The module successfully loaded and supported monitor-mode operation and packet capture.

USB disconnect stability remains unresolved.

Verify the file using:

    sha256sum -c SHA256SUMS
