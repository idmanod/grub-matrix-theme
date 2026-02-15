# GRUB Matrix Theme

A Matrix-inspired hacker theme for GRUB bootloader, matching the [SDDM Hacker Theme](https://github.com/idmanod/sddm-hacker-theme).

## Features

- 🟢 Matrix digital rain background
- 💻 MesloLGM Nerd Font Mono (20px + 32px bold)
- 🎯 Green selection bar with glow
- 📁 Distro icons included (CachyOS, Arch, Windows, etc.)
- 🎨 Terminal-style decorations

## Installation

```bash
# Clone
git clone https://github.com/idmanod/grub-matrix-theme.git

# Install
sudo cp -r grub-matrix-theme /boot/grub/themes/

# Set theme in GRUB config
sudo sed -i 's|GRUB_THEME=.*|GRUB_THEME="/boot/grub/themes/grub-matrix-theme/theme.txt"|' /etc/default/grub

# Regenerate GRUB config
sudo grub-mkconfig -o /boot/grub/grub.cfg
```

## Requirements

- GRUB 2
- MesloLGM Nerd Font (included as .pf2)

## License

MIT
