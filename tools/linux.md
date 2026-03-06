# Linux Commands Cheatsheet

> Linux is an open-source operating system. Run, configure, and administer Linux systems from the command line.

## Quick Reference

> **Preview** — This is a curated selection of key commands. Explore the full command list with examples, practice exercises, and more on [Command Playground](https://technoscripts.com/command-playground/?utm_source=github&utm_medium=repository&utm_campaign=explore-all).

| Command | Description |
|---------|-------------|
| `ls` | List directory contents |
| `cd` | Change the current directory |
| `pwd` | Print current working directory path |
| `cp` | Copy files and directories |
| `mv` | Move or rename files and directories |
| `rm` | Remove files or directories |
| `mkdir` | Create new directories |
| `rmdir` | Remove empty directories |
| `touch` | Create empty files or update timestamps |
| `cat` | Concatenate and display file contents |
| `ln` | Create hard and symbolic links |
| `chmod` | Change file access permissions |
| `chown` | Change file owner and group |
| `nano` | Simple terminal text editor |
| `grep` | Search text using patterns |
| `sed` | Stream editor for text transformation |
| `awk` | Pattern scanning and text processing |
| `sort` | Sort lines of text files |
| `uniq` | Report or filter repeated lines |
| `cut` | Remove sections from each line |
| `head` | Output the first part of files |
| `tail` | Output the last part of files |
| `wc` | Count lines, words, and bytes |
| `tr` | Translate or delete characters |
| `diff` | Compare files line by line |
| `less` | View file contents page by page |
| `more` | View file contents one screen at a time |
| `tac` | Concatenate and print files in reverse |
| `nl` | Number lines of files |
| `printf` | Format and print data |
| `paste` | Merge lines of files side by side |
| `uname` | Print system information |
| `hostname` | Show or set the system hostname |
| `uptime` | Show how long the system has been running |
| `df` | Report file system disk space usage |
| `du` | Estimate file and directory space usage |
| `free` | Display free and used memory |
| `date` | Display or set the system date/time |
| `cal` | Display a calendar |
| `whoami` | Print current username |
| `id` | Print user and group IDs |
| `env` | Display environment variables |
| `printenv` | Print specific environment variables |
| `ps` | Report current running processes |
| `top` | Display real-time process activity |
| `htop` | Interactive process viewer |
| `kill` | Send a signal to a process |
| `killall` | Kill processes by name |
| `pkill` | Signal processes by name pattern |
| `pgrep` | Look up processes by name |
| `bg` | Resume a job in the background |
| `fg` | Bring a job to the foreground |
| `jobs` | List active jobs in the shell |
| `nohup` | Run a command immune to hangups |
| `nice` | Run a command with modified priority |
| `renice` | Alter priority of running processes |
| `ping` | Send ICMP echo requests to hosts |
| `curl` | Transfer data from or to a server |
| `wget` | Download files from the web |
| `ssh` | Secure shell remote login |
| `scp` | Securely copy files between hosts |
| `netstat` | Show network connections and stats |
| `ss` | Show socket statistics |
| `ifconfig` | Configure network interfaces |
| `ip` | Show and manipulate network settings |
| `nc` | Read and write network connections |
| `traceroute` | Trace the route to a host |
| `dig` | DNS lookup utility |
| `nslookup` | Query DNS name servers |
| `route` | Show and manipulate IP routing table |
| `arp` | Manipulate the ARP cache |
| `nmap` | Network exploration and security scanning |
| `telnet` | Connect to remote hosts via telnet |
| `rsync` | Remote file and directory synchronization |
| `tcpdump` | Capture and analyze network packets |
| `sudo` | Execute commands as superuser |
| `su` | Switch user identity |
| `useradd` | Create a new user account |
| `userdel` | Delete a user account |
| `usermod` | Modify a user account |
| `passwd` | Change user password |
| `groupadd` | Create a new group |
| `groups` | Show group memberships |
| `chage` | Change user password expiry info |
| `find` | Search for files in directory tree |
| `locate` | Find files by name quickly |
| `which` | Locate a command in the PATH |
| `whereis` | Locate binary, source, and man pages |
| `type` | Show how a command would be interpreted |
| `file` | Determine file type |
| `updatedb` | Update the file name database |
| `tar` | Archive files using tape archive format |
| `gzip` | Compress files using Lempel-Ziv coding |
| `gunzip` | Decompress gzip compressed files |
| `zip` | Package and compress files |
| `unzip` | Extract compressed zip archives |
| `bzip2` | Compress files using Burrows-Wheeler algorithm |
| `xz` | Compress files using LZMA algorithm |
| `zcat` | View compressed file contents |
| `zgrep` | Search compressed files with patterns |
| `zless` | View compressed files page by page |
| `zdiff` | Compare compressed files |
| `zipgrep` | Search files inside a zip archive |
| `zipinfo` | List detailed zip archive information |
| `bzcat` | View bzip2 compressed file contents |
| `bzgrep` | Search bzip2 compressed files |
| `bunzip2` | Decompress bzip2 compressed files |
| `xzcat` | View xz compressed file contents |
| `xzgrep` | Search xz compressed files |
| `7z` | High-ratio file archiver and compressor |
| `mount` | Mount a file system |
| `umount` | Unmount a file system |
| `fdisk` | Partition table manipulator for Linux |
| `lsblk` | List information about block devices |
| `blkid` | Locate and print block device attributes |
| `mkfs` | Build a Linux file system |
| `fsck` | Check and repair a file system |
| `mkswap` | Set up a swap area |
| `swapon` | Enable swap space |
| `swapoff` | Disable swap space |
| `pvcreate` | Initialize a physical volume for LVM |
| `vgcreate` | Create an LVM volume group |
| `lvcreate` | Create an LVM logical volume |
| `lvextend` | Extend an LVM logical volume |
| `resize2fs` | Resize ext2/ext3/ext4 file systems |
| `echo` | Display a line of text |
| `man` | Display manual pages |
| `history` | Show command history |
| `alias` | Create command shortcuts |
| `clear` | Clear the terminal screen |
| `exit` | Exit the shell |
| `export` | Set environment variables |
| `source` | Execute commands from a file |
| `xargs` | Build and execute command lines |
| `tee` | Read stdin and write to files |
| `watch` | Execute a command periodically |
| `sleep` | Delay for a specified time |
| `lsof` | List open files |
| `crontab` | Schedule periodic commands |
| `journalctl` | Query the systemd journal |
| `dmesg` | Print kernel ring buffer messages |
| `logger` | Make entries in the system log |
| `logrotate` | Rotate, compress, and remove log files |
| `vmstat` | Report virtual memory statistics |
| `iostat` | Report CPU and I/O statistics |
| `sar` | Collect and report system activity |
| `lscpu` | Display CPU architecture information |
| `lsmem` | List available memory ranges |
| `systemctl` | Control systemd services and units |
| `service` | Run System V init scripts |
| `chkconfig` | Enable or disable system services |
| `openssl` | Cryptography and SSL/TLS toolkit |
| `ssh-keygen` | Generate SSH authentication key pairs |
| `ssh-copy-id` | Install SSH keys on a remote machine |
| `ufw` | Uncomplicated firewall management |
| `iptables` | Configure Linux kernel packet filtering |
| `keytool` | Manage Java keystores and certificates |
| `certutil` | Manage certificates and key databases |

## Practice & Resources

| Resource | Link |
|----------|------|
| **Practice Linux interactively** | [Open Terminal](https://technoscripts.com/cli/linux/?utm_source=github&utm_medium=repository&utm_campaign=cli-practice) |
| **Download PDF Cheatsheet** | [Get Cheatsheet](https://technoscripts.com/command-playground/cheatsheet/linux-commands/?utm_source=github&utm_medium=repository&utm_campaign=cheatsheet) |
| **Typing Practice** | [Type Linux Commands](https://technoscripts.com/command-playground/typing-practice/linux/?utm_source=github&utm_medium=repository&utm_campaign=typing) |
| **All 105+ CLI Tools** | [Browse Tools Directory](https://technoscripts.com/command-playground/?utm_source=github&utm_medium=repository&utm_campaign=tools-directory) |

---

*Part of the [CLI Commands Cheatsheet](../README.md) collection by [TechnoScripts](https://technoscripts.com/?utm_source=github&utm_medium=repository&utm_campaign=tool-page)*
