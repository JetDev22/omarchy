# Omarchy Notes

# Monitor Setup
env = GDK_SCALE, 1
monitor = eDP-1, 1920x1200@60, 0x0, auto

# Steam additional packages
lib32-vulkan-radeon
lib32-vulkan-mesa-layers
lib32-vulkan-validation-layers
SDL_VIDEODRIVER=x11 %command% (as fix for games)

# Surfshark VPN
sudo wget https://surfshark.com/api/v1/server/configurations
sudo openvpn *ovpn File from download*
enter Username
enter Password

# Wallpaper
stored in .config/omarchy/themes/
and then stored in relevant theme folder
