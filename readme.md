# 🖥️ PixelOS

**Lightweight Cross-Platform System in Python**

---

## 🚀 About PixelOS

**PixelOS** is a modular Windows subsystem written in Python. It’s built to:

- **Extend Windows functionality** via scripts and APIs.  
- **Simplify task automation** with Python.  
- **Integrate third-party tools and Python libraries** into Windows seamlessly.  

It’s ideal for developers, system administrators, and power users who want to craft custom solutions for Windows environments.

---

## ⚡ Features

✅ **Modularity**  
Add or remove components without restarting the core.

✅ **Python Integration**  
Leverage Python’s full ecosystem — standard libraries plus third-party packages like `pywin32`, `psutil`, and more.

✅ **Automation**  
Build powerful scripts to manage processes, files, networks, and other Windows resources.

✅ **Cross-Platform Compatibility:**  
- Runs on Windows 10/11
- In MacOS coming soon...
- Linux Distros Arch, Ubuntu Based

✅ **Windows API Access**  
Access Windows APIs directly through Python — e.g. registry management, window control, and driver interactions.

---

## 🛠️ Installation

**Requirements:**

- Python 3.10+
- Windows 10/11
- Arch Linux 2024+
- Ubuntu 22.04+
- Ubuntu Based
- Arch Based

### 1. Clone the repository

```bash
git clone https://github.com/MrT1mosha/PixelOS.git
```
### 2. Install Dependencies

```bash
cd PixelOS
pip install -r requirements.txt
```
### 2,5. Change Config

```python config.py
# --- Apps ---
explorerPath = "C:/Users/yourusername/PathToPixelOS/apps/explorer.py"
# And Other
# --- Images ---
start_img = "C:/Users/yourusername/PathToPixelOS/icons/start.png"
# And Other
```

### 3. Launch PixelOS

```bash
python main.py
```

## 4. 📦 Usage

### Basic Commands

```bash
# Launch PixelOS termina
pixel-terminal

# Get system information
pixel-info

# Manage processes
pixel-process --list
pixel-process --kill <PID>

# File operations
pixel-file --copy <src> <dst>
pixel-file --delete <path>
```
### Example: Automation via Python

```python
# pixel_script.py
import pixelos

# Get active processes
processes = pixelos.get_active_processes()

# Kill a process by name
pixelos.kill_process_by_name("notepad.exe")
```

## **📬 Contact:**
- Telegram: www.t.me/pixelOS_dev
- Email: mrdevcommand@gmail.com
- Documentation: coming soon...
