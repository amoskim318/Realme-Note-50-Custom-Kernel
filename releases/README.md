# RTL8188EUS Driver Releases

Tested device: Realme Note 50 (RMX3834)
Architecture: ARM64 (AArch64)
USB adapter: Realtek RTL8188EUS (VID:PID 0bda:8179)

## Magisk package — v1.0.2

`RTL8188EUS-Realme-Note-50-Magisk-v1.0.2.zip`

Install through the Magisk app using Install from storage.

Includes the kernel module, module metadata, device checks, and boot service.

## Standalone kernel module

`8188eu.ko` — for manual installation on a compatible rooted device.

## Verification

From the repository root, run:

    sha256sum -c releases/SHA256SUMS

The checksums cover both release files.

## Testing and limitations

The module successfully loaded on the tested device and supported monitor-mode operation and packet capture.

USB disconnect stability remains unresolved. Successful wireless testing does not establish support for every wireless feature.
