# Omarchy Notes

# Wifi setup during installation
- iwctl
- station list
- station wlan0 get-networks
- station wlan0 connect name-of-wifi
- enter password when promted
- ctrl+c

# Wifi settings to avoid wifi drops
- go to /etc/NetworkManager
- sudo nvim NetworkManager.conf
- add following lines
  [device]
  wifi.scan-rand-mac-address = no
  [connection]
  wifi.powersave = 0

# Monitor Setup
- env = GDK_SCALE, 1
- monitor = eDP-1, 1920x1200@60, 0x0, auto

# Steam additional packages
- lib32-vulkan-radeon
- lib32-vulkan-mesa-layers
- lib32-vulkan-validation-layers
- gamescope
- gamescope --backend sdl -f -- %command% (fix for games that error with X11 and runs fullscreen)

# Surfshark VPN
- sudo wget https://surfshark.com/api/v1/server/configurations
- install openvpn
- add following to ovpn file for autologin
  ```
  <auth-user-pass>
  username
  password
  </auth-user-pass>
  ```
- sudo openvpn [ovpn File from download]

# Wallpaper
- stored in .config/omarchy/themes/
- and then stored in relevant theme folder
