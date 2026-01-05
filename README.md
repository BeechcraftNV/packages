# Package Reference List

Personal reference list for populating fresh Linux system installs. Contains curated packages from apt/pacman and Flatpak organized by category.

## Purpose

This repository is my go-to resource when installing a new distro or setting up a fresh OS. Instead of remembering package names or searching for tools, I can quickly pull this list and install what I need.

**Primary use case:** Fresh distro/OS installs - a package name reference, not install scripts. Since the next OS could be Debian, Arch, NixOS, or something else entirely, the focus is on **what** to install, not **how**.

Also useful for:
- Migrating between distributions
- Sharing package recommendations
- Maintaining consistency across multiple machines
- Testing different distros (even NixOS)

## Structure

**packages.md** contains curated packages organized into categories:
- Essential CLI tools (vim, git, curl, etc.)
- Modern CLI replacements (eza, bat, fd, btop)
- Terminal emulators (multiple options to test)
- Development tools
- Media applications
- GUI applications (native and Flatpak)

**system-packages.md** is a generated snapshot of actual installed packages on the current system (for reference/comparison)

## Usage

On a fresh install:
1. Clone this repo
2. Review `packages.md`
3. Search for package names in your distro's package manager
4. Install what makes sense for your environment

Package names may vary slightly between distros (e.g., `fd-find` on Debian vs `fd` on Arch), but Flatpak IDs are consistent everywhere.

## Notes

- Contains intentional duplicates (multiple terminal emulators, file managers) for testing different options
- File manager choice depends on desktop environment
- Some packages require additional repository setup (Docker, Tailscale)
- Flatpaks are distribution-agnostic
- Pick and choose - you don't need everything on the list

---

*Maintained for quick system recovery and fresh OS population*
