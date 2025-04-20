<h1 align="center" id="title">p0rt-Monitor</h1>

<p id="description">The Port Monitoring Tool is a lightweight shell script that monitors open ports on a system in real-time. It helps detect changes in port activity such as newly opened or closed ports and provides alerts for suspicious or unauthorized behavior. This tool is ideal for system administrators and security enthusiasts to enhance network monitoring and improve system security.</p>

  
  
<h2>Features</h2>

Here're some of the project's best features:

*   Real-Time Monitoring: Continuously scans open ports at defined intervals.
*   Change Alerts: Detects and reports newly opened or closed ports.
*   Customizable: Allows configuration of monitoring intervals and alert mechanisms.
*   Lightweight: Minimal resource usage with fast execution.
*   Extensible: Can be integrated with logging systems or email alerts for advanced functionality.

<h2>🛠Installation Steps:</h2>

<p>1. Clone the repository:</p>

```
git clone https://github.com/ItsBeZ/ssh-slert-bash
```

<p>2. Make the script executable:</p>

```
chmod +x port_monitor.sh
```

<p>3. Run the script:</p>

```
./port_monitor.sh
```

<p>4. Modify the monitoring interval (MONITOR_INTERVAL) if needed by editing the script.</p>

```
MONITOR_INTERVAL=10  # Time in seconds between checks
```

*    Bug Reports: Open an issue with a detailed description of the problem. 
*    Feature Requests: Suggest new features via the issue tracker. 
*    Code Contributions: Fork the repository. 
*    Create a feature branch (git checkout -b feature-name). 
*    Commit your changes (git commit -m "Description of changes"). 
*    Push to your fork and submit a pull request.

  
  
<h2>Built with</h2>

Technologies used in the project:

*   Shell Scripting: Core implementation.
*   Netstat: For retrieving port and network information.
*   Linux Tools: awk sed grep and comm for data processing.
