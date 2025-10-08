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
Security tools like: Sonar Qube and Trivy

-  **2. Everyday basic commands**

 ```sh
pwd   	   Show current working directory	      	   pwd
ls	       List files and folders	    	           ls -ltr
cd	       Change directory		      	      	      cd /etc
mkdir   	 Create directory	      	      	      	mkdir logs
rmdir	     Remove empty directory		      	      rmdir old_logs
cp	       Copy files/folders		      	      cp file1.txt /tmp/
mv	       Move or rename file	      	      	mv app.log /var/logs/
rm	       Remove file or directory	      	      	rm -rf temp/
touch	     Create empty file		      	      	      touch test.txt
📂 2. Viewing and Reading Files
Command	Description	Example
cat	View file content	cat /etc/hosts
less	Scroll through file	less access.log
head	Show first few lines	head -n 10 syslog
tail	Show last few lines	tail -n 20 syslog
tail -f	Watch logs live	tail -f /var/log/syslog
wc -l	Count lines	wc -l access.log
grep	Search for keywords	grep "error" app.log
⚙️ 3. File Management & Compression
Command	Description	Example
find	Search files by name	find /var -name "*.log"
du -sh	Check folder size	du -sh /home/user/
df -h	Disk usage summary	df -h
tar -czf	Compress folder	tar -czf backup.tar.gz /data
tar -xzf	Extract compressed file	tar -xzf backup.tar.gz
zip	Create zip archive	zip -r logs.zip /var/log/
unzip	Extract zip	unzip logs.zip
🧩 4. Permissions & Ownership
Command	Description	Example
chmod	Change file permissions	chmod 755 script.sh
chown	Change file owner	chown user:group file.txt
ls -l	Show permissions of files	ls -l /etc/
sudo	Run command as root	sudo systemctl restart nginx
🧑‍💼 5. User Management
Command	Description	Example
whoami	Show current user	whoami
id	Show user ID and groups	id
adduser	Create new user	sudo adduser devops
passwd	Change password	passwd devops
su - user	Switch user	su - root
exit	Exit session	exit
🌐 6. Networking
Command	Description	Example
ping	Test network connectivity	ping google.com
ifconfig / ip a	View IP details	ip a
hostname -I	Show IP address	hostname -I
curl	Check endpoint/API	curl -I https://example.com
wget	Download file	wget https://example.com/file.zip
ss -tuln	Check listening ports	ss -tuln
scp	Copy file over SSH	scp file.txt user@server:/tmp/
ssh	Connect to remote host	ssh user@server
🧮 7. Process & System Monitoring
Command	Description	Example
ps aux	List all processes	`ps aux
top	Monitor live processes	top
htop	Better process viewer (install separately)	htop
free -h	Memory usage	free -h
uptime	Show system uptime	uptime
kill -9 PID	Kill process by PID	kill -9 1234
df -h	Disk space	df -h
vmstat 1	System performance summary	vmstat 1
🧰 8. Package Management
🟩 Ubuntu / Debian
Command	Description	Example
apt update	Refresh package list	sudo apt update
apt install	Install software	sudo apt install nginx
apt remove	Remove software	sudo apt remove nginx
dpkg -l	List installed packages	`dpkg -l
🟥 RHEL / CentOS
Command	Description	Example
yum install	Install package	sudo yum install httpd
yum remove	Uninstall package	sudo yum remove httpd
yum update	Update system	sudo yum update
rpm -qa	List installed RPMs	`rpm -qa
🔐 9. System and Service Management
Command	Description	Example
systemctl status	Check service status	systemctl status nginx
systemctl start/stop/restart	Manage services	systemctl restart docker
service	Legacy command to manage services	service ssh restart
journalctl -u	View logs for service	journalctl -u nginx -f
reboot	Reboot system	sudo reboot
shutdown now	Shutdown system	sudo shutdown now
🧩 10. Useful Everyday Utilities
Command	Description	Example
date	Display system date/time	date
cal	Display calendar	cal
clear	Clear screen	clear
history	Show command history	history
alias	Create short command	alias ll='ls -la'
echo	Print text	echo "Hello World"
man <command>	Manual for a command	man grep
🧠 Bonus: Common Daily Use Combos
Task	Command
Check last 100 lines of log	tail -n 100 /var/log/syslog
Monitor a log in real time	tail -f /var/log/nginx/access.log
Find large files	find / -type f -size +100M
Check system load	uptime
Check IP	curl ifconfig.me
Search running process	`ps aux
Check port usage	`ss -tuln
List cron jobs	crontab -l
Backup directory	tar -czf backup.tar.gz /etc
View disk usage sorted	`du -h --max-depth=1 /
```

-  **1. Self Introduction**:
-  **1. Self Introduction**:
We are following the agile and crum Metodology. We are following the sprint mechanisum
