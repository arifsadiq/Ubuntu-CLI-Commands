# I) System Information
hostnamectl : Shows current hostname and related details

uname -a : Displays all system information

timedatectl status : Shows system time

lscpu : Lists CPU architecture information

# II) System Monitoring and Management
top : Displays real-time system processes

htop : An interactive process viewer (needs installation)

df -h : Shows disk usage in human-readable format

free -m : Displays free and used memory in MB

kill <process id> : Terminate a process

# III) Running Commands
[command] & : Runs command in the background

jobs : Displays background commands

fg <command num> : Bring commands to the foreground

# IV) Service Management
sudo systemctl start <service> : Start a service

sudo systemctl stop <service> : Stop a service

sudo systemctl status <service> : Check the status of a service

sudo systemctl enable <service> : Enable a service to start automatically at boot time

sudo systemctl reload <service> : Reloads a service’s configuration without interrupting its operation

journalctl -f : showing new log messages in real time

journalctl -u [unit name] : Displays logs for a specific system

# V) Cron Jobs & Scheduling
crontab -e : Edit cron jobs for the current user

crontab -l : Lists cron jobs for the current user

crontab -r : Remove a cron job

sudo crontab -u username -e : Edit crontab for another user
