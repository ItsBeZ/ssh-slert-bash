SSH Login Alert System A lightweight shell script to monitor SSH login attempts in real time. It detects successful logins from system logs extracts user and IP information and sends instant alerts via email. Ideal for enhancing server security by staying informed of login activity.

Features:
Monitors system logs for successful SSH logins.
Extracts details such as username IP address and login timestamp.
Sends instant alerts via email to keep you informed.
Works seamlessly with popular Linux distributions (Ubuntu Debian CentOS etc.).
Simple setup and minimal dependencies.

Installation Steps:
1. Clone the Repository

https://github.com/SushantVijay/22h-al3rt.git
2. Install Dependencies For Debian/Ubuntu:

sudo apt update sudo apt install mailutils geoip-bin iptables
4. Configure the Script

nano shell.sh
5. Update the LOGFILE path if necessary (e.g. /var/log/secure for CentOS).

ALERT_EMAIL="your_email@example.com"
6. Make the Script Executable

chmod +x shell.sh
7. Run the Script

sudo ./shell.sh
8. To run in the background:

nohup sudo ./shell.sh &

Technologies used in the project:
shell scripting
mailx
mailutils
geoip-bin
iptables
