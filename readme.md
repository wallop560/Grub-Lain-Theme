
# Preview

![Preview](https://github.com/wallop560/Grub-Lain-Theme/blob/main/Preview.jpg?raw=true)
(the colours are a bit off because it was taken on my phone)
## Installation

*How to install:*

1. extract the zip to a folder inside of your grub/themes (example: boot/grep/themes/Lain).
2. open your grub config file located inside of the default folder (example: /etc/default/grub) and change the theme variable to point towards theme.txt inside of the theme folder.
3. run `sudo grub-mkconfig -o /boot/grub/grub.cfg` or `sudo update-grub` depending on your distro.
4. Restart and enjoy!