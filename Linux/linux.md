Linux Basic
1.what is linux in short.
Linux® is an open source operating system (OS). An operating system is the software that directly manages a system's hardware and resources, like CPU, memory, and storage. The OS sits between applications and hardware and makes the connections between all of your software and the physical resources that do the work.

Linux is an open-source operating system based on Unix. It is widely used for its stability, security, and flexibility. Linux powers many servers, desktops, and embedded systems, and comes in various distributions like Ubuntu, Fedora, and CentOS. It's favored in DevOps for its compatibility with many tools and platforms.
Features:
Linux is renowned for its robust features that cater to the demands of cloud computing and DevOps:Linux is renowned for its robust features that cater to the demands of cloud computing and DevOps:
•	Open-source: Linux’s opens source character allows for the formulation of the community’s development, the co-operation and frequent betterments.
•	Modularity: Modular design of Linux posits users to rebuild the operating system troops o hert needs, avoiding unnecessary overhead and saving energy.
•	Security: Since linux itself carries in its armor the security attributes like access controls and sandboxing, your critical operations are quite safe with it.
•	Compatibility: Linux lives off the fact that it supports diverse hardware and software eliminating compatibility problems with the legacy environment.

2. The history of linux
Linux, created by Linus Torvalds in 1991, is an open-source operating system inspired by Unix. Initially a personal project, it was released under the GNU General Public License, allowing free use and modification. It quickly gained popularity, leading to the development of various distributions like Red Hat and Ubuntu. By the 2000s, Linux became a staple in server environments and later in cloud computing and DevOps. Today, it powers a wide range of devices from smartphones to supercomputers.


3.why linux?
•  Open Source: It's free to use, modify, and distribute, promoting innovation and collaboration.
•  Security: Its architecture and regular updates make it highly secure.
•  Stability: Known for its robustness and reliability, especially in server environments.
•  Flexibility: Highly customizable and adaptable to various uses, from desktops to embedded systems.
•  Community Support: A vast community of developers and users contributes to its continuous improvement and provides extensive support.


4. The linux Architecture
Components of Linux:
Like any operating system, Linux consists of software, computer programs, documentation, and hardware.
The main components of Linux operating system are: Application, Shell, Kernel, Hardware, Utilities
 
1. Kernel:
Kernel is the main core component if Linux, it controls the activity of other hardware components. It visualizes the common hardware resources and provide each process with necessary virtual resources. It makes the process to wait in the ready queue and execute in consequently to avoid any kind of conflict.
Types:
-Monolithic Kernel
-Micro kernel:
-Exokernel:
-Hybrid kernel

2. System Library:
System libraries are some predefined functions by using which any application programs or system utilities can access kernel’s features. These libraries are the foundation upon which any software can be built.

--GNU C library: This is the C library that provides the most fundamental system for the interface and execution of C programs. This provides may in-built functions for the execution.

--libpthread (POSIX Threads): This library plays important role for multithreading in Linux, it allows users for creating and managing multiple threads.

--libdl (Dynamic Linker): This library is responsible for the loading and linking file at the runtime.

--libm (Math Library): This library provides user with all kind of mathematical function and their execution.

3. Shell:
Shell can be determined as the interface to the kernel, which hides the internal execution of functions of kernel from the user. Users can just enter the commend and using the kernel’s function that specific task is performed accordingly.

Different types of shell:

1. Command Line shell:
Executes the command provided by user given in the form command. A special program called terminal in executed and the result is displayed in the terminal itself.
2. Graphical User Interface:
Executes the process provided by user in graphical way and output is displayed in the graphical window.
 
Linux shell

 Hardware Layer:
Hardware layer of Linux is the lowest level of operating system track. It is plays a vital role in managing all the hardware components. It includes device drivers, kernel functions, memory management, CPU control, and I/O operations. This layer generalizes hard complexity, by providing an interface for software by assuring proper functionality of all the components.

 System utility:
System utilities are the commend line tools that preforms various tasks provided by user to make system management and administration better. These utilities enables user to perform different tasks, such as file management, system monitoring, network configuration, user management etc.

5.Flavour of linux 
•  Ubuntu
•	Base: Debian
•	Target Users: Beginners, general users
•	Key Features: User-friendly, strong community support, regular updates

•  Fedora
•	Base: Red Hat
•	Target Users: Developers, cutting-edge users
•	Key Features: Latest software, upstream development, strong focus on innovation

•  CentOS
•	Base: Red Hat Enterprise Linux (RHEL)
•	Target Users: Servers, enterprise users
•	Key Features: Stability, long-term support, community-driven

•  Debian
•	Base: Independent
•	Target Users: Advanced users, servers
•	Key Features: Stability, extensive software repositories, strong community

•  Kali Linux
•	Base: Debian
•	Target Users: Security professionals, ethical hackers
•	Key Features: Pre-installed security tools, penetration testing, forensics


6. role of linux in devops
The Role of Linux in DevOps
Linux speaks out a large role in DevOps (Development and Operations) ideology which aims to mend the gaps of the software developers and IT administrators. Here are some key points about the role of Linux in DevOps:Here are some key points about the role of Linux in DevOps:

•	Containerization: The bottom-line for containerize solutions like Docker and Kubernetes which are the most used in DevOps for the application packaging, deployment, and management lies in the fact that there are based on Linux.

•	Automation and Configuration Management: Operating system Linux gives a divergent choice of apparatuses and utilities to address automating tasks and managing configurations, as Ansible, Puppet and Chef are indeed indispensable to approach DevOps.

•	Continuous Integration and Continuous Deployment (CI/CD): In so many cases, mainstream continuous integration and continuous deployment tools like Jenkins, Gitlab CI/CD and Travis CI are popular and over widely used in DevOps workflow pipelines.

•	Cloud-Native Development: Cloud native development relies on a Linux kernel as being the core operating system component, a fact that is fundamental to DevOps, as it allows engineers to build and deploy applications that are designed to run on such cloud environments.

•	Scripting and Automation: One the areas where linux excels is its command-line interface and scripting capabilities (e.g., Bash Python). These make automating of various tasks and processes like DevOps practices easy.

 7. The Role of Linux in Cloud Computing
Linux is the main contributor in the modern cloud via using Linux based infrastructures for creating many cloud platforms and services Here are some key points about the role of Linux in cloud computing:The following are important themes concerning the Linux in Cloud Computing: Browse through our curated collection of mind-provoking questions to expand your understanding of familiar topics and broaden your intellectual horizons.

•	Virtualization: Linux is a great choice to use as an operating system for VMs which are required in cloud environments for both creating and managing them.

•	Cloud Infrastructure: Main cloud carriers, in particular Amazon Web Services (AWS), Microsoft Azure, and Google Cloud Platform, have started using Linux as an OS on the bottom tier of their cloud infrastructure.

•	Container Technologies: Linux functioned as a base for the container technologies, such as Docker and Kubernetes, which now are widely adopted for deployment and administration of applications on cloud environments.

•	Scalability and Flexibility: The scalable and customizable qualities of Linux mean that it’s a good fit for cloud atmospheres where resources need to be reallocated and scaled accordingly to match demand at any given time.

•	Open-Source Ecosystem: The Linux open source architecture and the ability to customize the operating system and tools with many cloud service providers and developers roles, that Linux provides an environment for its integration with various varieties.

Examples:
•	ls -l--> list the files and directories in long list format with extra information

•	ls -a --> list all including hidden files and directory

•	ls *.sh --> list all the files having .sh extension.

•	ls -i  --> list the files and directories with index numbers inodes

•	ls -d */ --> list only directories.(we can also specify a pattern)


Directoy commands
•	pwd --> print work directory. Gives the present working directory.

•	cd path_to_directory --> change directory to the provided path

•	cd ~  or just cd  --> change directory to the home directory

•	cd - --> Go to the last working directory.

•	cd .. --> change directory to one step back.

•	cd ../.. --> Change directory to 2 levels back.

•	mkdir directoryName --> to make a directory in a specific location


Examples:
mkdir newFolder              # make a new folder 'newFolder'

mkdir .NewFolder              # make a hidden directory (also . before a file to make it hidden)

mkdir A B C D                  #make multiple directories at the same time

mkdir /home/user/Mydirectory   # make a new folder in a specific location

mkdir -p  A/B/C/D              # make a nested directory




SHELL SCRIPTING
What is Kernel?
The kernel is a computer program that is the core of a computer’s operating system, with complete control over everything in the system.

What is Shell?
A shell is a special user program that provides an interface for users to interact with operating system services. It accepts human-readable commands from users and converts them into instructions that the kernel can understand. The shell is a command language interpreter that executes commands read from input devices such as keyboards or from files. It starts when the user logs in or opens a terminal.

What is Linux Shell Scripting?
Linux shell scripting involves writing programs (scripts) that can be run by a Linux shell, such as bash (Bourne Again Shell). These scripts automate tasks, perform system administration tasks, and facilitate the interaction between users and the operating system.

Task:

•	Explain in your own words and with examples what Shell Scripting means for DevOps.
shell scripting is a way to automate tasks in Unix-like operating systems using a series of commands written in a file, known as a script. In DevOps, shell scripts are used for automating repetitive tasks, managing system configurations, deploying applications, and more.

Example:

•	Automating backups

•	Deploying updates

•	Monitoring system performance

What is #!/bin/bash? Can we write #!/bin/sh as well?
The #!/bin/bash at the beginning of a shell script is called a shebang. It specifies the path to the interpreter that should execute the script.

1.#!/bin/bash tells the system to use the Bash shell to run the script.

2.#!/bin/sh tells the system to use the Bourne shell.
Both can be used, but bash (Bourne Again Shell) has more features compared to the original sh.


•	Write a Shell Script that prints I will complete #90DaysOfDevOps challenge.
#!/bin/bash
echo "I will complete #90DaysOfDevOps challenge"

•	Write a Shell Script that takes user input, input from arguments, and prints the variables.
#!/bin/bash
# Take user input
echo "Enter your name:"
read userName
# Take input from arguments
arg1=$1
arg2=$2
# Print the variables
echo "Hello, $userName!"
echo "First argument: $arg1"
echo "Second argument: $arg2"

•	Provide an example of an If-Else statement in Shell Scripting by comparing two numbers.
#!/bin/bash
 	num1=10
num2=20
if [ $num1 -gt $num2 ]; then
    echo "$num1 is greater than $num2"
else
    echo "$num1 is less than or equal to $num2"
fi

short notes on backup in shell scripting.

Backup in shell scripting involves creating copies of files or directories to prevent data loss. Automated backup scripts are crucial in maintaining data integrity and availability in case of system failures, data corruption, or accidental deletion.

Key Concepts:

1.	Backup Types:
o	Full Backup: Complete copy of all specified data.
o	Incremental Backup: Copies only data that has changed since the last backup.
o	Differential Backup: Copies data that has changed since the last full backup.

2.	Backup Location:
o	Local Backup: Stored on the same system or network.
o	Remote Backup: Stored on a different system, often using SSH or FTP.

3.	Scheduling Backups:
o	Use cron jobs to schedule regular backups.
o	Example: 0 2 * * * /path/to/backup-script.sh (runs daily at 2 AM)

Key Commands:

•	tar: Used to create archive files.

•	gzip: Compresses files.

•	scp or rsync: Transfers files to remote locations.

•	cron: Schedules scripts to run at specified times.

Best Practices:

1.	Automate Regular Backups: Use cron jobs to automate backups at regular intervals.
2.	Verify Backups: Periodically test backup files to ensure they can be restored.
3.	Secure Storage: Store backups in secure locations and consider encryption for sensitive data.
4.	Log Backup Activity: Maintain logs of backup operations for monitoring and troubleshooting.

Cron and Crontab for Automating Backup. 

Cron is a time-based job scheduler in Unix-like operating systems. It allows users to schedule scripts or commands to run automatically at specified intervals.
Crontab is a file that contains a list of cron jobs, and it also refers to the command used to edit this file.

Key Concepts:
1.	Cron Daemon (cron): Continuously runs in the background and executes scheduled tasks.
2.	Crontab File: A configuration file that specifies the commands to be executed and their scheduling.



Understanding File Permissions:

•	Basic Permissions

o	Permissions in Linux are represented by a three-digit number, where each digit represents a different set of users: owner, group, and others.

o	Highest Permission: 7 (4+2+1)

o	Maximum Permission: 777, but effectively 666 for files due to security reasons, meaning no user gets execute permission.

o	Effective Permission for Directories: 755

o	Lowest Permission: 000 (not recommended)

o	Minimum Effective Permission for Files: 644 (default umask value of 022)

o	Default Directory Permission: Includes execute permission for navigation


•	Categories of Users

o	Each of the three permissions are assigned to three defined categories of users:

o	Owner: The owner of the file or application.

	Command: chown is used to change the ownership of a file or directory.

o	Group: The group that owns the file or application.

	Command: chgrp is used to change the group permission of a file or directory.

o	Others: All users with access to the system.

	Command: chmod is used to change the permissions for other users.


•	Special Permissions

o	SUID (Set User ID): If SUID is set on an executable file and a normal user executes it, the process will have the same rights as the owner of the file being executed instead of the normal user (e.g., passwd command).

o	SGID (Set Group ID): If SGID is set on any directory, all subdirectories and files created inside will inherit the group ownership of the main directory, regardless of who creates them.

o	Sticky Bit: Used on folders to avoid deletion of a folder and its contents by other users though they have write permissions. Only the owner and root user can delete other users' data in the folder where the sticky bit is set.

What is a Package Manager in Linux?

In simpler words, a package manager is a tool that allows users to install, remove, upgrade, configure, and manage software packages on an operating system. The package manager can be a graphical application like a software center or a command line tool like apt-get or pacman.
You’ll often find me using the term ‘package’ in tutorials and articles. To understand a package manager, you must understand what a package is.

What is a Package?

A package is usually referred to as an application but it could be a GUI application, command line tool, or a software library (required by other software programs). A package is essentially an archive file containing the binary executable, configuration file, and sometimes information about the dependencies.

Different Kinds of Package Managers

Package managers differ based on the packaging system but the same packaging system may have more than one package manager.
For example, RPM has Yum and DNF package managers. For DEB, you have apt-get, aptitude command line-based package managers.



list of imp and daily use command in linux and shell scripting

File and Directory Management:

1.	ls: List directory contents
o	ls
o	ls -l (long listing format)
o	ls -a (list all files including hidden files)

2.	cd: Change directory
o	cd /path/to/directory
o	cd ~ (go to home directory)
o	cd .. (go up one directory level)

3.	pwd: Print working directory
o	pwd

4.	mkdir: Make directory
o	mkdir new_directory
o	mkdir -p parent_directory/child_directory (create nested directories)

5.	rm: Remove files or directories
o	rm file.txt
o	rm -r directory (remove directory and its contents)
o	rm -f file.txt (force remove a file)

6.	cp: Copy files or directories
o	cp source_file destination_file
o	cp -r source_directory destination_directory

7.	mv: Move or rename files or directories
o	mv old_name new_name (rename)
o	mv file.txt /new/path (move file)

8.	touch: Create an empty file or update the timestamp of an existing file
o	touch newfile.txt

File Viewing and Editing:

1.	cat: Concatenate and display file content
o	cat file.txt

2.	less: View file content one page at a time
o	less file.txt

3.	head: Display the first part of a file
o	head file.txt
o	head -n 10 file.txt (first 10 lines)

4.	tail: Display the last part of a file
o	tail file.txt
o	tail -n 10 file.txt (last 10 lines)
o	tail -f file.txt (follow file, useful for logs)

5.	nano / vim / gedit: Text editors
o	nano file.txt
o	vim file.txt
o	gedit file.txt (for graphical environment)

System Monitoring and Management:

1.	top: Display system processes and resource usage
o	top

2.	htop: Interactive process viewer (requires installation)
o	htop

3.	ps: Report a snapshot of current processes
o	ps aux

4.	kill: Terminate a process
o	kill PID
o	kill -9 PID (force kill)

5.	df: Report file system disk space usage
o	df -h

6.	du: Estimate file space usage
o	du -h
o	du -sh directory/

7.	free: Display memory usage
o	free -h

8.	uptime: Tell how long the system has been running
o	uptime

9.	uname: Print system information
o	uname -a

Networking:

1.	ping: Send ICMP ECHO_REQUEST to network hosts
o	ping example.com

2.	ifconfig / ip: Configure network interfaces
o	ifconfig
o	ip addr show

3.	netstat: Network statistics
o	netstat -tuln

4.	curl: Transfer data from or to a server
o	curl http://example.com

5.	wget: Download files from the web
o	wget http://example.com/file.tar.gz

File Permissions and Ownership:

1.	chmod: Change file modes or Access Control Lists
o	chmod 755 file.sh
o	chmod u+x file.sh (add execute permission for the user)

2.	chown: Change file owner and group
o	chown user:group file.txt

Searching and Filtering:

1.	grep: Print lines matching a pattern
o	grep "pattern" file.txt
o	grep -r "pattern" directory/

2.	find: Search for files in a directory hierarchy
o	find /path -name "filename"
o	find /path -type d -name "directoryname"

3.	awk: Pattern scanning and processing language
o	awk '{print $1}' file.txt (print first column)

4.	sed: Stream editor for filtering and transforming text
o	sed 's/old/new/g' file.txt (replace all occurrences of 'old' with 'new')

System Ctl:

systemctl is a command-line utility used to manage the systemd system and service manager. It allows administrators to control the system's services, check their status, and manage system states.

Checking a Service Status:

systemctl status sshd


Enabling a Service at Boot:-
systemctl enable nginx

Starting a Service:-
systemctl start docker

Stopping a Service:-
systemctl stop mysql


AWK

awk is a powerful text-processing language used for pattern scanning and processing. It is especially useful for extracting and manipulating data from text files or streams.

Eg.,
Print multiple columns: awk '{print $1, $3}' file.txt

Print the sum of the first and second columns: awk '{print $1 + $2}' file.txt

NR: Number of the current record (line): awk '{print NR, $0}' file.txt

Using if-else: awk '{if ($1 > 10) print $1 " is greater than 10"; else print $1 " is less than or equal to 10"}' file.txt

Count the number of lines in a file:

awk 'END {print NR}' file.txt


grep, find, and sed Commands in Linux

grep is used for searching plain-text data sets for lines that match a regular expression.

1.	Basic Usage:-
o	grep "pattern" file.txt: Search for "pattern" in file.txt

1.	Case Insensitive Search:-
o	grep -i "pattern" file.txt: Case insensitive search

2.	Recursive Search:-
o	grep -r "pattern" /path/to/directory: Search recursively in a directory

3.	Show Line Numbers:-
o	grep -n "pattern" file.txt: Show line numbers with matched lines

4.	Search Whole Words:-
o	grep -w "word" file.txt: Search for whole words only

5.	Invert Match:-
o	grep -v "p-attern" file.txt: Show lines that do not match the pattern


find Command

find is used for searching files and directories in a directory hierarchy.

1.	Basic Usage:-
o	find /path -name "filename": Search for files by name

2.	Search by Type:-
o	find /path -type d -name "dirname": Search for directories
o	find /path -type f -name "filename": Search for regular files

3.	Search by Size:-
o	find /path -size +100M: Search for files larger than 100MB

4.	Search by Modification Time:-
o	find /path -mtime -7: Search for files modified in the last 7 days

5.	Execute Command on Found Files:-
o	find /path -name "filename" -exec rm {} \;: Delete files found


sed Command

sed (Stream Editor) is used to perform basic text transformations on an input stream (a file or input from a pipeline).

1.	Basic Replacement:-
o	sed 's/old/new/' file.txt: Replace first occurrence of "old" with "new" in each line

2.	Global Replacement:-
o	sed 's/old/new/g' file.txt: Replace all occurrences of "old" with "new" in each line

3.	Edit File In-place:-
o	sed -i 's/old/new/g' file.txt: Edit the file directly

4.	Delete Lines Matching a Pattern:-
o	sed '/pattern/d' file.txt: Delete lines that match the pattern

5.	Print Specific Lines:-
o	sed -n '3p' file.txt: Print only the third line
o	sed -n '2,4p' file.txt: Print lines from 2 to 4

6.	Insert Text Before a Line:-
o	sed '2i\New line of text' file.txt: Insert text before the second line

