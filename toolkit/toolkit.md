Bash CLI Toolkit

This is my personal Bash toolkit for learning Linux system administration, cybersecurity (blue team), and daily CLI workflows. These are real commands I use regularly.

Basic Navigation & System Info

I use these commands regularly in my web infrastructure and cybersecurity work.

bash

`pwd`                     # Show current working directory  

`ls -lah`                 # List all files, including hidden, with details  

`cd ..`                   # Go up one directory  

`mkdir new-folder`        # Create a new folder  

`whoami`                  # Show current logged-in username  

`hostname`                # Show system hostname  

`cat /etc/os-release`     # Show OS version info  

`uname -a`                # Kernel and system architecture  

`uptime`                  # System uptime and load average  

`free -h`                 # RAM and swap usage in human-readable format  

`df -h`                   # Disk usage by mounted filesystem  

`top`                     # Real-time system processes  

`htop`                    # enhanced version of top  

`vmstat 1 5`              # System performance snapshots  

`cd /var/log`             # Change to the log directory  

`ls -lh`                  # View log file sizes and names  

`journalctl -xe`          # Show system errors and events  

`sudo less /var/log/syslog`     # View general system log  

`sudo less /var/log/auth.log`   # View authentication logs  

`sudo tail -f /var/log/syslog`  # Follow syslog in real time  

`ip a`                           # Show network interfaces and IPs  

`ping google.com`                # Test connection  

`traceroute example.com`         # Trace the route to a host  

`ss -tuln`                       # Show open ports and listening sockets  

`netstat -anp`                   # (If installed) show detailed network info  

`curl -I https://example.com`   # Show HTTP headers  

`wget https://example.com`      # Download file from web  

`nmap -sV 192.168.1.000`           # Scan ports and detect versions  

`whois sunpathseo.com`              # Whois info  

`dig example.com`               # DNS lookup  

`nslookup example.com`          # DNS alternative  

`masscan -p1-65535 192.168.1.000` # Super fast port scanner  

`nikto -h http://example.com`   # Web vulnerability scanner  

`wpscan --url https://site.com` # WordPress vulnerability scanner  

`cd ~/Documents/bash-toolkit`        # Move into your repo folder  

`git init`                           # Start Git repo  

`git add .`                          # Stage all files  

`git commit -m "Initial commit"`     # Save your changes  

`git branch -M main`                 # Rename branch to main  

`git remote add origin https://github.com/bornagaincoder7/bash-toolkit.git`  

`git push -u origin main`            # Push to GitHub  

`crontab -l`                          # List your current cron jobs  

`crontab -e`                          # Edit your cron jobs  

`cat /etc/crontab`                   # View system-wide cron jobs  

`sudo tail -f /var/log/syslog`       # View cron jobs running live  
