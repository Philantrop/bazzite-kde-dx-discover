# ⚙️ bazzite-kde-dx

A Bazzite Image with git master Plasma and Gears plus full KDE development tools. Perfect for KDE developers who want to game too.

## Features

- Plasma (git master)
- KDE Gears (git master)
- KDE development tools and dependencies
- Development utilities: `kdevelop`, `flatpak-builder`, `clang`, `neovim`, `zsh`
- Preinstalled `kde-builder` with completions
- Enabled system services: `podman.socket`, `waydroid-container.service`

## Rebase to This Image

### Regular (AMD/Intel)

```bash
sudo ostree rebase ostree-unverified-registry:ghcr.io/silverhadch/bazzite-kde-dx:latest
```

### NVIDIA

```bash
sudo ostree rebase ostree-unverified-registry:ghcr.io/silverhadch/bazzite-kde-dx-nvidia:latest
```

Reboot afterwards to apply the image.

## Credits

Customizations by @silverhadch. Based on Bazzite and the Universal Blue Project. Using Solopashas Coprs for KDE Master Builds.
