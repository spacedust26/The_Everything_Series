# 🐧 Linux Commands and Their Usage

## 🗂️ File and Directory Management
| Command     | Description                             |
|-------------|-----------------------------------------|
| `ls`        | List directory contents                 |
| `cd`        | Change the current directory            |
| `pwd`       | Show present working directory          |
| `mkdir`     | Create a new directory                  |
| `rmdir`     | Remove an empty directory               |
| `rm`        | Delete files or directories             |
| `touch`     | Create a new empty file                 |
| `cp`        | Copy files or directories               |
| `mv`        | Move or rename files/directories        |
| `find`      | Search for files and directories        |
| `locate`    | Find files quickly using a database     |
| `tree`      | Display directory structure in tree format |

## 📄 File Content and Processing
| Command     | Description                             |
|-------------|-----------------------------------------|
| `cat`       | Concatenate and display file content    |
| `more`      | View file content one page at a time    |
| `less`      | Scrollable file viewer                  |
| `head`      | View the first few lines of a file      |
| `tail`      | View the last few lines of a file       |
| `cut`       | Extract sections from lines of a file   |
| `wc`        | Word, line, character count             |
| `sort`      | Sort lines of text files                |
| `uniq`      | Remove duplicate lines                  |
| `grep`      | Search text using patterns              |
| `diff`      | Compare two files line by line          |
| `cmp`       | Compare two files byte by byte          |
| `awk`       | Pattern scanning and processing         |
| `sed`       | Stream editor for filtering text        |

## 🔍 System Information
| Command     | Description                             |
|-------------|-----------------------------------------|
| `uname`     | Show system information                 |
| `top`       | Real-time view of running processes     |
| `htop`      | Improved version of `top`               |
| `ps`        | Display running processes               |
| `whoami`    | Show current user                       |
| `uptime`    | System running time                     |
| `hostname`  | Display system hostname                 |
| `df`        | Show disk space usage                   |
| `du`        | Show directory space usage              |
| `free`      | Display memory usage                    |
| `vmstat`    | Report system performance               |
| `lscpu`     | Show CPU info                           |
| `lsblk`     | List block devices                      |
| `lspci`     | Show PCI devices                        |
| `lsusb`     | Show USB devices                        |

## 👤 User Management
| Command     | Description                             |
|-------------|-----------------------------------------|
| `adduser`   | Add a new user                          |
| `deluser`   | Delete a user                           |
| `usermod`   | Modify a user account                   |
| `passwd`    | Change user password                    |
| `id`        | Show UID and GID                        |
| `groups`    | Show user groups                        |
| `who`       | Show who is logged in                   |
| `w`         | Show user activity                      |
| `su`        | Switch user                             |
| `sudo`      | Execute command as another user         |

## 📦 Package Management (Debian-based)
| Command       | Description                           |
|---------------|---------------------------------------|
| `apt update`  | Update package lists                  |
| `apt upgrade` | Upgrade installed packages            |
| `apt install` | Install a new package                 |
| `apt remove`  | Remove a package                      |
| `apt search`  | Search for a package                  |
| `dpkg`        | Low-level Debian package manager      |

## 🔐 Permissions and Ownership
| Command     | Description                             |
|-------------|-----------------------------------------|
| `chmod`     | Change permissions                      |
| `chown`     | Change ownership                        |
| `chgrp`     | Change group ownership                  |

## 🌐 Networking
| Command     | Description                             |
|-------------|-----------------------------------------|
| `ping`      | Test network connection                 |
| `ifconfig`  | Show/configure interfaces (deprecated)  |
| `ip`        | Show/manage network settings            |
| `netstat`   | Show network connections (deprecated)   |
| `ss`        | Show socket stats (modern replacement)  |
| `curl`      | Transfer data from/to server            |
| `wget`      | Download files from internet            |
| `nslookup`  | DNS lookup                              |
| `dig`       | Advanced DNS query                      |
| `traceroute`| Trace network path                      |

## ⚙️ Process Management
| Command     | Description                             |
|-------------|-----------------------------------------|
| `kill`      | Terminate process by PID                |
| `killall`   | Terminate by name                       |
| `nice`      | Start process with priority             |
| `renice`    | Change process priority                 |
| `bg`        | Resume background process               |
| `fg`        | Bring background process to foreground  |
| `jobs`      | List background jobs                    |

## 🔧 Disk and Storage
| Command     | Description                             |
|-------------|-----------------------------------------|
| `mount`     | Mount filesystem/device                 |
| `umount`    | Unmount filesystem                      |
| `fsck`      | Check and repair filesystem             |
| `mkfs`      | Make filesystem                         |
| `parted`    | Manage partitions                       |
| `fdisk`     | Disk partition editor                   |

## 🔄 Compression and Archiving
| Command     | Description                             |
|-------------|-----------------------------------------|
| `tar`       | Archive files                           |
| `zip`       | Compress to ZIP                         |
| `unzip`     | Extract ZIP archives                    |
| `gzip`      | Compress files                          |
| `gunzip`    | Decompress `.gz` files                  |
| `xz`/`unxz` | High compression ratio tools            |

## 💻 Shell and Script Related
| Command     | Description                             |
|-------------|-----------------------------------------|
| `echo`      | Display text                            |
| `read`      | Take user input                         |
| `export`    | Set environment variable                |
| `alias`     | Create command alias                    |
| `source`    | Execute a script in current shell       |
| `bash`      | Start new shell                         |
| `history`   | Show command history                    |
| `crontab`   | Schedule recurring tasks                |
