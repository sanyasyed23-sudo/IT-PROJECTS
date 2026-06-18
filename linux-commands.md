# Linux Commands Cheat Sheet

## Navigation
| Command | What it does |
| :--- | :--- |
| `pwd` | Show current directory path |
| `ls` | List files and folders in current directory |
| `ls -la` | List all files (including hidden) with details |
| `cd` | Go to home directory |
| `cd /` | Go to root directory |
| `cd ..` | Go up one level |
| `cd foldername` | Go into a folder |

---

## File Management
| Command | What it does |
| :--- | :--- |
| `touch filename.txt` | Create an empty file |
| `mkdir foldername` | Create a new folder |
| `cp file1 file2` | Copy a file |
| `mv file1 file2` | Move or rename a file |
| `rm filename.txt` | Delete a file |
| `rm -r foldername` | Delete a folder and its contents |

---

## Viewing Files
| Command | What it does |
| :--- | :--- |
| `cat filename.txt` | Show full file content |
| `head filename.txt` | Show first 10 lines |
| `tail filename.txt` | Show last 10 lines |
| `tail -f filename.txt` | Show live updates (logs) |
| `less filename.txt` | View file page by page |
| `nano filename.txt` | Open file in text editor |

---

## Permissions
| Command | What it does |
| :--- | :--- |
| `ls -l` | Show permissions of files |
| `chmod 755 filename` | Give read/write/execute to owner |
| `chmod 644 filename` | Give read/write to owner, read to others |
| `chown user filename` | Change file owner |

---

## Processes
| Command | What it does |
| :--- | :--- |
| `ps` | Show running processes |
| `ps aux` | Show all processes with details |
| `top` | Show real-time system processes |
| `htop` | Interactive process viewer (better than top) |
| `kill PID` | Stop a process by ID |
| `kill -9 PID` | Force stop a process |

---

## Searching
| Command | What it does |
| :--- | :--- |
| `grep "text" filename.txt` | Search for text in a file |
| `grep -r "text" /folder` | Search for text in all files in a folder |
| `find / -name "filename"` | Find a file by name |
| `find / -type f -name "*.txt"` | Find all .txt files |

---

## Disk & Memory
| Command | What it does |
| :--- | :--- |
| `df -h` | Show disk space (human readable) |
| `du -sh /folder` | Show folder size |
| `free -m` | Show memory usage (MB) |
| `free -h` | Show memory usage (human readable) |

---

## System Info
| Command | What it does |
| :--- | :--- |
| `uname -a` | Show system information |
| `whoami` | Show current user |
| `hostname` | Show computer name |
| `date` | Show current date and time |
| `uptime` | Show how long system has been running |

---

## Networking
| Command | What it does |
| :--- | :--- |
| `ping google.com` | Test network connection |
| `ifconfig` | Show network interfaces |
| `ip addr` | Show IP addresses |
| `netstat -tuln` | Show open ports |

---

## SSH (Connecting to Remote Servers)
| Command | What it does |
| :--- | :--- |
| `ssh user@ip-address` | Connect to a remote server |
| `ssh -i key.pem user@ip` | Connect using a private key file |
| `scp file.txt user@ip:/path` | Copy file to remote server |

---

## System Control
| Command | What it does |
| :--- | :--- |
| `sudo apt update` | Update package list (Ubuntu) |
| `sudo apt upgrade` | Upgrade all packages (Ubuntu) |
| `sudo systemctl restart service` | Restart a service |
| `sudo systemctl status service` | Check service status |
| `shutdown -h now` | Shut down immediately |
| `reboot` | Restart system |

---

## My Practice Notes
- I installed Ubuntu on VMware
- I practice these commands daily
- I use `df -h` to check disk space on my home lab
- I use `grep` to search logs when troubleshooting
