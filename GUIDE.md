# MusicBox User Guide

[← Back to Home](README.md)

---

## Welcome to MusicBox

This guide will help you set up and use your MusicBox system. Whether you're setting up for the first time or need help troubleshooting, you'll find everything you need here.

### Jump to Section
- [Software Setup](#software-setup)
- [Hardware Setup](#hardware-setup)
- [Using the App](#using-the-application)
- [Troubleshooting](#troubleshooting)

---

## System Requirements

### 💻 Computer
- Windows 10/11 or Linux (Ubuntu/Debian)
- macOS support coming soon
- USB port available

### 🔌 Hardware
- MusicBox device
- USB cable (data-capable)

### 🎵 Media Apps
- Spotify, YouTube, VLC, etc.
- Any app with system media controls
- No special setup needed

---

## Software Setup

Install and configure the MusicBox application

### Step 1: Download & Install

#### Download - Get the Application

**Windows:** [Download MusicBox.exe](https://github.com/golf-team/musicbox-releases/raw/refs/heads/main/windows/MusicBox.exe)

**Linux:** [Download MusicBox executable](https://github.com/golf-team/musicbox-releases/raw/refs/heads/main/linux/MusicBox)

No installation needed—the app is completely portable!

#### Run - Launch the App

**Windows:** Simply double-click MusicBox.exe

**Linux:** Make the file executable first:
```bash
chmod +x MusicBox
./MusicBox
```

The app will open and appear in your system tray.

#### Setup - First Launch Configuration

On first launch, you'll be asked if you want MusicBox to start automatically with your computer. We recommend selecting "Yes" for the best experience.

---

### Step 2: Using the Application

MusicBox has three main tabs that help you monitor, configure, and debug your setup.

#### 📊 Status Tab

![Status Tab](images/guides/status.png)
*The Status tab displays your currently playing music*

View what's currently playing on your MusicBox display:
- **Track Title:** The name of the current song
- **Artist Name:** Who performs the song
- **Playback Time:** Current position and total duration
- **Status:** Shows if music is Playing, Paused, or Stopped

#### ⚙️ Config Tab

![Config Tab](images/guides/configuration.png)
*Configure your device and application settings*

Manage your device and application settings:
- **Current Port:** Shows which USB port your device is connected to
- **Change Port:** Manually select a different USB port if needed
- **Auto-Detect:** Automatically find and connect to your MusicBox device
- **Launch at Startup:** Toggle automatic startup with your computer

> **Tip:** If your device isn't connecting, try clicking "Auto-Detect" first!

#### 🔧 Debug Tab

![Debug Tab 1](images/guides/debug_1.png)
*Debug information and troubleshooting tools*

![Debug Tab 2](images/guides/debug_2.png)
*Connection debug information and last sent data*

Access system information and troubleshooting tools:
- **System Information:** App version, Python version, memory usage
- **Queue Size:** Number of pending messages
- **Connection Debug:** Real-time connection status messages
- **Last Sent Data:** JSON data sent to your device
- **Restart Service:** Restart the connection if something goes wrong
- **View Logs:** Open the folder containing detailed log files

---

## Hardware Setup

Connect and configure your MusicBox device

### What You Need

- ✓ **MusicBox Device** - Your MusicBox device
- ✓ **Type-C USB Cable** - A Type-C USB cable that supports data transfer (not charging-only)
- ✓ **Computer** - Windows or Linux computer with an available USB port

### Connection Steps

#### 1 – Connect the Device
Plug your MusicBox device into your computer using the USB cable. The device should power on and the display should light up.

#### 2 – Launch the Application
Open the MusicBox application. It will automatically search for and connect to your device.

#### 3 – Verify Connection
Open the Config tab in the app. You should see your device port displayed (like "COM3" on Windows or "/dev/ttyUSB0" on Linux).

#### 4 – Test It Out
Play some music in Spotify, YouTube, or any other supported app. Your MusicBox display should start showing the track information!

---

## Troubleshooting

Solutions to common problems

### 🔌 Device Won't Connect

![No device connected](images/guides/configuration_no_device.png)
*Config tab when no device is detected*

**Try these solutions in order:**

1. Click the **"Auto-Detect"** button in the Config tab
2. Check that the USB cable supports data transfer (not just charging)
3. Try a different USB port on your computer
4. Unplug the device, wait 5 seconds, and plug it back in
5. Click **"Restart Service"** in the Debug tab
6. Close and reopen the MusicBox application

![Port selection](images/guides/select_port.png)
*Manually select a port if Auto-Detect doesn't work*

### 🎵 Music Not Displaying

**Check these items:**
- Verify that music is actually playing in a supported application
- Check that your device is connected (see Config tab)
- Ensure your media player uses system media controls (most do)
- Try pausing and resuming playback
- Restart both MusicBox and your media player

### 💻 Application Won't Start

- **Windows:** Try running as administrator (right-click → Run as administrator)
- **Linux:** Make sure the file has executable permissions (`chmod +x MusicBox`)
- Check if antivirus software is blocking the application
- Check the log files for error messages (see below)

### ⚠️ Display Showing Wrong Information

- Check the Status tab to see what MusicBox thinks is playing
- Make sure only one media app is playing at a time
- Click "Restart Service" in the Debug tab
- Close other media apps that might be interfering

---

## 📧 Getting Help

### If You Still Need Help

If none of the above solutions work, we're here to help! Follow these steps:

1. **Get Your Log Files:** Open the MusicBox app and go to the Debug tab. Click the **"View Logs"** button. This will open the folder containing your log files.
2. **Note the Problem:** Write down exactly what you were doing when the problem occurred and what happened.
3. **Contact Us:** Send us the information using one of these methods:

![Logs folder](images/guides/logs.png)
*Log files folder opened via the Debug tab*

### 📧 Email Support
Send your log files and problem description to:
**[golfteam.info@gmail.com](mailto:golfteam.info@gmail.com)**

### 📝 Support Form
Fill out our online support form:
**[Submit Support Request](https://forms.gle/xaKGrrvCivJgm5dHA)**

> **Note:** Please include your log files when contacting support—they help us diagnose the issue much faster!

---

## Links

- [Home](README.md)
- [Download](README.md#download)
- [FAQ](README.md#frequently-asked-questions)

---

© 2024 MusicBox. Music Display System.

*Elevate Your Music Experience*
