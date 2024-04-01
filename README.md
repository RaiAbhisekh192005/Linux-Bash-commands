<h1 align="center">Linux Commands</h1>
<h3 align="center">Operating Linux becomes easy if you know the right commands</h3>

<p align="center">
<img style="padding:10px;" src="https://img.shields.io/badge/Open%20Source-💕%20-9cf?style=for-the-badge"><br>
<img style="padding:10px;" src="https://img.shields.io/github/contributors/RaiAbhisekh192005/Linux-Bash-commands?style=flat-square">
<img style="padding:10px;" src="https://img.shields.io/github/forks/RaiAbhisekh192005/Linux-Bash-commands?label=Forks&style=flat-square">
<img style="padding:10px;" src="https://img.shields.io/github/stars/RaiAbhisekh192005/Linux-Bash-commands?style=flat-square">
<img style="padding:10px;" src="https://img.shields.io/github/license/RaiAbhisekh192005/Linux-Bash-commands?style=flat-square">
<img style="padding:10px;" src="http://img.shields.io/github/issues/RaiAbhisekh192005/Linux-Bash-commands?style=flat-square">

#### What is this repository for?

This is list of many useful basic linux command lines.

#### Who can contribute for this repository?

Anyone. Absolutely anyone can contribute to this repository. Please check the rules below before you make pull requests.

#### CONTRIBUTION

##### How to contribute?

- Add an issue to this repository stating the use of that command line.
- Fork this repository and give a star.
- Try to provide examples for that command line.
- Once go through the raw file of `Basic_commands.md` to get the gist of formatting required.
- Create a Pull request
- Feel free to improve the README.md

#### Rules
##### Please follow format used in `Basic_commands.md`
- Please do not spam pull request for the sake of Hacktoberfest.
- No duplicate entries. Please check if the command is existing before you submit.
- Star this repository to show appreciation towards public efforts.

## Table of Contents

1. [Navigating the File System](#navigating-the-file-system)
2. [File Operations](#file-operations)
3. [Text Processing](#text-processing)
4. [User Management](#user-management)
5. [Process Management](#process-management)
6. [Networking](#networking)
7. [System Information](#system-information)


less: View file content one page at a time
 ```
 less long_file.txt
 ```

head: Output the first part of files
 ```
 head -n 5 file.txt
 ```

tail: Output the last part of files
 ```
 tail -n 10 file.txt
 ```

grep: Search for patterns in files
 ```
 grep "pattern" file.txt
 ```

find: Search for files and directories
 ```
 find . -name "*.txt"
 ```

chmod: Change file permissions
 ```
 chmod 755 file.sh
 ```

chown: Change file owner and group
 ```
 chown user:group file.txt
 ```

ps: Show process status
 ```
 ps aux
 ```

kill: Terminate processes
 ```
 kill PID
 ```

sudo: Execute a command as the superuser
 ```
 sudo apt-get install package_name
 ```

su: Switch user
 ```
 su username
 ```

df: Report file system disk space usage
 ```
 df -h
 ```

du: Estimate file space usage
 ```
 du -sh directory_name
 ```

tar: Manipulate archive files
 ```
 tar -cvf archive.tar file1 file2
 ```

gzip: Compress or decompress files
 ```
 gzip file.txt
 ```

ping: Test a network connection
 ```
 ping google.com
 ```

ifconfig: Configure network interfaces
 ```
 ifconfig eth0
 ```

netstat: Print network connections, routing tables, interface statistics, etc.
 ```
 netstat -an
 ```

hostname: Show or set the system's hostname
 ```
 hostname
 ```

whoami: Print the current user name
 ```
 whoami
 ```

uname: Print system information
 ```
 uname -a
 ```

date: Display or set the system date and time
 ```
 date
 ```

cal: Display a calendar
 ```
 cal
 ```

uptime: Show how long the system has been running
 ```
 uptime
 ```

free: Display amount of free and used memory in the system
 ```
 free -m
 ```

top: Display Linux processes
 ```
 top
 ```

htop: Interactive process viewer
 ```
 htop
 ```

who: Display who is logged on
 ```
 who
 ```

finger: User information lookup program
 ```
 finger username
 ```

w: Show who is logged on and what they are doing
 ```
 w
 ```

history: Display the command history
 ```
 history
 ```

man: Display the manual for a command
 ```
 man ls
 ```

apropos: Search the manual page names and descriptions
 ```
 apropos search_term
 ```

which: Locate a command
 ```
 which ls
 ```

locate: Find files by name
 ```
 locate filename
 ```

updatedb: Update the slocate database
 ```
 updatedb
 ```

clear: Clear the terminal screen
 ```
 clear
 ```

reboot: Reboot the system
 ```
 reboot
 ```

shutdown: Shutdown or restart the system
 ```
 shutdown -h now
 ```

exit: Exit the shell or terminal
 ```
 exit
 ```
chmod: Change file permissions
 ```
 chmod +x script.sh
 ```

chown: Change file owner and group
 ```
 chown user:group file.txt
 ```

chgrp: Change group ownership
 ```
 chgrp group_name file.txt
 ```

ln: Create links between files
 ```
 ln -s /path/to/file /path/to/symlink
 ```

mount: Mount a file system
 ```
 mount /dev/sdb1 /mnt/usb
 ```

umount: Unmount a file system
 ```
 umount /mnt/usb
 ```

df: Display disk space usage
 ```
 df -h
 ```

du: Display directory space usage
 ```
 du -sh directory
 ```

fdisk: Partition table manipulator for Linux
 ```
 fdisk /dev/sdb
 ```

mkfs: Build a Linux filesystem
 ```
 mkfs.ext4 /dev/sdb1
 ```

fsck: Check and repair a Linux filesystem
 ```
 fsck /dev/sdb1
 ```

grep: Search for patterns in files
 ```
 grep "pattern" file.txt
 ```

sed: Stream editor for filtering and transforming text
 ```
 sed 's/old/new/' file.txt
 ```

awk: Pattern scanning and processing language
 ```
 awk '{print $1}' file.txt
 ```

sort: Sort lines of text files
 ```
 sort file.txt
 ```

uniq: Report or omit repeated lines
 ```
 uniq file.txt
 ```

wc: Print newline, word, and byte counts for each file
 ```
 wc file.txt
 ```

diff: Compare files line by line
 ```
 diff file1.txt file2.txt
 ```

tar: Manipulate archive files
 ```
 tar -cvf archive.tar file1 file2
 ```

gzip: Compress or decompress files
 ```
 gzip file.txt
 ```

bzip2: A block-sorting file compressor
 ```
 bzip2 file.txt
 ```
