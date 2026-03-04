# arch-linux-install-guide
Clean Arch Linux installation notes (UEFI)

# Arch Linux Installation – Clean & Minimal Setup (UEFI)

This repository documents a clean, minimal, and practical Arch Linux
installation process. It is intended for users who want to understand
what they are installing instead of blindly copy-pasting commands.

## Who This Guide Is For

- New users installing Arch Linux for the first time
- Linux users switching from other distributions
- Users who want a minimal base system
- Anyone who prefers a documented, step-by-step approach

## What This Guide Covers

- UEFI based installation
- Disk partitioning (GPT)
- Base system installation
- User creation and permissions
- Networking setup
- Bootloader setup
- Post-install essentials

## What This Guide Does NOT Cover

- Desktop environment customization
- Gaming or GPU configuration
- Advanced theming or ricing

## Installation Flow (High Level)

1. Boot Arch ISO  
2. Verify network connectivity  
3. Partition disks  
4. Install base system  
5. Configure system  
6. Install bootloader  
7. Reboot into Arch  

## Important Notes

- This guide assumes UEFI firmware
- Commands may change over time
- Always refer to the Arch Wiki when needed

## Full Step-by-Step Guide

A fully detailed walkthrough with explanations, screenshots,
and troubleshooting notes is available here:

👉 https://www.musabase.com/2025/03/the-complete-arch-linux-installation.html

---

## Desktop Environments (After Installation)

Once the base Arch Linux system is installed, the next major step is
choosing a desktop environment. Arch does not ship with a default
desktop, so this choice depends entirely on your hardware and workflow.

Available desktop environment notes:

- **KDE Plasma** – Feature-rich and flexible, suitable as a daily driver  
- **GNOME** – Clean and opinionated with a focused workflow  
- **XFCE** – Lightweight, stable, and ideal for older hardware  

Detailed notes are available in the following directory:

👉 [desktop-environments/](desktop-environments/)

Each desktop environment file links to a full step-by-step setup guide
on MusaBase.

---

## Hyprland (Wayland Tiling Compositor)

Some users prefer tiling workflows instead of traditional desktop
environments. Hyprland is a modern Wayland compositor that provides
dynamic tiling, smooth animations, and highly customizable layouts.

It allows Arch Linux users to build a keyboard-driven workflow while
maintaining a visually polished desktop environment.

This repository includes documentation for several Hyprland setups.

Available Hyprland configurations:

- **ML4W (My Linux For Work)** – Productivity-focused Hyprland setup  
- **HyDE Project** – Visually refined Hyprland configuration  
- **Caelestia Dotfiles** – Highly customized Hyprland environment  
- **Jakoolit Hyprland** – Balanced setup suitable for daily use  
- **End-4 Hyprland** – Advanced themes and visual customization  

Hyprland documentation files:

- [ML4W Hyprland](hyprland/ml4w-hyprland.md)
- [HyDE Hyprland](hyprland/hyde-hyprland.md)
- [Caelestia Hyprland](hyprland/caelestia-hyprland.md)
- [Jakoolit Hyprland](hyprland/jakoolit-hyprland.md)
- [End-4 Hyprland](hyprland/end-4-hyprland.md)

Each file links to a full installation guide available on MusaBase.

---

## What Comes Next

After setting up a desktop environment or a Hyprland tiling workflow,
Arch Linux can be shaped into a stable daily driver or a gaming-focused system.

Planned and related topics include:

- Daily driver stability and maintenance
- Linux gaming with Steam and Proton
- Common troubleshooting notes (GRUB, initramfs, mirrors)

## Why This Exists

Arch Linux installation can feel overwhelming due to the number of
choices involved. This documentation exists to provide a clear,
practical starting point while respecting Arch Linux philosophy.

## References

- Arch Wiki: https://wiki.archlinux.org/
- Arch Linux Installation Guide: https://wiki.archlinux.org/title/Installation_guide
