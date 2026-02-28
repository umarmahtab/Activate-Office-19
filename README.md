⚠️ DISCLAIMER: For Educational and Project Testing Purposes Only

This script is intended solely for:

Development and testing environments

Personal lab setups

Educational demonstrations

Legitimate licensed scenarios where you own a valid license




📋 Description
A simple batch script to activate Windows Server 2019 using command-line tools. This script automates the activation process by running standard Windows activation commands.

🚀 Quick Start
Prerequisites
Windows Server 2019 operating system

Administrative privileges

Valid product key or KMS client setup key

Usage Instructions
Create the batch file:

Copy the provided code

Open Notepad

Paste the code

Save as activate_windows.bat (ensure file extension is .bat, not .txt)

Run as Administrator:

Right-click on the saved .bat file

Select "Run as administrator"

Press Enter when prompted

Wait for the process to complete

🔧 How It Works
The script executes three main commands:

slmgr /ipk - Installs the product key

slmgr /skms - Sets the KMS server for activation

slmgr /ato - Attempts online activation

⚠️ Important Notes
Run as Administrator: The script MUST be executed with administrator privileges

Internet Connection: Required for online activation

Firewall: Ensure KMS ports are not blocked

Product Keys: Different editions may require different product keys

📝 Legal Considerations
This script is provided for educational purposes. Users are responsible for:

Complying with Microsoft's licensing terms

Using appropriate, legally obtained product keys

Ensuring they have the right to activate the software

🔒 Security
The script only uses built-in Windows commands

No external downloads or installations

All actions are logged by Windows

🤝 Contributing
Feel free to fork this repository and submit pull requests for improvements.

📄 License
MIT License - See LICENSE file for details

⭐ Support
If you find this helpful, give it a star! For issues, open a GitHub issue.
