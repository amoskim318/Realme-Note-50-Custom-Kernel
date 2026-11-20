# RTL8188EUS Driver Source

Upstream: https://github.com/aircrack-ng/rtl8188eus

Upstream revision:
af3bf004458f76b7aec33e9ba552cd382ed1f5c3

The upstream directory contains the clean source snapshot.

Our compatibility modifications are preserved in:
`patches/rtl8188eus-compatibility.patch`

The patch was verified against the clean upstream source.

Apply it with:

    patch -p1 -d upstream < ../patches/rtl8188eus-compatibility.patch

See the project Wiki for device information, compatibility changes, installation, and testing.
