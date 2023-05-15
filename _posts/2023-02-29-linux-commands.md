---
layout: post
title: The 50 most popular Linux and Terminal commands
excerpt: "Linux is a powerful and versatile operating system that has gained immense popularity in recent years, especially among developers and system administrators. The terminal, also known as the command line interface (CLI), is a powerful tool that allows users to interact with the operating system using text commands. In this article, we'll discuss the 50 most popular Linux and Terminal commands that you should know to navigate and manage your Linux system efficiently. These commands are organized into categories, and we'll provide examples for each command to help you understand how they work. Whether you're a beginner or an experienced Linux user, mastering these commands will help you become more productive and efficient on the command line."
categories: [Linux]
comments: true
url : https://anand.dev/articles/2023-03/linux-commands
identifier: 1234
image:
  feature: https://miro.medium.com/max/8512/0*-hMqapazeDO-IOck
  credit: 
  creditlink: 
---
<!-- **Navigation and File Management:** -->

01. **cd** - Change directory
	
	`cd /home/user/Documents` - changes the current directory to /home/user/Documents.

02. **ls** - List directory contents
	
	`ls` - lists the contents of the current directory.
	
	`ls /home/user/Documents` - lists the contents of the directory /home/user/Documents.

03. **pwd** - Print working directory
	
	`pwd` - prints the current working directory.

04. **mkdir** - Make directory
	
	`mkdir new_directory` - creates a new directory named new_directory.

05. **rmdir** - Remove directory
	
	`rmdir old_directory` - removes the directory named old_directory if it's empty.

06. **touch** - Create a file
	
	`touch new_file.txt` - creates a new file named new_file.txt.

07. **cat** - Concatenate and print files
	
	`cat file.txt` - prints the contents of file.txt to the terminal.

08. **cp** - Copy files or directories

	`cp file.txt /home/user/Documents` - copies file.txt to the directory /home/user/Documents.

09. **mv** - Move or rename files or directories
	
	`mv file.txt new_file.txt` - renames file.txt to new_file.txt.

	`mv file.txt /home/user/Documents` - moves file.txt to the directory /home/user/Documents.

10. **rm** - Remove files or directories

	`rm file.txt` - removes file.txt from the current directory.
	
	`rm -r directory` - removes directory and all its contents recursively.

	<!-- **Permissions and Ownership:** -->
11. **chmod** - Change file permissions
		
	`chmod 755 file.txt` - sets the file permission for file.txt to read, write, and execute for the owner, and read and execute for others.
12. **chown** - Change file ownership
	
	`sudo chown user:group file.txt` - changes the ownership of file.txt to user and the group to group.
	<!-- #### Process Management: -->
13. **ps** - Show current processes
	
	`ps` - displays a list of the current processes running in the terminal.
14. **top** - Show system processes and resource usage
	
	`top` - displays a dynamic real-time view of the processes currently running in the system.
15. **kill** - Send a signal to terminate a process

	`kill process_id` - terminates the process with the specified process_id.
	<!-- #### User and Authentication: -->
16. **sudo** - Run a command with elevated privileges
	
	`sudo apt-get update` - runs the command `apt-get update` with elevated privileges.
17. **su** - Switch to another user account

	`su - user` - switches to the user account named user.
	<!-- #### Network: -->
18. **ping** - Check network connectivity

	`ping google.com` - sends a ping request to google.com to check network connectivity.
19. **traceroute** - Trace the route taken by packets through an IP network

	`traceroute google.com` - displays the route taken by packets through the IP network to reach `google.com`.
20. **ifconfig** - Show network interface configuration

	`ifconfig` - displays the configuration details of all the network interfaces in the system.

Sure! Here are examples of the next 10 Linux and Terminal commands:

21. netstat - Show network status
   - `netstat` - displays the current network connections and their status.

22. iptables - Configure firewall rules
   - `iptables -L` - lists all the current firewall rules.

23. wget - Download files from the web
   - `wget http://example.com/file.zip` - downloads the file `file.zip` from the web.

24. curl - Transfer data from or to a server
   - `curl http://example.com/api` - sends an HTTP GET request to `example.com/api` and displays the server's response.

25. ssh - Connect to a remote server securely
   - `ssh user@remote_server` - connects to `remote_server` as `user`.

26. scp - Securely copy files between hosts
   - `scp file.txt user@remote_server:/home/user` - copies `file.txt` to `remote_server`'s `/home/user` directory.
	
	<!-- #### Archiving and Compression: -->

27. tar - Archive files and directories
   - `tar -cvf archive.tar file.txt` - creates a new tar archive `archive.tar` containing `file.txt`.

28. gzip - Compress files
   - `gzip file.txt` - compresses `file.txt` and renames it to `file.txt.gz`.

29. unzip - Extract files from a ZIP archive
   - `unzip archive.zip` - extracts all the files from the ZIP archive `archive.zip`.

<!-- #### Search and Text Manipulation: -->

30. find - Search for files and directories
   - `find /home/user -name file.txt` - searches for the file `file.txt` in the directory `/home/user` and its subdirectories.
Sure, here are examples of the next 10 Linux and Terminal commands:

31. grep - Search for a pattern in a file
   - `grep 'error' log.txt` - searches for the word 'error' in the file `log.txt`.

32. sed - Stream editor for filtering and transforming text
   - `sed 's/old_text/new_text/g' file.txt` - replaces all occurrences of `old_text` with `new_text` in `file.txt`.

33. awk - Text processing and data extraction
   - `awk '{print $1}' file.txt` - prints the first column of `file.txt`.

34. echo - Print a message to the terminal
   - `echo 'Hello World!'` - prints 'Hello World!' to the terminal.

35. date - Display or set the system date and time
   - `date` - displays the current system date and time.

36. cal - Display a calendar
   - `cal` - displays a calendar of the current month.

37. history - Display the command history
   - `history` - displays the list of commands executed in the terminal.

38. du - Estimate file space usage
   - `du -h file.txt` - displays the disk usage of `file.txt` in human-readable format.
<!-- #### Disk and Memory Usage: -->

39. df - Show disk usage and free space
   - `df -h` - displays the disk usage and free space of all the mounted filesystems in human-readable format.

40. free - Display system memory usage
   - `free -h` - displays the system memory usage in human-readable format.
   Sure, here are examples of the next 10 Linux and Terminal commands:

<!-- #### System Information and Utilities: -->

41. uname - Display system information
   - `uname -a` - displays all the system information, including the operating system, kernel version, and hardware architecture.

42. whoami - Display the current user
   - `whoami` - displays the name of the current user.

43. id - Display user and group information
   - `id` - displays the user and group information of the current user.

44. passwd - Change user password
   - `passwd` - changes the password of the current user.

45. useradd - Create a new user account
   - `sudo useradd newuser` - creates a new user account named `newuser`.

46. usermod - Modify user account
   - `sudo usermod -aG groupname username` - adds the user `username` to the group `groupname`.

47. userdel - Delete a user account
   - `sudo userdel username` - deletes the user account `username`.

48. groupadd - Create a new group
   - `sudo groupadd newgroup` - creates a new group named `newgroup`.

49. groupmod - Modify a group
   - `sudo groupmod -n newname oldname` - renames the group `oldname` to `newname`.

50. groupdel - Delete a group
   - `sudo groupdel groupname` - deletes the group named `groupname`.




