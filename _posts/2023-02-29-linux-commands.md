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



21. netstat
22. iptables
23. wget
24. curl
25. ssh
26. scp
	<!-- #### Archiving and Compression: -->
27. tar
28. gzip
29. unzip
	<!-- #### Search and Text Manipulation: -->
30. find
31. grep
32. sed
33. awk
	<!-- #### Disk and Memory Usage: -->
34. du
35. df
36. free
	<!-- #### System Information and Utilities: -->
37. uname
38. date
39. history
40. clear
41. exit
	<!-- #### Tar Archives: -->
42. tar -xvf
43. tar -cvf
44. tar -czvf
45. tar -xvzf
	<!-- #### List Files: -->
46. ls -l
47. ls -a
	<!-- #### User Information: -->
48. whoami
	<!-- #### Human-Readable Disk Space Usage: -->
49. df -h
	<!-- #### Show All Processes:  -->
50. ps aux



