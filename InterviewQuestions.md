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
BIOS stands for Basic Input/Output System.

It is firmware stored on a small memory chip on your motherboard that initializes and tests hardware when a computer starts and loads the operating system.

- **15.How to transfer files between two servers without using FTP**:
```sh
scp [options] source_file user@remote_host:/remote/directory/
scp /home/user/file.txt ubuntu@192.168.1.10:/home/ubuntu/
scp ubuntu@192.168.1.10:/home/ubuntu/file.txt /home/user/
```
- **16. 🔹 Why Monitoring Tools Are Used**:

Monitoring tools are used to:

Track system performance – CPU, memory, disk, network.

Monitor applications – web servers, databases, microservices, APIs.

Detect issues proactively – alert on high load, downtime, errors.

Visualize metrics – dashboards, charts, and reports.

Log analysis – track errors, user behavior, security events.

Capacity planning – understand trends to scale resources effectively.

Automate incident response – integrate with alerting/notification systems.

- **17. How to check connectivity of one server from another server**:

We have different way to check connectivity here below examples
```sh
ping <remote_server_ip_or_hostname>
ssh username@remote_server_ip
telnet <server_ip> <port>
nc -zv <server_ip> <port>
curl -I http://192.168.1.10
wget --spider http://192.168.1.10
```
- **18. Port number for FTP, SFTP.**:

| Protocol | Port(s)                 | Security | Notes                              |
| -------- | ----------------------- | -------- | ---------------------------------- |
| FTP      | 21 (command), 20 (data) | Insecure | Plain text credentials, legacy use |
| SFTP     | 22                      | Secure   | Encrypted over SSH, modern usage   |

- **19. what is Runlevel**:

Definition: Runlevel is a state of init/systemd in Linux, defining which services/processes are running.
| SysVinit Runlevel | systemd Target    | Description      |
| ----------------- | ----------------- | ---------------- |
| 0                 | poweroff.target   | Shutdown         |
| 1                 | rescue.target     | Single-user mode |
| 3                 | multi-user.target | Multi-user CLI   |
| 5                 | graphical.target  | GUI mode         |
| 6                 | reboot.target     | Reboot           |

- **19. fstab**:

fstab stands for File System Table.

It is a configuration file in Linux located at:
```
/etc/fstab
```
Purpose: Defines how disk partitions, storage devices, and remote filesystems are automatically mounted when the system boots.
- **20. What is the command to check the processes that are running and CPU utilization?**:

Below different commands are used to find
```
ps -ef
top
htop
vmstat
# List the top 10 cpu using processes
ps -eo pid,ppid,cmd,%mem,%cpu --sort=-%cpu | head -n 10
```
- **21. Explain about APM**:

APM = Application Performance Monitoring (or Application Performance Management)

Focuses on monitoring, managing, and improving the performance of software applications.

🔹 Advantages of APM

Performance Monitoring

Tracks response times, latency, and throughput to ensure the application is fast and responsive.

Error Detection and Resolution

Identifies crashes, exceptions, or failed transactions quickly.

Helps reduce downtime and improve reliability.

Resource Optimization

Monitors CPU, memory, database queries, and other resources.

Helps optimize infrastructure and application performance.

Improved User Experience

Monitors end-user interactions (page load times, API response times).

Ensures smooth and consistent experience for users.

Root Cause Analysis (RCA)

Detects which service, code, or database query is causing performance issues.

Proactive Alerts and Notifications

Sends alerts when performance thresholds are crossed.

Helps teams react before users are affected.

Business Insights

Provides analytics on application usage, peak traffic, and trends.

Supports capacity planning and scaling decisions.
- **22.Explain stuck threads in WebLogic and reasons for them happening.**:

A stuck thread in WebLogic is a thread in the server’s thread pool that has been executing a request for longer than a configured timeout.

These threads are considered “stuck” because they may be blocking resources and can affect server performance.

WebLogic uses execute threads to process incoming requests. If a thread is stuck, it cannot pick up new requests until it completes or is killed.
-  **23. What is the command for creating a partition and checking the partition?**:

```
lsblk
# or
fdisk -l
```
- **24. How to make a particular partition as a mandatory partition that is required at the time of booting, and whenever booting the system, this particular partition will be present.**:

```
Identify partition → lsblk / blkid
Create mount point → mkdir -p /data
Backup fstab → cp /etc/fstab /etc/fstab.bak
Edit fstab → add UUID, mount point, filesystem type, options, dump, pass
Test mount → mount -a
Verify → df -h
```
- **25. How to check how many cores are present in my system.**:

| Command                            | What it Shows                              |
| ---------------------------------- | ------------------------------------------ |
| `lscpu`                            | Detailed CPU info, cores, threads, sockets |
| `grep -c ^processor /proc/cpuinfo` | Count of logical CPUs                      |
| `nproc`                            | Number of available processors             |
| `top` / `htop`                     | Real-time CPU usage per core               |

- **26. What are all infrastructure servers?**:

🔹 1️⃣ Web/Application Servers

Purpose: Host web applications, APIs, and services.

Examples:

Apache HTTP Server, Nginx, Tomcat, WebLogic, WebSphere, Node.js / Express servers

Role in Infrastructure: Serve application traffic to users or other systems.

🔹 2️⃣ Database Servers

Purpose: Store and manage structured/unstructured data.

Examples:

MySQL, MariaDB, PostgreSQL, Oracle DB, MongoDB, Cassandra, Redis, Memcached (caching)

🔹 3️⃣ File / Storage Servers

Purpose: Centralized file storage and sharing.

Examples:

NFS (Network File System), Samba / Windows File Server, SAN / NAS storage systems

Role in Infrastructure: Store files, backups, media, and logs.

🔹 4️⃣ Authentication / Directory Servers

Purpose: Manage user authentication and access control.

Examples:

Active Directory (AD)


🔹 5️⃣ DNS / DHCP Servers

DNS (Domain Name System): Resolve domain names to IP addresses.

DHCP (Dynamic Host Configuration Protocol): Assign IP addresses automatically.

Examples: BIND DNS server, Microsoft DNS, ISC DHCP

🔹 6️⃣ Proxy / Load Balancer Servers

Purpose:

Proxy: Manage and forward client requests

Load balancer: Distribute traffic across multiple servers for availability

Examples: Nginx, HAProxy, F5, AWS ELB

🔹 7️⃣ Monitoring & Logging Servers

Purpose: Monitor health, performance, and logs of infrastructure and apps.

Examples:

Prometheus + Grafana, Nagios, Zabbix, ELK Stack (Elasticsearch, Logstash, Kibana), Splunk

🔹 8️⃣ Backup / Disaster Recovery Servers

Purpose: Store backups, snapshots, and recovery systems.

Examples: Veeam, NetBackup, custom NAS/SAN servers

🔹 9️⃣ Security / Firewall / VPN Servers

Purpose: Protect network and infrastructure.

Examples:

Firewalls (Fortinet, Palo Alto)

VPN servers (OpenVPN, Cisco ASA)

Intrusion detection systems (Snort, Suricata)

🔹 10️⃣ CI/CD & Automation Servers

Purpose: Automate build, deploy, and testing pipelines.

Examples:

Jenkins, GitLab CI, TeamCity, Ansible Tower / AWX, Terraform / Pulumi automation

🔹 11️⃣ Container / Orchestration Servers

Purpose: Host containers and orchestrate microservices.

Examples:

Docker hosts, Kubernetes master and worker nodes

OpenShift clusters
- **27. What is used in AppDynamics?**:

AppDynamics uses agents installed on applications and servers to collect metrics, traces user transactions, and provides dashboards for monitoring and alerting, helping DevOps teams quickly identify and resolve performance issues.”

- **28. Why WebLogic is used and how it works.**:

High Availability & Clustering

Enterprise Java Support

Centralized Administration

Scalability & Performance

Security & Transaction Management

- **29. What is meant by clusters?**:

A cluster is a group of independent servers (nodes) working together as a single system to provide high availability, scalability, and load balancing.

- **30. What are the components of a WebLogic cluster?**:

A WebLogic cluster is a group of WebLogic Server instances (Managed Servers) working together to provide high availability, scalability, and load balancing.

- **31. Calculate 37×34**: 1110+148=1258

- **32. A monkey is trying to climb a 12-foot pole. The monkey takes 5 minutes to climb 2 feet of the pole. However, in the next 5 minutes, it slips down 1 foot. How much time will it take for the monkey to climb to the top of the pole?**: 105 mins

- **32. I have 9 coins with me, all coins have the same width, size, and texture, but one coin is a bit different, having excess weight. What are the least possible steps to identify the odd coin?**: 2 weighings

- **33. What is LVM?**:

LVM = Logical Volume Manager
| Component                | Description                                                     |
| ------------------------ | --------------------------------------------------------------- |
| **Physical Volume (PV)** | Actual physical disk or partition (e.g., /dev/sdb, /dev/sdc)    |
| **Volume Group (VG)**    | Pool of storage combining multiple PVs                          |
| **Logical Volume (LV)**  | Virtual partition created from VG, used like a normal partition |
| **Physical Extent (PE)** | Smallest chunk of space on a PV, allocated to LV                |
| **Logical Extent (LE)**  | Chunk of LV corresponding to PE in VG                           |

- **34 How to transfer files from one server to another server.**:

```
scp /path/to/local/file username@remote_host:/path/to/remote/directory
rsync -avz /home/user/data/ ubuntu@192.168.1.10:/home/ubuntu/data/
```

- **35. How to enter into single-user mode.**:

```
sudo init 1
```

- **36.After upgrading the package, the package is not working, what is the reason for that?**:

Mention dependency issues, config changes, permissions, conflicts, and bugs.

Emphasize troubleshooting steps: check binaries, dependencies, logs, and configs.

- **37. After upgrading the package, the package is not working, what is the reason for that?**:

```
sudo lvextend -L +10G /dev/vg_name/lv_name
```

- **38. What is Ansible?**:

Mention agentless architecture, idempotency, and playbooks written in YAML.

Example answer:

“Ansible is an open-source automation tool used for configuration management, application deployment, and orchestration. It is agentless, uses YAML playbooks to define desired states, and ensures idempotency, making automation across multiple servers simple and reliable.”

```yaml
---
- name: Install Nginx on web servers
  hosts: webservers
  become: yes

  tasks:
    - name: Install Nginx
      apt:
        name: nginx
        state: present

    - name: Start Nginx service
      service:
        name: nginx
        state: started
```

- **39. AWS**:

AWS is a cloud computing platform provided by Amazon.
Offers on-demand computing, storage, databases, networking, and other cloud services over the internet.
Enables organizations to deploy and scale applications without managing physical servers.

| Category                 | Key Services                             | Use Case                                              |
| ------------------------ | ---------------------------------------- | ----------------------------------------------------- |
| **Compute**              | EC2, Lambda, ECS, EKS                    | Run applications, serverless functions, containers    |
| **Storage**              | S3, EBS, EFS, Glacier                    | Object storage, block storage, file storage, archival |
| **Database**             | RDS, DynamoDB, Aurora, Redshift          | Managed SQL/NoSQL databases, data warehousing         |
| **Networking**           | VPC, Route 53, ELB, CloudFront           | Virtual networks, DNS, load balancing, CDN            |
| **Security**             | IAM, KMS, Shield, WAF                    | Access management, encryption, firewall protection    |
| **Monitoring & Logging** | CloudWatch, CloudTrail, X-Ray            | Metrics, logs, auditing, tracing                      |
| **DevOps / Automation**  | CloudFormation, CodeDeploy, CodePipeline | Infrastructure as code, CI/CD automation              |

- **40. What is Nagios, ServiceNow?**:

Nagios is used for monitoring servers, applications, and network health, generating alerts when issues occur. ServiceNow is used for IT service management, creating and tracking incident tickets, and managing change requests. Often, they are integrated so alerts from Nagios automatically create incidents in ServiceNow.”


- **41. What is coroutine?**:

diagram showing coroutine lifecycle: start → pause → resume → complete

- **42. Coroutine dispatcher and builder.**:

In Kotlin, a coroutine builder like launch or async starts a coroutine, defining its scope. A dispatcher like Dispatchers.IO or Dispatchers.Default determines which thread or thread pool the coroutine runs on, allowing efficient handling of I/O or CPU-bound tasks.

- **43. MVC, MVP, MVVM**:

| Pattern  | View updates via       | Logic handled by | Data binding | Common Use                     |
| -------- | ---------------------- | ---------------- | ------------ | ------------------------------ |
| **MVC**  | Controller             | Controller       | ❌            | Web apps (Spring MVC, Django)  |
| **MVP**  | Presenter              | Presenter        | ❌            | Older Android apps             |
| **MVVM** | ViewModel (observable) | ViewModel        | ✅            | Modern Android, React, SwiftUI |

- **44. ProGuard**:

ProGuard workflow: Source code → Compilation → Shrinking → Optimization → Obfuscation → Final APK

- **45. Kotlin playground website - take a string (person name) and give the counts of duplicates.**:

Kotlin snippet you can run on the Kotlin Playground
 that takes a person's name and counts duplicate characters.
 
- **46. What is DNS?**:

DNS = Domain Name System

It is like the “phonebook of the internet”.

Converts human-readable domain names (e.g., www.google.com) into IP addresses (e.g., 142.250.191.196) that computers use to communicate.


- **47. Patching process.**:

Patching is mean to update the all the dependies and libraries

- **48. How to change the user and group permission.**:

```
sudo chown sharath:devops file.txt
chmod 755 file.txt   # user=rwx, group=rx, others=rx
chmod 644 file.txt   # user=rw, group=r, others=r
chmod -R 700 /home/sharath/project  # Recursive private access

Read- write execute
User group other

```

- **49. What is snapshot?**:

A snapshot is a point-in-time copy of a system, disk, or VM, which captures its exact state and data. Snapshots allow quick restoration in case of failures, making them useful for patching, upgrades, or testing. They are space-efficient because they typically store only changes after the initial snapshot.”


- **50. Infra Domain understanding (If applicable).**:

| Skill                       | Importance                                            |
| --------------------------- | ----------------------------------------------------- |
| Linux Administration        | Server management, commands, logs, users, permissions |
| Networking                  | TCP/IP, ports, DNS, load balancing, firewalls         |
| Cloud                       | AWS EC2, S3, VPC, IAM, Azure/GCP equivalents          |
| Monitoring & Alerting       | Nagios, Prometheus, Grafana, ELK                      |
| Automation                  | Ansible, Terraform, Shell scripting                   |
| Virtualization / Containers | VMware, KVM, Docker, Kubernetes                       |
| Backup & Recovery           | Snapshots, EBS/Azure snapshots, restore procedures    |
| Security                    | IAM policies, SSH, patching, firewall rules           |

- **51. What is NetFlow?**:

NetFlow is a network protocol developed by Cisco to collect and monitor IP network traffic.

It provides visibility into network usage, helping administrators analyze traffic patterns, bandwidth usage, and potential network issues.

Essentially, NetFlow allows you to see who is communicating with whom, when, and how much data is being transferred.

- **52. If Apache (HTTP server) is not installed or not running, here’s a step-by-step approach you can explain in an interview or follow in production:**:

If Apache is not installed, I would first check the server to confirm installation. If missing, I would install Apache using the package manager (apt or yum), start the service, enable it to run on boot, and verify it is running. If installation fails, I can use Nginx as an alternative web server


- **53. Which monitoring tool are you using and what do you see in this monitoring tool?**:

“I typically use Nagios and Prometheus + Grafana for monitoring. In these tools, I monitor CPU, memory, disk, network usage, as well as application health like HTTP response time or service availability. I also configure alerts when metrics cross thresholds, and visualize trends on dashboards to proactively identify issues.”

- **54. What is the pre-check for upgradation?**:

“Before performing any upgrade, I first take backups and snapshots, check disk, memory, CPU, and service status, verify network connectivity, confirm current versions and dependencies, and ensure compatibility. I also schedule a maintenance window, document a rollback plan, and perform a dry run or test upgrade in staging to minimize risks.”

- **55. What is DNS & DHCP?**:

| Feature          | DNS                                 | DHCP                                        |
| ---------------- | ----------------------------------- | ------------------------------------------- |
| Function         | Resolves domain names to IPs        | Assigns IP addresses & network configs      |
| Protocol         | UDP/TCP port 53                     | UDP ports 67 (server), 68 (client)          |
| Manual/Automatic | Usually configured manually         | Automatic IP allocation                     |
| Example          | `www.google.com` → `142.250.190.78` | Laptop gets IP `192.168.1.50` automatically |

- **56. What is TCP & UDP?**:

TCP is a reliable, connection-oriented protocol that guarantees delivery and order of packets, commonly used for web, FTP, SSH, and email. UDP is a faster, connectionless protocol without delivery guarantees, used for DNS, streaming, online gaming, and VoIP. TCP ensures reliability, whereas UDP prioritizes speed.”

