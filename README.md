# 🧠 show_hide_taskbar_windows
A script to toggle the taskbar visibility on Windows

## ✅ Description
This .bat script uses PowerShell to toggle the taskbar visibility on Windows systems. It modifies a registry key to change how the taskbar behaves based on your current settings.

## 📌 How it works
The script does the following:

Accesses the registry key:
HKCU:\Software\Microsoft\Windows\CurrentVersion\Explorer\StuckRects3
Toggles the value at position [8] (which controls taskbar visibility).
Restarts the explorer.exe process to apply changes.
## 🧰 Usage
Clone the repository:
git clone https://github.com/KamiMortem/show_hide_taskbar_windows.git 
Run the script: 
Open a terminal (CMD or PowerShell) in the project folder.
Execute:
show_hide_taskbar_windows.bat
## ⚠️ Notes
Admin permissions required: The script modifies the registry, so it may require elevated privileges.
Only works on Windows: This script is designed specifically for Windows (not compatible with macOS or Linux).
Registry backup: Always back up the registry before making critical changes.
## 📝 Limitations
Only works on Windows 10/11 versions.
May not be fully compatible with all taskbar settings (e.g., "Always on Top" mode).
