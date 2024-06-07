## dotfiles

This is a repo for my personal dotfiles.

I am using Debain 12 and working currently with i3 and its adjacents like:
* 13blocks
* i3lock
* i3status
* picom

## Terminal workplace
![Screenshot from 2024-06-06 02-24-49](https://github.com/CrescentMnn/dotfiles/assets/169625322/dacb387d-641c-47b8-8d39-7f10c4a99f17)

## Firefox workplace
![Screenshot from 2024-06-06 02-27-02](https://github.com/CrescentMnn/dotfiles/assets/169625322/44946d6a-f199-4630-bfe6-ea141cada666)

## Music workplace
![Screenshot from 2024-06-06 02-27-45](https://github.com/CrescentMnn/dotfiles/assets/169625322/cdb96c90-dcb3-4560-aed6-e924e38d7858)

## i3lock
![Screenshot from 2024-06-06 02-28-16](https://github.com/CrescentMnn/dotfiles/assets/169625322/29184644-6336-47f6-919d-d00ea89fa248)

## Installation

To use these dotfiles, you can clone the repository and copy the files to your home directory:

```bash
# Clone the repository
git clone https://github.com/yourusername/dotfiles.git

# Navigate to the dotfiles directory
cd dotfiles

# Copy the configuration files to your home directory
cp -r .config/* ~/.config/

```

## Configuration

This repository includes configuration files for the following:

- **i3**: The window manager configuration.
- **i3status**: The status bar configuration.
- **i3blocks**: A flexible status line for the i3 window manager.
- **picom**: A compositor for X11, used for window transparency and effects.
- **scripts**: Custom scripts, including `i3lock` for screen locking.

### i3

The i3 configuration file is located at `.config/i3/config`. This file contains the keybindings, window rules, and other settings for the i3 window manager.

### i3status

The i3status configuration file is located at `.config/i3status/config`. This file defines what information is displayed in the i3 status bar.

### i3blocks

The i3blocks configuration file is located at `.config/i3blocks/config`. This file allows you to customize the blocks displayed in the status bar.

### picom

The picom configuration file is located at `.config/picom/picom.conf`. This file contains settings for window transparency, shadows, and other visual effects.

### Scripts

The `scripts` directory contains custom scripts that enhance the functionality of i3. For example, the `i3lock` script is used for locking the screen with a custom lock screen.

