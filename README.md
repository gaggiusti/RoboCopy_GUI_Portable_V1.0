# RoboCopy All In One GUI V1.0

A free, intuitive graphical user interface (GUI) for the Windows command-line tool RoboCopy. Designed by Gianpaolo Aggiusti, this software simplifies file and folder copy and synchronization operations, making them accessible even to less experienced users. Its purpose is to provide complete control over RoboCopy through a user-friendly interface, eliminating the need to memorize complex commands.

DOWNLOAD LINKS at the bottom of the page.

---

## About Robocopy

**Robocopy** (Robust File Copy) is a powerful file copy utility developed by Microsoft for Windows. It is designed for reliable, high-performance copying of files and directories, supporting advanced features such as mirroring, incremental updates, and robust error recovery.

- **Windows NT 4.0, Windows 2000, Windows XP/Server 2003:**  
  Robocopy was available as part of the Windows Resource Kit.

- **Windows Vista and later (including Windows 7, 8, 10, and 11):**  
  Robocopy is built directly into the operating system and accessible from the command line.

- **Windows Server 2008 and later:**  
  Robocopy is included by default.

> **Note:** Robocopy must be present on your system. If you are using Windows 7 or newer, no additional installation is required.

---

## Features

- **Graphical User Interface (GUI):** Intuitive interface for RoboCopy.
- **Path Selection:** Easily select source and destination paths.
- **Copy Presets:** Predefined options for Mirror Copy, Incremental Copy, and Move.
- **Manual & Advanced Options:** Enter custom RoboCopy options or use a visual selector for common flags and parameters.
- **Command Preview:** See the full RoboCopy command before execution.
- **Real-time Console Output:** Monitor RoboCopy output directly.
- **Log Management:** Automatic log file generation and quick access.
- **Performance Monitoring:** Real-time graphs (disk/network speed, CPU/RAM usage).
- **Progress Bar:** File copy progress indicator.
- **Integrity Verification:** SHA256 hash verification for copied files (not available for move operations).
- **Network Credential Management:** Popup for protected network (UNC) paths.
- **Save/Load Jobs:** Store and recall configurations (`.rjob` files).
- **Multi-language Support:** English, Italian, and German with language selection.
- **Swap Paths Button:** Quickly swap source and destination.
- **Splash Screen & Welcome/Donation Window:** Informative popups at startup.
- **Help/About Menu:** Access to EULA, Changelog, third-party notices, and program info.

---

## Installation

RoboCopy All In One GUI V1.0 is portable software; no installation is required.

- **Operating System:** Windows 7 or higher.
- **Dependencies:** None. The .exe includes all required Python libraries (`psutil`, `matplotlib`).

### Steps:

1. Download `RoboCopy All In One GUI V1.0.exe`.
2. Move the `.exe` to your desired folder.
3. Double-click to launch.

---

## Usage

- **Select Source and Destination** folders.
- **Choose a preset** (Mirror Copy, Incremental Copy, Move) or customize options.
- **Review the command preview** for transparency.
- **Start RoboCopy** and monitor progress and performance.
- **Check logs** and verify file integrity as needed.

### Example Workflows

- **Mirror Copy:**  
  - Select source and destination.
  - Check "Mirror Copy (/MIR)".
  - Click "Start RoboCopy".

- **Incremental Copy:**  
  - Select paths.
  - Check "Incremental Copy".
  - Click "Start RoboCopy".

- **Custom Options:**  
  - Enter flags in "Manual Options" (e.g., `/XO /Z`).
  - Or use the advanced options window.

---

## FAQ

- **Is the software truly free?**  
  Yes, for personal and commercial use.

- **Can I use it on multiple computers?**  
  Yes, unlimited PCs.

- **Do I need to install Robocopy separately?**  
  No; it is included in Windows 7 and newer.

- **Does it modify my source files?**  
  No, unless using "move" options (`/MOV` or `/MOVE`).

- **Why is verification unavailable for move operations?**  
  Verification compares source/destination files. After a move, the source is deleted.

---

## License

Distributed under the terms of the End-User License Agreement (EULA) included in the package. Freeware: use, copy, and distribute freely (unaltered, free of charge).  
**Contact:** Gianpaolo Aggiusti ([g.aggiusti@gmail.com](mailto:g.aggiusti@gmail.com))

---

## Third-Party Notices

- **Python** (PSF License)
- **Tkinter** (BSD-style)
- **Matplotlib** (BSD-style)
- **psutil** (BSD 3-clause)
- **Robocopy** (Microsoft Windows component; subject to the Windows license)

See `Third party notices_EN.txt` for full details.

---

## Changelog

See [Changelog_EN.txt](./Changelog_EN.txt) for version history.

---

## Contact & Donations

For questions, suggestions, or bug reports:  
**Email:** [g.aggiusti@gmail.com](mailto:g.aggiusti@gmail.com)

Support development via [PayPal Donation](https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=g.aggiusti@gmail.com&item_name=Donation+for+RobocopyGUI)

DOWNLOAD LINK: http://bit.ly/3Io03oh

---
