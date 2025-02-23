# Bindable-LagSwitch
A simple Lag Switch designed for windows, with a toast notification when enabled / disabled, and hotkey support

# Hotkey Creation + Downloading
- - Download the exe
- - On first run, it will ask you to create a keybind, it can be any single key
- - It will also ask for the mode to use
- - It will then store this file under hotkey.txt and mode.txt respectivly, delete these file to reset them

# Script Usage
- - To enable, press your assigned hotkey
- - To disable, press your assigned hotkey again
  - OR
- - When using hold, hold to enable, release to disable

# How it works
It uses the os import to run a simple command:
- ipconfig /release (To disable the connection)
- ipconfig /renew (To Re-Enable the connection)
