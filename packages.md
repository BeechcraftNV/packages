# System Package List

Reference list for fresh system installs. Pick and choose based on distro/DE.

## Essential CLI Tools
```
vim
git
curl
wget
rsync
tmux
```

## Modern CLI Tools
```
fzf          # fuzzy finder
eza          # better ls
bat          # better cat with syntax highlighting
fd-find      # better find
btop         # system monitor
duf          # better df (disk usage)
tldr         # quick command examples
glow         # markdown viewer
gum          # shell script UI components
mods         # CLI for LLMs
cht.sh       # cheat sheets
pandoc       # universal document converter
```

## Shells
```
fish         # friendly interactive shell
```

## Terminal Emulators
Pick one or two based on preference/testing:
```
ghostty              # fast, native, new
wezterm-nightly      # GPU-accelerated, Rust
kitty                # GPU-accelerated
warp-terminal        # AI features, blocks
cosmic-term          # native for Cosmic DE
xterm                # lightweight fallback
```

## Network/System Tools
```
tailscale            # VPN mesh network
nmap                 # network scanner
arp-scan             # local network discovery
netcat-openbsd       # network debugging
wl-clipboard         # Wayland clipboard utilities
```

## Development
```
code                 # VSCode
nodejs               # JavaScript runtime
```

## Media
```
ffmpeg               # video/audio processing
mpv                  # minimalist video player
```

## File Managers
DE-dependent - pick what matches your desktop:
```
nautilus             # GNOME default
nemo                 # Cinnamon/lightweight
thunar               # XFCE
doublecmd-common     # dual-pane Norton Commander style
# dolphin via flatpak (see below)
```

## GUI Applications (native packages)
```
brave-browser        # privacy-focused browser
foliate              # ebook reader
fresh-editor         # text editor
pan                  # usenet newsreader
weasyprint           # HTML to PDF converter
```

## Flatpaks - Core Apps
```
com.spotify.Client
org.videolan.VLC
org.qbittorrent.qBittorrent
tv.plex.PlexDesktop
us.zoom.Zoom
```

## Flatpaks - Creative/Productivity
```
org.blender.Blender
org.gimp.GIMP
com.github.marktext.marktext           # markdown editor
```

## Flatpaks - Utilities
```
dev.vencord.Vesktop                    # better Discord client
io.github.martinrotter.rssguard        # RSS/Atom feed reader
org.angryip.ipscan                     # network scanner GUI
org.gnome.Boxes                        # VM manager
org.kde.dolphin                        # KDE file manager
dev.edfloreshz.CosmicTweaks            # Cosmic DE customization
com.sleepfiles.OSCAR                   # sleep apnea data viewer
```

---

## Installation Notes

### Quick install patterns:

**Debian/Ubuntu:**
```bash
sudo apt install vim git curl wget rsync tmux fzf eza bat fd-find btop wl-clipboard
```

**Arch:**
```bash
sudo pacman -S vim git curl wget rsync tmux fzf eza bat fd btop wl-clipboard
```

**Flatpak:**
```bash
flatpak install com.spotify.Client org.videolan.VLC org.qbittorrent.qBittorrent
```

### Remember:
- Terminal choice depends on testing mood that day
- File manager depends on DE
- Don't install all terminals at once (but you will anyway)
- Docker/Podman installed separately via their official repos
- Tailscale needs their repo setup first

---

*Last updated: 2026-01-04*
