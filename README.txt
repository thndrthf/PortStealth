
PortStealth v1.0 Alpha

Description:
PortStealth is a security tool designed to bind to common vulnerable ports and spoof connection attempts. 
The tool logs all incoming connection attempts and sends deceptive information to make the probing device 
believe it has found a vulnerable system, while stealthily recording all activity. 
It features two modes: PASSIVE mode logs connection attempts, while ACTIVE mode responds with spoofed data.

Key Features:
- Monitors common ports like SSH, HTTP, HTTPS, MySQL, RDP, etc.
- Logs connection attempts and provides macOS notifications when a connection is detected.
- Active mode responds with fake vulnerable system data to deceive attackers.
- Passive mode only logs the activity without sending responses.
- Simple user interface with a toggle button to enable/disable protection and switch modes.

How to Use:
1. Launch the application.
2. The main window will show a "PROTECTED" button indicating that ports are blocked.
3. To block ports, simply click the "PROTECTED" button; it will switch to "UNPROTECTED."
4. A toggle button allows switching between PASSIVE (default) and ACTIVE mode.
5. In ACTIVE mode, the system will send spoofed responses to attackers.
6. Connection attempts are logged and can be viewed in real-time through macOS notifications and log files.

System Requirements:
- macOS
- Python 3.x
- Tkinter for GUI
- macOS 'osascript' for notifications

Installation:
1. Ensure Python 3.x is installed.
2. Run the application using Python in your terminal.
3. Ensure you have administrative rights to bind to lower-numbered ports.

Logging:
- All logs are saved in `portstealth.log`.
- Connection attempts are recorded with timestamps and relevant details.

Security Disclaimer:
PortStealth is a tool designed for educational and security research purposes. 
Misuse of this tool for malicious purposes is strictly prohibited.

Author: 
THNDRTHF

Version:
v1.0 Alpha
