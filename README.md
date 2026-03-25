# Hyprland-Configuration
A streamlined, performance-oriented Hyprland setup designed for a seamless transition from KDE Plasma. This configuration focuses on a clean aesthetic while maintaining full hardware control and compatibility for gaming and productivity.

Quick Setup
Install Dependencies:

Bash
paru -S swayosd-git brightnessctl pamixer pipewire-pulse wireplumber foot wofi waybar swaybg nm-applet blueman flatpak hyprpolkitagent
Set Permissions:

Bash
sudo usermod -aG video,input $USER
Reboot your system after running this command.

Deploy Config: Copy your hyprland.conf to ~/.config/hypr/.

Features
Custom OSD: Plasma-style volume and brightness overlays via SwayOSD.

Modern Suite: Waybar for monitoring and Wofi for application launching.

Visual Polish: Cyan/Green gradient borders, 10px rounding, and active blur.

Power Management: Keybinds for reboot and shutdown without sudo.

Expandable: Lines 115 to 121 are reserved for adding your own extra bindings.

Keybinds
Super + Q: Terminal (Foot)

Super + B: Google Chrome

Super + C: Kill Active Window

Super + M: Exit Hyprland

Super + Shift + R: Reboot

Super + Shift + P: Power Off

F1-F3: Audio Controls (Mute/Down/Up)

F4-F5: Brightness Controls (Down/Up)
