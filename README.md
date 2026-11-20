# Realme Note 50 Custom Kernel

An experimental custom kernel development and Android hardware research project for the Realme Note 50 (RMX3834).

## Project Overview

This project explores the device's Android kernel, hardware compatibility, kernel configuration, driver development, and possibilities for custom Android system development.

A major part of the project is integrating and testing the Realtek RTL8188EUS USB Wi-Fi adapter with the device's Linux kernel.

## Device Information

| Component | Details |
|---|---|
| Device | Realme Note 50 |
| Model | RMX3834 |
| Android | Android 15 |
| SoC | Unisoc UMS9230 |
| Kernel | Linux 5.15.178 |

## Development Areas

- Android kernel source investigation
- Kernel configuration and vendor feature research
- External Linux driver integration
- RTL8188EUS USB Wi-Fi driver compatibility
- Kernel module compilation and installation
- Wireless interface and monitor-mode testing
- Hardware compatibility and stability investigation
- Custom ROM and Android platform research

## Current Project Status

Experimental development.

The RTL8188EUS driver has been successfully loaded and tested, including wireless monitor-mode operation and packet capture.

USB disconnect stability remains under investigation.

## Repository Structure

- `driver-source/` — driver source code
- `patches/` — project modifications and compatibility fixes
- `tests/` — testing scripts and procedures
- `evidence/` — screenshots, logs, and demonstration recordings
- `poc/` — proof-of-concept experiments

## Documentation

Detailed technical documentation, development history, source references, troubleshooting, and test results will be maintained in the [GitHub Wiki](https://github.com/amoskim318/Realme-Note-50-Custom-Kernel/wiki).

## Disclaimer

This is an experimental research and development project. Use modifications and kernel modules at your own risk. Only perform wireless security testing on networks and devices you own or are authorized to test.
