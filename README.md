⚠️ Disclaimer
Attention! This tool is designed for educational purposes and CTF enthusiasts.
It automates several common cybersecurity tasks to make learning and solving challenges easier.

Use at your own risk. The author assumes no responsibility for any misuse.
Tested only on Kali Linux; optimal performance is guaranteed on this platform.
Written in Python and Bash Script for automation of multiple security tools.
Unauthorized use of this software against systems without explicit permission is illegal. Always stay ethical.

📖 About the Tool
ffurares Cybersecurity Automation Tool is a multi-purpose security suite designed for beginners, CTF players, and ethical hackers.
It integrates multiple popular tools into a single automated interface, streamlining security testing on Kali Linux.

Key Features Include:

Feature	Description
🔑 Hash Cracker	Brute-force or dictionary-based hash cracking
🧩 Hash Generator	Generate MD5, SHA1, SHA256 hashes quickly
🌐 Nmap Scanner	Network scanning and enumeration
🚪 Gobuster	Directory/file brute-forcing
💣 MSFVenom	Payload generation for penetration testing
🕵️ Metasploit	Quick integration for exploitation tasks
🔄 Reverse Shells	Pre-built reverse shell payloads
⚙️ System Update	Update Kali Linux system and tools
🕸️ Burp Suite	Web application security testing and interception
📡 Wireshark	Network traffic capture and analysis
⚡ Bettercap	Advanced MITM and network attacks
🔐 OpenVPN Connection	Setup and connect to VPNs for secure testing
🧪 Hydra	Password brute-forcing tool for multiple protocols
🔑 SSH Key Crack	Brute-force or test SSH keys
📥 Download Most Common Tools	Auto-download commonly used pentesting tools
All these features are automated and integrated, making it easy to test and learn.

Tool Demo

⚙️ Installation
Clone the repository and install dependencies:

# 1️⃣ Clone the repo
git clone https://github.com/ffurares/ctf-toolkit.git

# 2️⃣ Enter the project folder
cd ctf-toolkit

# 3️⃣ Create a Python virtual environment
python3 -m venv myvenv

# 4️⃣ Activate the virtual environment
source myvenv/bin/activate

# 5️⃣ Install Python dependencies inside the virtual environment
pip install -r requirements.txt

# 6️⃣ Run the tool
python3 main.py
