# Win11-unistall_browser_troubleshoting
## Overview
Uninstalling a web browser in Windows 11 can be simple with just a few clicks, but sometimes it's difficult—especially when the browser refuses to uninstall due to various reasons.
As a regular user, I’ve installed multiple browsers over time. Many of them have become quite advanced, which can lead to performance issues since they run multiple background processes. This can significantly slow down your PC.

**Why do web browsers use so much memory?**
Modern browsers use a multiprocess model, where each tab, extension, and plug-in runs in its own process. This improves stability and security, but it also consumes more RAM.In fact, browser processes can consume more than 33% of your system’s memory—a huge hit, especially if you have many tabs or extensions open.On top of that, system background services like antivirus software, sync clients, and telemetry tools already take up memory. Not to mention user restrictions and group policies, which can introduce additional processes and slow things down even more.

## ✨ Features
-  🛠️ **List browser processes**: Lists all browser processes
- 🧹 **Cleans Temporary Files**: Clears system and user temp folders.
-  ❌ **Kill browser background processes**: This will stoped all background processes
-  ❌ **Delete all files in C:\Windows\Temp**: Deletes all temporary files
-  ❌ **Remove all files and folders in the Temp directory**: Removes all temporary files and folder in User\AppData 
-  ❌ **Delete browser directories**: Removes browser directories in Program Files&Program Files (x86)
- ⚙️❔**Check if the folder exists in User\AppData**: It checks does folder exit in user local programs
- 📋 **List all tasks to identify the auto-update tasks**: Checking is there any auto-update tasks of browser in Task Scheduler
- ❌ **Delete a specific auto-update task**:  Deleting specific automatic tasks like update
- ❌ **Delete all tasks containing "Update" in their name**: Alternativily, but recommended deleting all task that's run by browser like update 

## 📦 How to Use

1. **Download** or **clone** the repository.
2. Right-click the script file (`Win11-unistall-browser-troubleshoting.ps1`) → click **“Run with PowerShell”**.🚀
3. Or:
   - Open PowerShell as Administrator
   - Navigate to the script folder:
     ```powershell
     Set-Location for example "C:\Users\YourName\Desktop"
       - Run the script:
     powershell
     .\Win11-unistall-browser-troubleshoting.ps11

## 🧠 IMPORTANT 
🛠️Replace every 'your browser name', 'TaskName' with browser name where is required 

## Author
Created with care by** **Julia Ilić**👩🏻‍💻  
🇭🇷 Zagreb, Croatia  
