# home-network-diagram
this diagram outline internet  connectivity between ISP (internet service provider), private network, and End device 
Home Network Overview

Your home network is built around a router connected to your ISP through a modem. The router manages both wired and wireless connections, providing internet access and internal networking capabilities.

1. Internet Connection
	•	ISP Connection: Your network connects to the internet via fiber, DSL, or coaxial cable.
	•	Modem: This device receives the internet signal and passes it to your router.

2. Core Network Components
	•	Router: Acts as the default gateway for all devices, assigning IP addresses and managing traffic. It supports:
	•	Firewall protection
	•	DNS, DHCP, NAT, and Wireless Access Point (WAP) functionalities
	•	Router IP: 192.168.1.1
	•	Switch (if applicable): Provides additional Ethernet ports for wired devices.

3. Connected Devices

Your network includes a mix of wired and wireless devices:
	•	Smart Home Devices (connected via WiFi)
	•	Smart TV
	•	Security Camera
	•	Personal Devices (WiFi or Ethernet)
	•	Smartphone
	•	Laptop
	•	PC

4. Network Configuration
	•	Network Addressing:
	•	Internal Network: 192.168.1.0/24
	•	Devices receive private IP addresses from the router.
	•	Wired Connections: Use Ethernet cables (RJ45)
	•	Wireless Connections: Provided through the router’s WiFi capabilities.

5. Security & Advanced Configurations
	•	Firewall: Protects the network from external threats.
	•	DHCP & DNS Services: The router dynamically assigns IPs to devices.
	•	NAT (Network Address Translation): Manages internet access for multiple devices.

Router Settings 


1. Change Router Admin Password

To improve security, change the default admin password of your router.
	1.	Access Router Settings
	•	Open a web browser and enter 192.168.1.1 (or your router’s gateway IP).
	•	Log in with your admin username and password (default credentials are usually found on a sticker on the router).
	2.	Change the Password
	•	Navigate to Administration, System, or Management Settings (depending on your router model).
	•	Look for the Change Password or Router Login Password section.
	•	Enter a new strong password and save changes.

2. Change SSID and WiFi Password
	1.	Navigate to Wireless Settings
	•	Go to Wireless or WiFi Settings in your router’s interface.
	2.	Change SSID (WiFi Network Name)
	•	Locate the field labeled SSID or Network Name and enter a new one.
	3.	Change WiFi Password
	•	Find the Security or Passphrase section.
	•	Ensure WPA2/WPA3 encryption is enabled (avoid WEP as it’s outdated).
	•	Enter a strong password and save changes.

3. Hide SSID (WiFi Network Name)
	1.	Go to Wireless Settings.
	2.	Find the option “SSID Broadcast” or “Visibility”.
	3.	Select Disable/Hide SSID and apply changes.
	•	Note: Devices will need to manually enter the SSID and password to connect.

4. Enable Guest WiFi & Change Default Settings
	1.	Navigate to Guest Network or Wireless Guest Access.
	2.	Enable Guest WiFi and set a separate SSID.
	3.	Configure:
	•	Access Type: Internet-only (prevents access to local network devices).
	•	Bandwidth Control: (Optional) Limit the guest network speed.
	•	Security: Enable WPA2/WPA3 with a separate password.
	4.	Save changes.

5. Set DHCP Scope (IP Address Range)
	1.	Go to LAN Settings or DHCP Settings.
	2.	Locate DHCP Server Configuration.
	3.	Set:
	•	Starting IP Address: Example: 192.168.1.100
	•	Ending IP Address: Example: 192.168.1.200
	•	Subnet Mask: Usually 255.255.255.0
	4.	Save settings.

6. Set DHCP Reservation for a Printer
	1.	Go to DHCP Reservation or Static DHCP in router settings.
	2.	Find the printer’s MAC Address (you can check connected devices or find it in the printer settings).
	3.	Assign a fixed IP Address (e.g., 192.168.1.50).
	4.	Save and apply changes.

7. Update Router Firmware
	1.	Go to Administration > Firmware Upgrade.
	2.	Click Check for Updates (some routers require downloading the update from the manufacturer’s website).
	3.	If an update is available:
	•	Click Update and wait for the router to restart.
	•	Do not turn off the router during the update.

8. Disable UPnP (Universal Plug and Play)
	1.	Navigate to Advanced Settings or NAT & Port Forwarding.
	2.	Locate UPnP Settings.
	3.	Select Disable and save changes.
	•	UPnP can be a security risk as it allows devices to open ports automatically.

Final Step: Restart Your Router
