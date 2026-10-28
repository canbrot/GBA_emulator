# GBA_emulator
Retro console appliance on a legacy PC (i3-2100, 4 GB RAM, HDD): Debian 13 with a trimmed custom Linux 6.12 kernel, a custom init written in C and a minimal graphics stack, running Game Boy games via RetroArch + mGBA. Operating Systems course project: boot, memory, CPU and disk scheduling measurements.
# Retroconsole

An Operating Systems course project that turns a legacy PC into a dedicated
retro gaming console. Instead of writing an emulator, we build and measure the
system around it: a trimmed and recompiled Linux kernel, a custom init (PID 1)
written in C, and a minimal graphics stack on Debian 13, running Game Boy games
through RetroArch with the mGBA core.

The focus is on OS subsystems: boot and services, memory management, I/O and
interrupts, CPU scheduling and disk scheduling. Each result is measured on the
real hardware and explained.

## Hardware

| Component | Detail |
|---|---|
| Motherboard | Biostar H61MH (Micro-ATX, legacy BIOS) |
| CPU | Intel Core i3-2100 |
| RAM | 4 GB DDR3 |
| Disk | 500 GB HDD |
| Input | Wired USB gamepad |

## Status

Work in progress. See BITACORA.md for the log of what has been done.
