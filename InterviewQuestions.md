# InterviewQuestions

-  **1. Self Introduction**:
  
My self Sharath Kumar, Over IT is 5.3 years of experince. Devops which having 4 years of experince.
As a devops i have great experince in building the applications, Testing the applications. Deploying the applications in various environment. Ensure on the application run smoothly with out end user failing issue

Coming to technologies like:

Git and Github - Version control Tool.
By developer worked on the git.
Once code is ready they will push the code into git and gitub repository. Will use GitHub is Repostory where will store the appliation sorce code
I worked with Maven as a build tool, to create binary artifact file
And Jenkins as a Continous Intergartion tool, With the help of jenkins will continously building , testing and deploying the applications. In the jenkins am taking care of adminstartion activies
like creating the jobs, installing the pulgins and providing the user level access to developer and testers
We are following the micro service architecture applications. What ever application is run it create small part of micro service applications
We will perform the individual development and releases on various environments. To manage this micro services orchitecture will kubernetes.

Coming Monitoring Prosfective:

i worked with promotheous and grafana as a monitoring tool
What ever applications and What ever production application running on onpremisis.
Entire application is monitored by premeteous and Grafana. Grafana loki for the log issues finding
And worked with Jira as a ticketing tool and X-matters as page rasing tool. Apart for Configuring and management tools like ansible
Security tools like: Sonar Qube and Trivy. We are following the agile and crum Metodology. We are following the sprint mechanisum

-  **2. Everyday basic commands**


| Command | Description                    | Example                 |
| ------- | ------------------------------ | ----------------------- |
| `pwd`   | Show current working directory | `pwd`                   |
| `ls`    | List files and folders         | `ls -ltr`               |
| `cd`    | Change directory               | `cd /etc`               |
| `mkdir` | Create directory               | `mkdir logs`            |
| `rmdir` | Remove empty directory         | `rmdir old_logs`        |
| `cp`    | Copy files/folders             | `cp file1.txt /tmp/`    |
| `mv`    | Move or rename file            | `mv app.log /var/logs/` |
| `rm`    | Remove file or directory       | `rm -rf temp/`          |
| `touch` | Create empty file              | `touch test.txt`        |

📂 2. Viewing and Reading Files
| Command   | Description          | Example                   |
| --------- | -------------------- | ------------------------- |
| `cat`     | View file content    | `cat /etc/hosts`          |
| `less`    | Scroll through file  | `less access.log`         |
| `head`    | Show first few lines | `head -n 10 syslog`       |
| `tail`    | Show last few lines  | `tail -n 20 syslog`       |
| `tail -f` | Watch logs live      | `tail -f /var/log/syslog` |
| `wc -l`   | Count lines          | `wc -l access.log`        |
| `grep`    | Search for keywords  | `grep "error" app.log`    |

⚙️ 3. File Management & Compression
| Command    | Description             | Example                        |
| ---------- | ----------------------- | ------------------------------ |
| `find`     | Search files by name    | `find /var -name "*.log"`      |
| `du -sh`   | Check folder size       | `du -sh /home/user/`           |
| `df -h`    | Disk usage summary      | `df -h`                        |
| `tar -czf` | Compress folder         | `tar -czf backup.tar.gz /data` |
| `tar -xzf` | Extract compressed file | `tar -xzf backup.tar.gz`       |
| `zip`      | Create zip archive      | `zip -r logs.zip /var/log/`    |
| `unzip`    | Extract zip             | `unzip logs.zip`               |

🧩 4. Permissions & Ownership
| Command | Description               | Example                        |
| ------- | ------------------------- | ------------------------------ |
| `chmod` | Change file permissions   | `chmod 755 script.sh`          |
| `chown` | Change file owner         | `chown user:group file.txt`    |
| `ls -l` | Show permissions of files | `ls -l /etc/`                  |
| `sudo`  | Run command as root       | `sudo systemctl restart nginx` |

🧑‍💼 5. User Management
| Command     | Description             | Example               |
| ----------- | ----------------------- | --------------------- |
| `whoami`    | Show current user       | `whoami`              |
| `id`        | Show user ID and groups | `id`                  |
| `adduser`   | Create new user         | `sudo adduser devops` |
| `passwd`    | Change password         | `passwd devops`       |
| `su - user` | Switch user             | `su - root`           |
| `exit`      | Exit session            | `exit`                |

🌐 6. Networking
| Command             | Description               | Example                             |
| ------------------- | ------------------------- | ----------------------------------- |
| `ping`              | Test network connectivity | `ping google.com`                   |
| `ifconfig` / `ip a` | View IP details           | `ip a`                              |
| `hostname -I`       | Show IP address           | `hostname -I`                       |
| `curl`              | Check endpoint/API        | `curl -I https://example.com`       |
| `wget`              | Download file             | `wget https://example.com/file.zip` |
| `ss -tuln`          | Check listening ports     | `ss -tuln`                          |
| `scp`               | Copy file over SSH        | `scp file.txt user@server:/tmp/`    |
| `ssh`               | Connect to remote host    | `ssh user@server`                   |

🧮 7. Process & System Monitoring
| Command       | Description                                | Example        |             |
| ------------- | ------------------------------------------ | -------------- | ----------- |
| `ps aux`      | List all processes                         | `ps aux        | grep nginx` |
| `top`         | Monitor live processes                     | `top`          |             |
| `htop`        | Better process viewer (install separately) | `htop`         |             |
| `free -h`     | Memory usage                               | `free -h`      |             |
| `uptime`      | Show system uptime                         | `uptime`       |             |
| `kill -9 PID` | Kill process by PID                        | `kill -9 1234` |             |
| `df -h`       | Disk space                                 | `df -h`        |             |
| `vmstat 1`    | System performance summary                 | `vmstat 1`     |             |

🧰 8. Package Management
| Command       | Description             | Example                  |              |
| ------------- | ----------------------- | ------------------------ | ------------ |
| `apt update`  | Refresh package list    | `sudo apt update`        |              |
| `apt install` | Install software        | `sudo apt install nginx` |              |
| `apt remove`  | Remove software         | `sudo apt remove nginx`  |              |
| `dpkg -l`     | List installed packages | `dpkg -l                 | grep docker` |
| `yum install` | Install package         | `sudo yum install httpd` |             |
| `yum remove`  | Uninstall package       | `sudo yum remove httpd`  |             |
| `yum update`  | Update system           | `sudo yum update`        |             |
| `rpm -qa`     | List installed RPMs     | `rpm -qa                 | grep nginx` |

🔐 9. System and Service Management
| Command                        | Description                       | Example                    |
| ------------------------------ | --------------------------------- | -------------------------- |
| `systemctl status`             | Check service status              | `systemctl status nginx`   |
| `systemctl start/stop/restart` | Manage services                   | `systemctl restart docker` |
| `service`                      | Legacy command to manage services | `service ssh restart`      |
| `journalctl -u`                | View logs for service             | `journalctl -u nginx -f`   |
| `reboot`                       | Reboot system                     | `sudo reboot`              |
| `shutdown now`                 | Shutdown system                   | `sudo shutdown now`        |

🧩 10. Useful Everyday Utilities
| Command         | Description              | Example              |
| --------------- | ------------------------ | -------------------- |
| `date`          | Display system date/time | `date`               |
| `cal`           | Display calendar         | `cal`                |
| `clear`         | Clear screen             | `clear`              |
| `history`       | Show command history     | `history`            |
| `alias`         | Create short command     | `alias ll='ls -la'`  |
| `echo`          | Print text               | `echo "Hello World"` |
| `man <command>` | Manual for a command     | `man grep`           |

🧠 Bonus: Common Daily Use Combos
| Task                        | Command                             |            |
| --------------------------- | ----------------------------------- | ---------- |
| Check last 100 lines of log | `tail -n 100 /var/log/syslog`       |            |
| Monitor a log in real time  | `tail -f /var/log/nginx/access.log` |            |
| Find large files            | `find / -type f -size +100M`        |            |
| Check system load           | `uptime`                            |            |
| Check IP                    | `curl ifconfig.me`                  |            |
| Search running process      | `ps aux                             | grep java` |
| Check port usage            | `ss -tuln                           | grep 8080` |
| List cron jobs              | `crontab -l`                        |            |
| Backup directory            | `tar -czf backup.tar.gz /etc`       |            |
| View disk usage sorted      | `du -h --max-depth=1 /              | sort -hr`  |


-  **3. What does ps stand for?**: Process Staus

It’s a command-line utility used to display information about the currently running processes on a system.
```sh
ps	Shows processes running in the current shell
ps -e or ps -A	Show all processes running on the system
ps -f	Show full-format listing (includes PPID, CMD, etc.)
ps aux	Show detailed info of all processes (commonly used)
ps -ef	Another full listing format (used in most scripts)
```
- **4.Disk usage and df**

disk usage commands:
```sh
Files:
df -h
df -ah

Directories:
du -h
du -sh
du -sch*
```
-  **5. ELK stack.**:
ELK stands for:

**Elasticsearch + Logstash + Kibana**: these tools form a powerful centralized logging and monitoring system used to collect, process, and visualize logs in real time.

✅ Centralized log management
✅ Real-time application monitoring
✅ Infrastructure troubleshooting
✅ Security event monitoring (SIEM)
✅ Business analytics (via log data)

| Task                 | Command                           |
| -------------------- | --------------------------------- |
| Start Elasticsearch  | `systemctl start elasticsearch`   |
| Start Logstash       | `systemctl start logstash`        |
| Start Kibana         | `systemctl start kibana`          |
| Verify Elasticsearch | `curl -X GET "localhost:9200"`    |
| Access Kibana        | Browser → `http://localhost:5601` |

-  **6. ⚙️ What is ulimit in Linux?**:

ulimit stands for User Limit —
It controls the resource limits available to processes started by a user.

You use it to restrict or view system resource consumption like:

Number of open files
Number of processes
Maximum file size
Stack size, memory, CPU time, etc.
| Command                          | Description                    |
| -------------------------------- | ------------------------------ |
| `ulimit -a`                      | Show all limits                |
| `ulimit -n`                      | Show open file limit           |
| `ulimit -u`                      | Show process limit             |
| `ulimit -Sn`                     | Show soft limit                |
| `ulimit -Hn`                     | Show hard limit                |
| `ulimit -n 65535`                | Increase file descriptor limit |
| Edit `/etc/security/limits.conf` | Make changes permanent         |
 
-  **7. How to set up a passwordless connection.**:

setting up a passwordless SSH connection is one of the most common tasks for DevOps, SRE, and Platform Engineers.

Passwordless SSH uses public/private key authentication instead of passwords.
| File             | Path                     | Permission |
| ---------------- | ------------------------ | ---------- |
| Private Key      | `~/.ssh/id_rsa`          | `600`      |
| Public Key       | `~/.ssh/id_rsa.pub`      | `644`      |
| Authorized Keys  | `~/.ssh/authorized_keys` | `600`      |
| `.ssh` Directory | `~/.ssh/`                | `700`      |

-  **8. Soft link and hard link**:

Hard Link- A hard link is another directory entry for the same inode. Both Files share the same data

Deleting one doesn’t affect the other.  
Works only for files (not directories)  
Works within the same filesystem

Soft Link: A soft link (or symlink) is like a shortcut or pointer to another file’s name.
It’s a small file that contains the path of the target file.

Can link files or directories  
Works across filesystems 
If the original file is deleted → link becomes broken (dangling link)
| Task                          | Command                           |
| ----------------------------- | --------------------------------- |
| Create hard link              | `ln file1.txt file1_hard.txt`     |
| Create soft link              | `ln -s file1.txt file1_soft.txt`  |
| List with inode numbers       | `ls -li`                          |
| Delete link                   | `rm linkname`                     |
| View what a symlink points to | `ls -l` or `readlink -f linkname` |


-  **9. ⚙️ How to Check System Load in Linux**:

To check the Load, Cpu, memory, process details
| Command         | Description                                   |
| --------------- | --------------------------------------------- |
| `uptime`        | Shows load averages                           |
| `top` / `htop`  | Real-time CPU, memory, and process monitoring |
| `vmstat`        | System performance (CPU, memory, I/O)         |
| `sar`           | Historical performance stats                  |
| `/proc/loadavg` | Direct kernel load info                       |

-  **10. How to remove a directory**:

```sh
rmdir directory_name
rmdir -r directory_name
rm -rf files
```
- **11. If you've run the rm command on the server and deleted everything, how will you inform the client and your manager?**:

I want to inform you that during maintenance, an rm command was accidentally run, resulting in deletion of [affected files/directories]. I have immediately stopped further operations and am now working on restoring from backup. I will provide a full impact assessment and timeline for recovery shortly.

*Prevention Measures (Follow-Up)*

Enable file system snapshots / backups

Implement rm safeguards:

Use rm -i for interactive deletion

Alias rm to rm -i for safety

Restrict root user direct deletions

Automate critical file protection — immutable flags, access control

Incident review meeting — discuss root cause and preventive actions

-  **12. Monolithic, Microservices, SNMP.**:
1️⃣ Monolithic Architecture

A monolithic application is a single unified unit where all components (UI, business logic, database access) are tightly coupled and run as one process.

Characteristics:

All modules are part of one codebase.
Single deployment — updating any module requires redeploying the whole app.

2️⃣ Microservices Architecture

Microservices break the application into small, independent services. Each service handles a specific business function and communicates over APIs (usually REST/gRPC).

Characteristics:

Each service is independently deployable. 
Services can be written in different languages. 
Uses lightweight communication (HTTP, message queues).

3️⃣ SNMP (Simple Network Management Protocol): 
SNMP is a protocol used to monitor and manage network devices like routers, switches, servers, and printers.

Key Components:

Managed Devices → Routers, switches, servers.

SNMP Agent → Software on device that reports status.

SNMP Manager → Central system that polls devices and collects data.


-  **13. How to configure SSH login**:

If ssh is not configured in local need to perform the below steps

Step 1: Install OpenSSH server (if not installed)
```sh
# Ubuntu/Debian
sudo apt update
sudo apt install openssh-server

# RHEL/CentOS
sudo yum install openssh-server
```
Step 2: Start and enable SSH service

```sh
sudo systemctl start ssh
sudo systemctl enable ssh
```
Step 3: Check SSH status
```sh
sudo systemctl status ssh
ssh username@server_ip
```
- **14. What is BIOS?**:


-    **1. Self Introduction**:
-     **1. Self Introduction**:
-  **1. Self Introduction**:
