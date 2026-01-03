# <img src="logo.png" width=40> SquirrelBak Sender & Receiver  

SquirrelBak is a simple, secure, and silent one-way backup tool for Windows environments. It enables real-time folder synchronization from a source machine ("Sender") to an idle PC in another location ("Receiver")—with no cloud, no login, and no restore complexity.

Ideal for backing up logs, documents, OA data, or any continuously growing folder.

> 🌐 Official Website: [https://www.squirrelbak.com](https://www.squirrelbak.com)  
> ✉️ Support: [support@squirrelbak.com](mailto:support@squirrelbak.com)


## ✨  Features
- **Real-time folder monitoring** with minimal CPU and disk usage  
- **One-way sync** from Sender → Receiver (no bidirectional conflicts)  
- **Auto-resume after reboot, crash, or network interruption** (resume from breakpoint)  
- **Silent background operation** with system tray control (minimize to tray, start/stop anytime)  
- **Zero configuration restore needed** — files are stored as-is on the Receiver


## 🖥️ System Compatibility
- **Supported OS**:  
  Windows 7 / 8 / 10 / 11  
  Windows Server 2008 / 2012 / 2016 / 2019 / 2022  
- **Architecture**: Both 32-bit and 64-bit systems supported  
- **Network**: Stable LAN or WAN connection between Sender and Receiver  


## 📥 Downloads

| File Name | Architecture |
|----------|--------------|
| SquirrelBak-Sender-32.exe | 32-bit |
| SquirrelBak-Sender-64.exe | 64-bit |
| SquirrelBak-Receiver-32.exe | 32-bit |
| SquirrelBak-Receiver-64.exe | 64-bit |


## 🚀 Usage Guide

### Step 1: Setup Sender (Source PC)
1. Launch **SquirrelBak Sender** on the **source PC**.  
2. Select the local IP address and configure the **Source Folder**.  
3. Click **Start** to begin listening.  

### Step 2: Setup Receiver (Destination PC)
1. Launch **SquirrelBak Receiver** on the **destination (storage) PC**.  
2. Configure the **Sender IP** and **Destination Folder** in the Receiver UI.  
3. Click **Connect** to establish the connection and start synchronization.


## 📬 Get Help
- **FAQ**: [Frequently Asked Questions](https://www.squirrelbak.com/faq.html)
- **Help Guide**: [Detailed Usage Guide](https://www.squirrelbak.com/help-detail.html) 
- **Support**: [support@squirrelbak.com](mailto:support@squirrelbak.com) 


## 📌 Notes
- **Version Matching**:  Sender and Receiver **must be the same version** (both v1.0.0) for compatibility
- **Firewall**:  It is recommended to allow SquirrelBak through your firewall or antivirus software.  
- The Receiver **only receives data**—it never initiates connections or exposes files back to the network.
- Backups are **one-way only**: changes on the Receiver side are **not synced back** to the Sender.
- If a power or network interruption occurs, SquirrelBak will automatically restart and resume transfer once the system and network recover.


Thank you for using **SquirrelBak** — backup like a squirrel: steadily, reliably, always ready. 🐿️
