<h1 align="center" id="title">SSH-AL3RT</h1>

<p id="description">SSH Login Alert System A lightweight shell script to monitor SSH login attempts in real time. It detects successful logins from system logs extracts user and IP information and sends instant alerts via email. Ideal for enhancing server security by staying informed of login activity.</p>

  
  
<h2>Features</h2>

Here're some of the project's best features:

*   Monitors system logs for successful SSH logins.
*   Extracts details such as username IP address and login timestamp.
*   Sends instant alerts via email to keep you informed.
*   Works seamlessly with popular Linux distributions (Ubuntu Debian CentOS etc.).
*   Simple setup and minimal dependencies.

<h2>Installation Steps:</h2>

<p>1. Clone the Repository</p>

```
https://github.com/ItsBeZ/ssh-slert-bash.git
```

<p>2. Install Dependencies For Debian/Ubuntu:</p>

```
sudo apt update sudo apt install mailutils geoip-bin iptables
```

<p>4. Configure the Script</p>

```
nano shell.sh
```

<p>5. Update the LOGFILE path if necessary (e.g. /var/log/secure for CentOS).</p>

```
ALERT_EMAIL="your_email@example.com"
```

<p>6. Make the Script Executable</p>

```
chmod +x shell.sh
```

<p>7. Run the Script</p>

```
sudo ./shell.sh
```

<p>8. To run in the background:</p>

```
nohup sudo ./shell.sh &
```
<h2>Built with</h2>

Technologies used in the project:

*   shell scripting
*   mailx
*   mailutils
*   geoip-bin
*   iptables
