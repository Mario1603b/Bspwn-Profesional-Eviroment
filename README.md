auto-bspwm
This is a Bash script that automates the setup of a professional hacking environment for Kali Linux using the tiled window manager bspwm.

Installation
Install available updates.
sudo apt update
sudo apt upgrade -y
Clone the repository and navigate to it.
git clone https://github.com/r1vs3c/auto-bspwm.git
cd auto-bspwm
Grant execution permissions to the script.
chmod +x setup.sh
Execute the script.
./setup.sh
After the script has finished, you will be prompted to restart the system. Once you have rebooted, select bspwm as the window manager and then log in.
Overview of the environment
overview1

overview2

overview3

Keyboard shortcuts
Windows + Enter: Open a terminal emulator window (kitty).
Windows + W: Close the current window.
Windows + Alt + R: Restart the bspwm configuration.
Windows + Alt + Q: Log out.
Windows + (⬆⬅⬇➡): Navigate through windows in the current workspace.
Windows + D: Open Rofi. Press Esc to exit.
Windows + (1,2,3,4,5,6,7,8,9,0): Switch to the respective workspace.
Windows + T: Change the current window to tile mode.
Windows + M: Toggle the current window to "full" mode (doesn't occupy the polybar). Press the same keys to return to tile mode.
Windows + F: Change the current window to fullscreen mode (occupies the entire screen, including the polybar).
Windows + S: Change the current window to floating mode.
Windows + Shift + (1,2,3,4,5,6,7,8,9,0): Move the current window to another workspace.
Windows + Alt + (⬆⬅⬇➡): Resize the current window (only works if it's in floating mode).
Windows + Ctrl + (⬆⬅⬆➡): Change the position of the current window (only works if it's in floating mode).
Windows + Shift + F: Open Firefox.
Windows + Shift + B: Open Burpsuite.
Ctrl + Alt + L: Lock the screen.
Ctrl + Shift + ⬆⬇: Increase/decrease volume.
Ctrl + Shift + M: Mute/unmute volume.
Windows + Ctrl + Alt + (⬆⬅⬇➡): Show a preselection and then open a window (kitty, Firefox, File manager, etc.).
Windows + Ctrl + Alt + Space: Undo the preselection.
Ctrl + Shift + Enter: Open a sub-window in the current window.
Ctrl + Shift + Z: Zoom in on the current sub-window.
Ctrl + (⬆⬅⬇➡): Navigate between sub-windows in the current window.
Ctrl + Shift + R: Resize the current sub-window. Afterward, use:
W for 'Wider'
N for 'Narrower'
T for 'Taller'
S for 'Shorter'
R for 'Reset'
Esc to quit resize mode.
Ctrl + Shift + L: Toggle the arrangement of sub-windows.
Ctrl + Shift + W: Close the current sub-window or tab.
Ctrl + Shift + T: Open a tab in the current window.
Ctrl + Shift + Alt + T: Rename the title of the current tab.
Ctrl + Shift + (⬅➡): Navigate between current tabs.
Ctrl + Shift + C: Copy to the clipboard.
Ctrl + Shift + V: Paste from the clipboard.
F1: Copy to buffer A.
F2: Paste from buffer A.
F3: Copy to buffer B.
F4: Paste from buffer B.
Software
This configuration uses the following software:

WM: bspwm
Hotkey: sxhkd
Locker: i3lock-fancy
Shell: zsh
Shell Theme: powerlevel10k
Shell configuration manager: ohmyzsh
Bars: polybar
Bars Theme: polybar-themes
Compositor: picom
File Manager: thunar
Fonts: iosevka and hack
Application Launcher: rofi
Browsers: firefox
Terminals: kitty and qterminal
Static Wallpaper: feh
Screenshot: flameshot
Credits
This environment has been inspired by the functionalities of S4vitar's environment.
Thanks to Cube for their contribution to the creation of the archkali.png wallpaper.
