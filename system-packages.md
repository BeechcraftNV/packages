# Actual System Package List

Generated from current system installation (Pop!_OS).

**Generated:** 2026-01-04

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
```
nautilus             # GNOME default
nemo                 # Cinnamon/lightweight
thunar               # XFCE
doublecmd-common     # dual-pane Norton Commander style
```

## GUI Applications (native packages)
```
brave-browser        # privacy-focused browser
foliate              # ebook reader
fresh-editor         # text editor
pan                  # usenet newsreader
weasyprint           # HTML to PDF converter
```

## Flatpaks - Installed
```
com.github.marktext.marktext           # markdown editor
com.sleepfiles.OSCAR                   # sleep apnea data viewer
com.spotify.Client                     # music streaming
dev.edfloreshz.CosmicTweaks            # Cosmic DE customization
dev.vencord.Vesktop                    # better Discord client
io.github.martinrotter.rssguard        # RSS/Atom feed reader
org.angryip.ipscan                     # network scanner GUI
org.blender.Blender                    # 3D creation suite
org.gimp.GIMP                          # image editor
org.gnome.Boxes                        # VM manager
org.kde.dolphin                        # KDE file manager
org.qbittorrent.qBittorrent            # torrent client
org.videolan.VLC                       # media player
tv.plex.PlexDesktop                    # media server client
us.zoom.Zoom                           # video conferencing
```

## System Packages (Bulk Installs)
### LibreOffice Localization
```
libreoffice-help-de, libreoffice-help-en-gb, libreoffice-help-en-us
libreoffice-help-es, libreoffice-help-fr, libreoffice-help-it
libreoffice-help-ja, libreoffice-help-pt, libreoffice-help-pt-br
libreoffice-help-ru, libreoffice-help-zh-cn, libreoffice-help-zh-tw
libreoffice-l10n-ar, libreoffice-l10n-de, libreoffice-l10n-en-gb
libreoffice-l10n-en-za, libreoffice-l10n-es, libreoffice-l10n-fr
libreoffice-l10n-it, libreoffice-l10n-ja, libreoffice-l10n-pt
libreoffice-l10n-pt-br, libreoffice-l10n-ru, libreoffice-l10n-zh-cn
libreoffice-l10n-zh-tw
```

### Thunderbird Localization
```
thunderbird-locale-ar, thunderbird-locale-de, thunderbird-locale-en
thunderbird-locale-en-gb, thunderbird-locale-en-us, thunderbird-locale-es
thunderbird-locale-es-ar, thunderbird-locale-es-es, thunderbird-locale-fr
thunderbird-locale-it, thunderbird-locale-ja, thunderbird-locale-pt
thunderbird-locale-pt-br, thunderbird-locale-pt-pt, thunderbird-locale-ru
thunderbird-locale-zh-cn, thunderbird-locale-zh-hans, thunderbird-locale-zh-hant
thunderbird-locale-zh-tw
```

### Spell Check & Hyphenation
```
hunspell-ar, hunspell-de-at-frami, hunspell-de-ch-frami, hunspell-de-de-frami
hunspell-en-au, hunspell-en-ca, hunspell-en-gb, hunspell-en-us, hunspell-en-za
hunspell-es, hunspell-fr, hunspell-it, hunspell-pt-br, hunspell-pt-pt, hunspell-ru
hyphen-de, hyphen-en-ca, hyphen-en-gb, hyphen-en-us, hyphen-es, hyphen-fr
hyphen-it, hyphen-pt-br, hyphen-pt-pt, hyphen-ru
mythes-ar, mythes-de, mythes-de-ch, mythes-en-au, mythes-en-us, mythes-es
mythes-fr, mythes-it, mythes-pt-br, mythes-pt-pt, mythes-ru
```

### Language Packs
```
language-pack-ar, language-pack-de, language-pack-en, language-pack-es
language-pack-fr, language-pack-it, language-pack-ja, language-pack-pt
language-pack-ru, language-pack-zh-hans, language-pack-zh-hant
language-pack-gnome-ar, language-pack-gnome-de, language-pack-gnome-en
language-pack-gnome-es, language-pack-gnome-fr, language-pack-gnome-it
language-pack-gnome-ja, language-pack-gnome-pt, language-pack-gnome-ru
language-pack-gnome-zh-hans, language-pack-gnome-zh-hant
```

### Input Methods (IBus)
```
ibus-chewing         # Traditional Chinese
ibus-libpinyin       # Simplified Chinese Pinyin
ibus-table-cangjie3  # Cangjie input method
ibus-table-cangjie5  # Cangjie input method (v5)
ibus-table-quick-classic  # Quick input method
ibus-table-wubi      # Wubi input method
```

### Fonts
```
fonts-arphic-ukai
fonts-arphic-uming
fonts-noto-cjk
fonts-noto-cjk-extra
fonts-noto-core
fonts-noto-ui-core
```

### System76 Hardware Support
```
system76-acpi-dkms   # ACPI drivers
system76-dkms        # system drivers
system76-io-dkms     # I/O drivers
```

### Development Libraries (selected)
```
libadwaita-1-dev     # GTK4/Adwaita development
libgtk-4-dev         # GTK4 development
systemd-dev          # systemd development
```

---

## Notes

- Multiple terminal emulators installed for testing/comparison
- Multiple file managers for different DE testing
- Extensive localization packages (LibreOffice, Thunderbird, system)
- System76 hardware-specific drivers (Pop!_OS on System76 hardware)
- Development libraries present (GTK4, Adwaita, systemd headers)
