# GNOME Workspace Configurator ✨

<p align="center">
  <a href="https://github.com/LINUX-OASIS/GNOME-WORKSPACES-STATIC-DYNAMIC/blob/main/LICENSE">
    <img src="https://img.shields.io/badge/License-GPLv3-blue.svg" alt="License: GPL v3">
  </a>
  <a href="https://www.gnu.org/software/bash/">
    <img src="https://img.shields.io/badge/Shell_Script-121011?style=for-the-badge&logo=gnu-bash&logoColor=white" alt="Language: Bash">
  </a>
  <a href="https://www.gnome.org/">
    <img src="https://img.shields.io/badge/GNOME-%234A86CF.svg?style=for-the-badge&logo=gnome&logoColor=white" alt="GNOME">
  </a>
  <a href="#">
    <img src="https://img.shields.io/badge/Compatibility-Debian%20%7C%20Ubuntu%20%7C%20Mint-orange" alt="Compatibility">
  </a>
</p>

<p align="center">
  <a href="https://github.com/LINUX-OASIS/GNOME-WORKSPACES-STATIC-DYNAMIC/stargazers">
    <img src="https://img.shields.io/github/stars/LINUX-OASIS/GNOME-WORKSPACES-STATIC-DYNAMIC?style=social" alt="GitHub stars">
  </a>
  <a href="https://github.com/LINUX-OASIS/GNOME-WORKSPACES-STATIC-DYNAMIC/network/members">
    <img src="https://img.shields.io/github/forks/LINUX-OASIS/GNOME-WORKSPACES-STATIC-DYNAMIC?style=social" alt="GitHub forks">
  </a>
  <a href="https://github.com/LINUX-OASIS/GNOME-WORKSPACES-STATIC-DYNAMIC/issues">
    <img src="https://img.shields.io/github/issues/LINUX-OASIS/GNOME-WORKSPACES-STATIC-DYNAMIC" alt="GitHub issues">
  </a>
  <a href="https://github.com/LINUX-OASIS/GNOME-WORKSPACES-STATIC-DYNAMIC/pulls">
    <img src="https://img.shields.io/github/issues-pr/LINUX-OASIS/GNOME-WORKSPACES-STATIC-DYNAMIC" alt="GitHub pull requests">
  </a>
</p>

A simple yet powerful shell script to quickly switch your GNOME desktop environment between **dynamic** and **static** workspaces using a friendly terminal-based UI.

---

## 🚀 Features

-   **Interactive TUI**: Uses `whiptail` for a clean and simple menu-driven experience right in your terminal.
-   **Dynamic Workspaces**: Enable GNOME's default behavior where workspaces are created and removed on the fly.
-   **Static Workspaces**: Set a fixed number of workspaces for a more predictable workflow.
-   **Customizable Count**: When choosing static workspaces, you can select between 4, 6, or 8 workspaces.
-   **Dependency Checker**: Automatically checks for required tools and offers to install them for you.

## 🖥️ Compatibility

This script is designed for Linux distributions using the **GNOME Desktop Environment**. It is compatible with:

-   Debian
-   Ubuntu
-   Linux Mint
-   Other Debian derivatives that use the `apt` package manager.

The script relies on `gsettings` to modify GNOME's configuration, which is a standard part of the desktop.

## 🛠️ Prerequisites & Dependencies

The script requires the following command-line tools to be installed:

-   `gsettings` (typically included with GNOME in the `libglib2.0-bin` package)
-   `whiptail` (provided by the `whiptail` package)

Don't worry if you don't have them! The script will check for these dependencies on launch. If any are missing, it will prompt you for permission and attempt to install them automatically using `apt`.

## ⚙️ Installation & Usage

1.  **Clone the repository (once it's on GitHub):**
    ```bash
    git clone https://github.com/LINUX-OASIS/GNOME-WORKSPACES-STATIC-DYNAMIC.git
    cd GNOME-WORKSPACES-STATIC-DYNAMIC
    ```

2.  **Make the script executable:**
    ```bash
    chmod +x custom-GNOME-WORKSPACES-STATIC-DYNAMIC.sh
    ```

3.  **Run the script:**
    ```bash
    ./custom-GNOME-WORKSPACES-STATIC-DYNAMIC.sh
    ```

    Follow the on-screen menus to configure your workspaces!

## 💬 Contributing

Pull requests, issues, and suggestions are warmly welcomed!

See [CONTRIBUTING.md](https://github.com/LINUX-OASIS/GNOME-WORKSPACES-STATIC-DYNAMIC/blob/main/CONTRIBUTING.md) for guidelines.

## 🌐 Links

-   [**Issues**](https://github.com/LINUX-OASIS/GNOME-WORKSPACES-STATIC-DYNAMIC/issues)
-   [**Pull Requests**](https://github.com/LINUX-OASIS/GNOME-WORKSPACES-STATIC-DYNAMIC/pulls)
-   [**Releases**](https://github.com/LINUX-OASIS/GNOME-WORKSPACES-STATIC-DYNAMIC/releases)
-   [**Wiki**](https://github.com/LINUX-OASIS/GNOME-WORKSPACES-STATIC-DYNAMIC/wiki)

## 🧙‍♂️ Maintainer

-   [**LINUX-OASIS**](https://github.com/LINUX-OASIS)

## 📜 License

This project is licensed under the **GNU General Public License v3.0**. See the `LICENSE` file for details.
