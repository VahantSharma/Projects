# Spotify Installer Script

Welcome to the Spotify Installer Script! 🎶 This handy Bash script helps you install the Spotify client on your Debian-based system with ease.

## Overview

This script performs the following tasks:

1. Checks if the script is being run as the root user.
2. Verifies that the `apt-get` package manager is available.
3. Searches for the Spotify repository in your system’s sources list.
4. Prompts the user to add the Spotify repository if it’s not found.
5. Updates the package list and installs the Spotify client.
6. Displays a fun congratulatory message upon successful installation.

## Requirements

- A Debian-based operating system (e.g., Ubuntu).
- Root privileges to install software.

## How to Use

1. **Open Terminal**: Launch your terminal application.
2. **Make the Script Executable**:
   If you haven’t already, make the script executable by running:
   ```bash
   chmod +x spotify_installer.sh
3. **Run the Script: Execute the script with root privileges**:
    sudo ./spotify_installer.sh
4. **Follow the Prompts: The script will guide you through the installation process. If the Spotify repository is not found, it will ask if you’d like to add it.**\

# Important Notes

- **Running as Root**:
    - Ensure you run the script as a root user.
    - If you try to run it as a regular user, you’ll receive a message indicating that administrator privileges are required.
- **Repository Check**:
    - The script checks if the Spotify repository is already added.
    - If not, it will prompt you for confirmation to add it.
- **Installation Time**:
    - The script will pause for 10 seconds after installation to let you enjoy a quirky little poem.