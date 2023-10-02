# slstatus - Lightweight Status Bar for Window Managers

slstatus is a lightweight status monitor for window managers like dwm that fills the status bar with system information.  

## Features

- Battery percentage, state, and estimated time remaining
- CPU usage and frequency   
- Custom shell commands
- Current date and time
- Disk usage and available storage
- Available entropy
- User, group, and host details
- IP addresses (IPv4 and IPv6)
- Kernel version 
- Keyboard indicators and current keymap
- System load average
- Network speeds (RX and TX)   
- File counts for directories
- Memory and swap usage
- Temperature
- Uptime
- Volume percentage
- WiFi signal strength and SSID

## Compatibility

slstatus works on Linux, FreeBSD, and OpenBSD. It requires Xlib headers to build.

## Installation

Edit `config.mk` to match your system settings then run:

    make clean install

See the man page for usage details. Customize the status bar by editing `config.h`.

## Upcoming

- v1.0 release coming soon!
- Development has resumed after long hiatus. 

## Summary

slstatus is a lightweight status monitor for hackable window managers like dwm. It displays system stats like CPU, memory, network, temps, and more. Customizable and available on Linux, BSD.
