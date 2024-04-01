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

21. su: Switch user
 ```
 su username
 ```

22. df: Report file system disk space usage
 ```
 df -h
 ```

23. du: Estimate file space usage
 ```
 du -sh directory_name
 ```

24. tar: Manipulate archive files
 ```
 tar -cvf archive.tar file1 file2
 ```

25. gzip: Compress or decompress files
 ```
 gzip file.txt
 ```
