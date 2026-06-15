# My Typecraft Dotfiles Fork (Streamlined Workflow)

This repository is a personalized fork of [Typecraft's dotfiles](https://github.com/typecraft-dev/dotfiles). 

I have stripped out the components that don't align with my current setup (such as Hyprland and its associated window management utilities) to create a lean, hyper-focused configuration tailored specifically for a terminal-centric workflow on a stacked CLI/TUI stack.

## Key Differences & Focus Areas

While the original repository provides a beautiful, full-desktop environment configuration, this fork strips away dotfiles to focus entirely on productivity inside the terminal emulator.

* **Removed:** Hyprland configurations, Waybar, Rofi, and other Linux window manager-specific utilities.
* **Kept & Optimized:**
    * **Kitty:** My primary terminal emulator, configured for performance and aesthetics.
    * **Tmux:** Workspace management, session handling, and persistent multiplexing.
    * **Zsh (`.zshrc`):** Optimized shell configurations, aliases, and prompt settings for a fast, intuitive CLI experience.

---

## Components

### Kitty
Configured with clean typography, optimal padding, and a color scheme that reduces eye strain during long sessions.

### Tmux
The nerve center of the workflow. Includes intuitive session switching, split pane management, and status bar configurations that keep relevant system info visible without being distracting.

### Zsh / `.zshrc`
Packed with essential productivity aliases, functions, and completions designed to speed up daily systems administration and development tasks.

---

## 👥 Credits & Acknowledgments

A massive thank you to **Typecraft** for the incredible foundation. 

* **Original Repository:** [typecraft-dev/dotfiles](https://github.com/typecraft-dev/dotfiles)
* **YouTube Channel:** [Typecraft on YouTube](https://www.youtube.com/@typecraft_dev)

> **Note:** The Tmux configuration in this repository is heavily inspired by and built upon Typecraft's excellent YouTube tutorials. If you are looking to master Tmux terminal multiplexing or want to understand the philosophy behind these dotfiles, I highly recommend checking out his videos.

---

## 🔧 Installation / Usage

> [!WARNING]
> This is a personal configuration fork. Back up your existing configurations before copying or symlinking any files to your local system.

1. Clone the repository:
   ```bash
   git clone [https://github.com/YOUR_USERNAME/dotfiles.git](https://github.com/YOUR_USERNAME/dotfiles.git) ~/src/dotfiles
