# Linux Administration Tool.sh
This BASH script is designed to assist you in administrating and monitoring a Linux distribution. Some features include adding and removing users, changing passwords, checking for failed login attempts and showing active network connections to your system. 

Tested on a Red Hat distribution (CentOS 7). Debian users should replace "yum" with "apt-get".

# **Installation :-**
1.	Install Git and Network tools (required for option 6):
> sudo yum -y install git net-tools
2.	Clone the repository locally and navigate there:
> git clone https://github.com/Kevin-Mould/Linux-Administration-Script.git

> cd linux-administration-script
3.	Make the script executable:
> chmod +x “Linux Administration Tool.sh”
4.	Change the Windows line endings (CRLF) to Linux line Endings (LF):
>  sed -i -e 's/\r$//' "Linux Administration Tool.sh"
5.	Run the shell script:
> ./”Linux Administration Tool.sh”


Main menu of the script.

![](Pictures/mainMenu.PNG)

Adding a user to the system.

![](Pictures/addUser.PNG)

Delete a user from the system.

![](Pictures/delUser.PNG)

Show disk usage statistics.

![](Pictures/diskUsage.PNG)

Display network statistics.

![](Pictures/networkStats.PNG)
