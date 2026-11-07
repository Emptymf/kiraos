# KiraOS ✦ キラ — Y2K anime Linux, two editions

| | debian/ | arch/ |
|---|---|---|
| Base | Debian 13 live-build | Arch (archiso) |
| Desktop | XFCE + Plank dock + picom | Hyprland + Waybar |
| Blur / effects | picom dual-kawase blur on frosted frames, panels, dock | native Hyprland blur, animated borders, gel animations |
| Window frames | custom **Kira-Y2K** xfwm4 theme (aqua gradient + gel orb buttons) | Hyprland borders + GTK gel CSS |
| Layouts | Dock / Taskbar (`kira-layout`) | Dock / Taskbar (`kira-layout`, SUPER+SHIFT+L) |
| Installer | Calamares | archinstall + `kira-post-install` |
| Works in VMs | yes (auto lite mode) | needs 3D-accelerated VM or real hardware |

Build instructions are in each edition's README. Neither ISO has been built or booted by me (no network in my sandbox),
so expect a fix or two on first build; the window theme PNGs and configs were generated/validated for syntax.
