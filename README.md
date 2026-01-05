# Package Reference List

Personal reference list for populating fresh Linux system installs. Contains curated packages from apt/pacman and Flatpak organized by category.

## Purpose

This repository is my go-to resource when installing a new distro or setting up a fresh OS. Instead of remembering package names or searching for tools, I can quickly pull this list and install what I need.

**Primary use case:** Fresh distro/OS installs - open this list and populate the new system with preferred tools and applications.

Also useful for:
- Migrating between distributions
- Sharing package recommendations
- Maintaining consistency across multiple machines

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
3. Pick packages based on your distro/DE
4. Copy relevant install commands
5. Customize as needed

Quick install examples are included at the bottom of `packages.md` for common package managers (apt, pacman, flatpak).

## Notes

- Contains intentional duplicates (multiple terminal emulators, file managers) for testing different options
- File manager choice depends on desktop environment
- Some packages require additional repository setup (Docker, Tailscale)
- Flatpaks are distribution-agnostic
- Pick and choose - you don't need everything on the list

---

*Maintained for quick system recovery and fresh OS population*
