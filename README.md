# Installing Swavoti on Linux

Welcome to Swavoti! Follow these simple steps to install the Linux desktop application on your Debian or Ubuntu-based system.

## Download the App

Download the latest Swavoti `.deb` package here:
[Download Swavoti (v2.4.1)](https://github.com/swavoti/swavoti-releases/releases/download/v2.4.1/swavotidesktop-linux.deb)

---

## How to Install

### Method 1: The Easy Way (Graphical UI)
1. Open your **Downloads** folder.
2. **Double-click** the downloaded `swavotidesktop-linux.deb` file.
3. This will open your system's default software manager (like Ubuntu Software Center, GNOME Software, or Eddy).
4. Click the **Install** button.
5. Enter your computer's password when prompted.
6. Once finished, you can find **Swavoti** in your application launcher!

### Method 2: The Terminal Way (For Power Users)
If you prefer using the command line, or if the graphical method isn't working, follow these steps:

1. Open your Terminal (`Ctrl + Alt + T`).
2. Navigate to your downloads folder:
   ```bash
   cd ~/Downloads
   ```
3. Install the package using `apt` (this automatically handles any missing dependencies):
   ```bash
   sudo apt install ./swavotidesktop-linux.deb
   ```
4. Press `Y` if prompted, and wait for the installation to finish.
5. Launch the app by typing `swavoti` in the terminal or finding it in your app menu.

---

## Troubleshooting
- **Missing Dependencies?** If you used `dpkg` and ran into dependency errors, simply run:
  ```bash
  sudo apt-get install -f
  ```
- **Updates:** Swavoti includes an automatic updater! When a new version is released, the app will notify you and handle the download directly from within the interface.
