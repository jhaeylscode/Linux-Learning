# Linux Learning Guide

<p align="center">
  <img src="logo.png" alt="Linux Logo" width="50%">
</p>

---

**Created by:** [CLOUDWERX LAB](http://cloudwerx.dev)  
**Repository:** [github.com/CLOUDWERX-DEV/Linux-Learning](https://github.com/CLOUDWERX-DEV/Linux-Learning)  
**License:** Open Source - Free to use, share, and modify
---

## Welcome to Linux!

This comprehensive guide is designed to take you from complete beginner to confident Linux user. Whether you're a student, developer, system administrator, or just curious about Linux, this guide will help you master the command line and understand how Linux works.

We'll start with the absolute basics and gradually build up your knowledge. Don't worry if things seem overwhelming at first - everyone starts somewhere, and with practice, these commands will become second nature!

### Why Learn Linux?

**Linux is everywhere:**
- 🌐 **Web servers**: Over 90% of the internet runs on Linux
- 📱 **Mobile devices**: Android is built on Linux
- ☁️ **Cloud computing**: AWS, Google Cloud, Azure all use Linux
- 🖥️ **Supercomputers**: 100% of the world's top 500 supercomputers run Linux
- 🏠 **IoT devices**: Smart home devices, routers, TVs
- 🚀 **Space**: NASA, SpaceX, and the International Space Station use Linux

**Career benefits:**
- High demand for Linux skills in IT, DevOps, and cybersecurity
- Better understanding of how computers and networks work
- Essential for cloud computing and containerization (Docker, Kubernetes)
- Foundation for programming and software development
- Automation and scripting capabilities

**Personal benefits:**
- Complete control over your computer
- Free and open source - no licensing costs
- Privacy and security focused
- Highly customizable to your needs
- Runs efficiently on older hardware
- Vibrant community support

### What Makes This Guide Different?

✅ **Beginner-friendly**: Clear explanations without assuming prior knowledge  
✅ **Progressive learning**: Builds from basics to advanced topics  
✅ **Real-world examples**: Practical scenarios you'll actually encounter  
✅ **Hands-on practice**: Exercises at every level  
✅ **Comprehensive**: Covers everything from navigation to system administration  
✅ **Quick reference**: Includes a printable command reference card  

### How to Use This Guide

1. **Start at the beginning** if you're new to Linux
2. **Follow along** by typing commands in your terminal
3. **Practice regularly** - repetition builds muscle memory
4. **Don't rush** - take time to understand each concept
5. **Experiment safely** - use a virtual machine or test system
6. **Join the community** - ask questions, share knowledge

### Prerequisites

- A computer running Linux (Ubuntu, Linux Mint, Debian, Fedora, etc.)
- OR a virtual machine with Linux installed
- OR Windows Subsystem for Linux (WSL)
- Basic computer literacy (using a mouse, keyboard, opening applications)
- Curiosity and willingness to learn!

### What You'll Learn

**Beginner Level:**
- Understanding the Linux filesystem
- Navigating with the terminal
- Creating, moving, and deleting files
- File permissions and ownership
- Viewing and editing text files
- Finding files and searching content
- Managing processes
- Installing software

**Intermediate Level:**
- Shell scripting and automation
- Pipes and redirection
- Text processing with grep, sed, awk
- Archives and compression
- System information and monitoring
- Networking basics
- User and group management
- Environment variables and PATH
- Job scheduling with cron

**Advanced Level:**
- Advanced shell scripting
- systemd service management
- Advanced file operations
- Disk management and mounting
- Network configuration and troubleshooting
- Firewall configuration
- Process management and debugging
- Performance tuning
- Security basics
- Troubleshooting and recovery

---

## Table of Contents

### Getting Started
1. [What is Linux?](#what-is-linux)
2. [Understanding the Linux Filesystem](#understanding-the-linux-filesystem)
3. [Getting Started with the Terminal](#getting-started-with-the-terminal)

### Beginner Topics
4. [Essential Commands for Beginners](#essential-commands-for-beginners)
5. [Working with Files and Directories](#working-with-files-and-directories)
6. [Understanding Permissions](#understanding-permissions)
7. [Text Viewing and Editing](#text-viewing-and-editing)
8. [Finding Files and Searching Content](#finding-files-and-searching-content)
9. [Managing Processes](#managing-processes)
10. [Package Management](#package-management)

### Intermediate Topics
11. [Shell Basics and Scripting](#shell-basics-and-scripting)
12. [Pipes and Redirection](#pipes-and-redirection)
13. [Archives and Compression](#archives-and-compression)
14. [System Information](#system-information)
15. [Networking Basics](#networking-basics)
16. [User and Group Management](#user-and-group-management)
17. [Environment and PATH](#environment-and-path)
18. [Job Scheduling with Cron](#job-scheduling-with-cron)

### Advanced Topics
19. [Advanced Shell Scripting](#advanced-shell-scripting)
20. [systemd Service Management](#systemd-service-management)
21. [Advanced File Operations](#advanced-file-operations)
22. [Disk Management](#disk-management)
23. [Networking Deep Dive](#networking-deep-dive)
24. [Process Management Deep Dive](#process-management-deep-dive)
25. [Security Basics](#security-basics)
26. [Performance Tuning](#performance-tuning)
27. [Troubleshooting Guide](#troubleshooting-guide)

### Resources
28. [Useful Tips and Tricks](#useful-tips-and-tricks)
29. [Practice Exercises](#practice-exercises)
30. [Additional Resources](#additional-resources)
31. [Quick Reference Card](Card.md)

---

## What is Linux?

Linux is an operating system, just like Windows or macOS. It's the software that manages your computer's hardware and provides services for running applications.

### A Brief History

- **1991**: Linus Torvalds, a Finnish student, creates Linux as a hobby project
- **1992**: Linux becomes open source under the GPL license
- **1993-1994**: First Linux distributions emerge (Slackware, Debian)
- **2000s**: Linux dominates web servers and supercomputers
- **2008**: Android (based on Linux) launches
- **Today**: Linux powers billions of devices worldwide

### Key Concepts

#### Open Source
The source code is freely available for anyone to:
- View and study how it works
- Modify and customize for their needs
- Distribute and share with others
- Contribute improvements back to the community

This creates a collaborative ecosystem where thousands of developers worldwide improve Linux every day.

#### Distributions (Distros)
Linux comes in many "flavors" called distributions. Each distro packages the Linux kernel with different software, desktop environments, and tools.

**Popular distributions:**
- **Ubuntu**: Beginner-friendly, great community support
- **Linux Mint**: Based on Ubuntu, very user-friendly
- **Debian**: Stable, reliable, basis for many other distros
- **Fedora**: Cutting-edge features, sponsored by Red Hat
- **Arch Linux**: Minimalist, for advanced users
- **CentOS/Rocky Linux**: Enterprise-focused, server use
- **Kali Linux**: Security and penetration testing

**Which should you choose?**
- **New to Linux?** Start with Ubuntu or Linux Mint
- **Want stability?** Choose Debian or Ubuntu LTS
- **Like latest features?** Try Fedora
- **Server use?** Consider Ubuntu Server, Debian, or Rocky Linux

#### The Linux Kernel
The kernel is the core of the operating system. It:
- Manages hardware (CPU, memory, devices)
- Handles processes and scheduling
- Provides security and access control
- Manages file systems and storage
- Handles networking

When people say "Linux," they technically mean the kernel. A complete system includes the kernel plus GNU tools, desktop environments, and applications.

#### Terminal/Shell
The terminal (also called command line or shell) is a text-based interface where you type commands. It might seem old-fashioned, but it's incredibly powerful:

**Why use the terminal?**
- **Speed**: Faster than clicking through menus
- **Power**: Can do things GUIs can't
- **Automation**: Write scripts to automate tasks
- **Remote access**: Manage servers over SSH
- **Precision**: Exact control over what happens
- **Efficiency**: Chain commands together

**Common shells:**
- **bash**: Most common, default on most systems
- **zsh**: Modern, feature-rich (default on macOS)
- **fish**: User-friendly, great auto-completion
- **sh**: Original Unix shell, very basic

#### Root User
The root user (also called superuser) is the administrator account with complete system access. It can:
- Install and remove software
- Modify system files
- Create and delete users
- Change any file or setting

**Important safety notes:**
- Don't run as root for daily use
- Use `sudo` to run individual commands as root
- Be careful with `sudo` - it can break your system
- Never run commands you don't understand

### Linux vs Windows vs macOS

| Feature | Linux | Windows | macOS |
|---------|-------|---------|-------|
| **Cost** | Free | Paid | Paid (with Mac) |
| **Open Source** | Yes | No | Partially |
| **Customization** | Extensive | Limited | Limited |
| **Hardware Support** | Wide range | Wide range | Apple only |
| **Software** | Growing | Most | Good |
| **Gaming** | Improving | Best | Good |
| **Security** | Excellent | Good | Excellent |
| **Privacy** | Excellent | Concerns | Good |
| **Learning Curve** | Moderate | Easy | Easy |
| **Server Use** | Dominant | Common | Rare |

### The Linux Philosophy

Linux follows the Unix philosophy:
1. **Do one thing well**: Each tool has a specific purpose
2. **Work together**: Tools can be combined (pipes, redirection)
3. **Text streams**: Universal interface for data
4. **Everything is a file**: Consistent way to interact with system
5. **Small, sharp tools**: Many simple tools instead of few complex ones

This philosophy makes Linux powerful and flexible. You'll see it in action as you learn commands.

### Getting Help

The Linux community is welcoming and helpful. When you need assistance:

**Built-in help:**
- `man command` - Manual pages (detailed documentation)
- `command --help` - Quick help summary
- `info command` - Info pages (alternative to man)
- `apropos keyword` - Search for commands

**Online resources:**
- [Stack Overflow](https://stackoverflow.com) - Q&A for specific problems
- [Ask Ubuntu](https://askubuntu.com) - Ubuntu-specific questions
- [Reddit r/linux4noobs](https://reddit.com/r/linux4noobs) - Beginner-friendly
- [Linux Documentation Project](https://tldp.org) - Comprehensive guides
- [Arch Wiki](https://wiki.archlinux.org) - Excellent even for non-Arch users

**Community:**
- IRC channels (#linux, #ubuntu, etc.)
- Discord servers
- Local Linux user groups (LUGs)
- Forums for your specific distribution

**Tips for asking questions:**
1. Search first - your question may already be answered
2. Be specific - include error messages, what you tried
3. Show your work - demonstrate you've attempted to solve it
4. Be patient and polite
5. Share your solution when you find it

---

## Understanding the Linux Filesystem

### Everything is a File

One of Linux's core concepts is "everything is a file." This means:
- Regular files (documents, images, programs)
- Directories (folders)
- Devices (hard drives, USB, keyboard, mouse)
- Processes (running programs)
- Network connections
- System information

This unified approach makes the system consistent and predictable. You interact with everything using similar commands and concepts.

### The Filesystem Hierarchy

Unlike Windows (which has separate drive letters like C:, D:, E:), Linux has a single unified filesystem starting at `/` (called "root" - not to be confused with the root user).

Think of it like a tree:
```
/                           (root - the top of everything)
├── home/                   (user home directories)
│   ├── john/              (john's personal files)
│   └── jane/              (jane's personal files)
├── etc/                    (system configuration files)
├── var/                    (variable data - logs, caches)
│   ├── log/               (system and application logs)
│   └── www/               (web server files)
├── usr/                    (user programs and data)
│   ├── bin/               (user programs)
│   ├── lib/               (program libraries)
│   └── share/             (shared data)
├── tmp/                    (temporary files)
├── bin/                    (essential programs)
├── boot/                   (boot loader files)
├── dev/                    (device files)
├── opt/                    (optional software)
├── proc/                   (process information)
└── sys/                    (system information)
```

### Important Directories Explained

#### For Everyday Users

| Directory | What it contains | When you'll use it | Example |
|-----------|------------------|-------------------|---------|
| `/home/username` | Your personal files | Every day - this is YOUR space | `/home/john/Documents` |
| `/tmp` | Temporary files (cleared on reboot) | For temporary work | `/tmp/download.zip` |
| `/media` or `/mnt` | Mounted drives (USB, external drives) | When accessing external storage | `/media/usb-drive` |

#### For Configuration

| Directory | What it contains | When you'll use it | Example |
|-----------|------------------|-------------------|---------|
| `/etc` | System configuration files | When configuring software | `/etc/apache2/apache2.conf` |
| `/home/username/.config` | User configuration files | Customizing applications | `~/.config/Code/settings.json` |

#### For System Information

| Directory | What it contains | When you'll use it | Example |
|-----------|------------------|-------------------|---------|
| `/var/log` | Log files (system activity) | Troubleshooting problems | `/var/log/syslog` |
| `/proc` | Process and system info | Checking system status | `/proc/cpuinfo` |
| `/sys` | Hardware information | Hardware troubleshooting | `/sys/class/net` |

#### For Programs

| Directory | What it contains | When you'll use it | Example |
|-----------|------------------|-------------------|---------|
| `/bin` | Essential system programs | Rarely directly | `/bin/ls` |
| `/usr/bin` | User programs | Rarely directly | `/usr/bin/firefox` |
| `/usr/local/bin` | Locally installed programs | Custom software | `/usr/local/bin/myapp` |
| `/opt` | Optional/third-party software | Some applications | `/opt/google/chrome` |

#### For System Files

| Directory | What it contains | When you'll use it | Example |
|-----------|------------------|-------------------|---------|
| `/boot` | Boot loader and kernel | System updates | `/boot/vmlinuz` |
| `/dev` | Device files | Hardware access | `/dev/sda1` |
| `/lib` | System libraries | Rarely directly | `/lib/x86_64-linux-gnu` |
| `/var` | Variable data (logs, caches) | Troubleshooting | `/var/cache/apt` |

### Path Types

**Absolute paths** start from root (`/`):
```bash
/home/john/Documents/report.txt
/etc/apache2/apache2.conf
/usr/bin/python3
```

**Relative paths** start from your current location:
```bash
Documents/report.txt          # If you're in /home/john
../jane/Documents/file.txt    # Go up one level, then down
./script.sh                   # Current directory
```

**Special path shortcuts:**
- `~` - Your home directory (`/home/username`)
- `.` - Current directory
- `..` - Parent directory (one level up)
- `-` - Previous directory
- `/` - Root directory

**Examples:**
```bash
cd ~              # Go to your home directory
cd ~/Documents    # Go to your Documents folder
cd ..             # Go up one level
cd ../..          # Go up two levels
cd -              # Go back to previous directory
```

### Hidden Files

Files and directories starting with `.` are hidden:
- `.bashrc` - Bash configuration
- `.config/` - Application configurations
- `.ssh/` - SSH keys and config
- `.gitconfig` - Git configuration

View hidden files with `ls -a`

### File Extensions

Unlike Windows, Linux doesn't rely on file extensions to determine file types. A file named `script` can be executable, while `document.txt` might be a program.

The system uses:
- **File permissions** (execute bit) to determine if it's executable
- **File content** (magic numbers) to determine file type
- **Shebang** (`#!/bin/bash`) in scripts to specify interpreter

However, extensions are still useful for humans and some applications.

---

## Getting Started with the Terminal

The terminal (also called shell or command line) is where you type commands. Don't be intimidated - it's just another way to interact with your computer, and it's incredibly powerful once you get comfortable!

### Opening the Terminal

**Linux Mint / Ubuntu / Debian:**
- Press `Ctrl + Alt + T`
- Or search for "Terminal" in the application menu
- Or right-click on desktop and select "Open Terminal"

**Other methods:**
- Many file managers have "Open Terminal Here" option
- Some desktop environments have terminal in the panel

### Understanding the Prompt

When you open a terminal, you'll see something like:
```
john@laptop:~$
```

Let's break this down:
- `john` - Your username
- `@` - Separator
- `laptop` - Your computer's hostname
- `:` - Separator
- `~` - Your current location (~ means home directory)
- `$` - You're a regular user

If you see `#` instead of `$`, you're root (administrator) - be careful!

**The prompt changes as you navigate:**
```
john@laptop:~$ cd Documents
john@laptop:~/Documents$ cd /etc
john@laptop:/etc$
```

### Your First Commands

Let's try some safe, simple commands to get comfortable:

```bash
# Show where you are (Print Working Directory)
pwd
# Output: /home/john

# List files in current directory
ls
# You'll see your folders like Documents, Downloads, Desktop, etc.

# Show who you are
whoami
# Output: john

# Show the date and time
date
# Output: Wed Jan 15 10:30:45 AM EST 2025

# Show a calendar
cal
# Shows current month's calendar

# Clear the screen
clear
# Or press Ctrl+L

# Show system information
uname -a
# Shows kernel version and system info
```

**What just happened?**
- `pwd` = "Print Working Directory" - shows your current location in the filesystem
- `ls` = "List" - shows files and folders in current directory
- `whoami` = shows your username
- `date` = shows current date and time
- `cal` = shows a calendar
- `clear` = clears the terminal screen
- `uname` = shows system information

### Important Terminal Concepts

**Commands are case-sensitive!**
- `ls` works ✓
- `LS` doesn't work ✗
- `Ls` doesn't work ✗

**Spaces matter!**
- `ls -l` (correct - space between command and option)
- `ls-l` (wrong - no space)

**Options modify command behavior:**
- Short options: `-a`, `-l`, `-h`
- Combined short options: `-lah` (same as `-l -a -h`)
- Long options: `--all`, `--help`, `--version`

**Arguments are what the command acts on:**
```bash
ls Documents        # 'Documents' is the argument
cp file.txt backup/ # 'file.txt' and 'backup/' are arguments
```

### Terminal Shortcuts You Need to Know

These will save you tons of time:

**Navigation:**
- `Ctrl + A` - Move to beginning of line
- `Ctrl + E` - Move to end of line
- `Alt + B` - Move back one word
- `Alt + F` - Move forward one word

**Editing:**
- `Ctrl + U` - Delete from cursor to beginning
- `Ctrl + K` - Delete from cursor to end
- `Ctrl + W` - Delete word before cursor
- `Ctrl + Y` - Paste deleted text

**Control:**
- `Ctrl + C` - Cancel current command
- `Ctrl + Z` - Suspend current command
- `Ctrl + D` - Exit terminal (or end input)
- `Ctrl + L` - Clear screen (same as `clear`)

**History:**
- `↑` (Up arrow) - Previous command
- `↓` (Down arrow) - Next command
- `Ctrl + R` - Search command history (type to search, Enter to run)
- `!!` - Repeat last command
- `!$` - Last argument of previous command

**Auto-completion:**
- `Tab` - Auto-complete file/command names
- `Tab Tab` - Show all possible completions

**Practice these shortcuts - they'll become muscle memory!**

### Common Beginner Mistakes

1. **Forgetting sudo for system commands**
   ```bash
   apt install firefox     # Error: permission denied
   sudo apt install firefox # Correct
   ```

2. **Not using quotes for filenames with spaces**
   ```bash
   cat my file.txt         # Wrong - tries to cat 'my' and 'file.txt'
   cat "my file.txt"       # Correct
   cat my\ file.txt        # Also correct (escaped space)
   ```

3. **Using rm without thinking**
   ```bash
   rm -rf *                # DANGER - deletes everything!
   rm -i file.txt          # Safer - asks for confirmation
   ```

4. **Not reading error messages**
   - Error messages tell you what went wrong
   - Read them carefully before asking for help

5. **Copying commands without understanding**
   - Always understand what a command does before running it
   - Especially with `sudo` or `rm`

### Tips for Success

1. **Practice regularly** - Use the terminal daily, even for simple tasks
2. **Type commands yourself** - Don't just copy-paste, build muscle memory
3. **Read man pages** - `man ls` shows the manual for `ls`
4. **Experiment safely** - Use a test directory or virtual machine
5. **Don't fear mistakes** - You'll learn more from errors than successes
6. **Use tab completion** - Let the computer do the typing
7. **Keep notes** - Write down useful commands you discover


---

## Essential Commands for Beginners

### Getting Help

Before we dive in, know that you can get help anytime:

```bash
# Get help for a command (press 'q' to quit)
man ls          # Manual page for 'ls'
ls --help       # Quick help for 'ls'
help cd         # Help for built-in commands like 'cd'
```

**How to read man pages:**
- Press `Space` to go down one page
- Press `b` to go back one page
- Type `/word` to search for "word"
- Press `n` to find next match
- Press `q` to quit

### Navigation Commands

Moving around the filesystem:

```bash
# Go to your home directory
cd
# or
cd ~

# Go to a specific folder
cd Documents
cd /home/username/Pictures

# Go up one level (to parent directory)
cd ..

# Go back to previous directory
cd -

# See where you are
pwd
```

**Real example:**
```bash
pwd                    # Shows: /home/john
cd Documents           # Move into Documents
pwd                    # Shows: /home/john/Documents
cd ..                  # Go back up
pwd                    # Shows: /home/john
```

### Listing Files

```bash
# Basic list
ls

# List with details (permissions, size, date)
ls -l

# List all files (including hidden ones starting with .)
ls -a

# List with human-readable sizes
ls -lh

# Combine options (detailed + hidden + human-readable)
ls -lah
```

**Understanding `ls -l` output:**
```
-rw-r--r-- 1 john john 1.2K Jan 15 10:30 myfile.txt
│          │ │    │    │    │            └─ filename
│          │ │    │    │    └─ date modified
│          │ │    │    └─ file size
│          │ │    └─ group owner
│          │ └─ user owner
│          └─ number of links
└─ permissions (we'll explain this later!)
```

---

## Working with Files and Directories

### Creating Directories

```bash
# Create a single directory
mkdir my_project

# Create nested directories (parent + child)
mkdir -p projects/web/html
# This creates: projects/ then projects/web/ then projects/web/html/

# Create multiple directories at once
mkdir folder1 folder2 folder3
```

**Beginner tip**: Use underscores or hyphens instead of spaces in names. `my_project` is easier than `my project` (which needs quotes).

### Creating Files

```bash
# Create an empty file
touch newfile.txt

# Create multiple files
touch file1.txt file2.txt file3.txt
```

### Copying Files and Directories

```bash
# Copy a file
cp source.txt destination.txt

# Copy a file to a directory
cp myfile.txt Documents/

# Copy a directory and all its contents
cp -r my_folder backup_folder
# The -r means "recursive" (include everything inside)

# Copy with verbose output (shows what's being copied)
cp -v file.txt backup.txt
```

**Real example:**
```bash
# Make a backup of an important file
cp important.txt important.txt.backup

# Copy your entire Documents folder
cp -r Documents Documents_backup
```

### Moving and Renaming

In Linux, moving and renaming use the same command: `mv`

```bash
# Rename a file
mv oldname.txt newname.txt

# Move a file to a directory
mv myfile.txt Documents/

# Move and rename at the same time
mv oldfile.txt Documents/newfile.txt

# Move a directory
mv old_folder new_location/
```

### Deleting Files and Directories

**⚠️ WARNING**: There's no "Recycle Bin" in the terminal. Deleted = gone forever!

```bash
# Delete a file
rm unwanted.txt

# Delete multiple files
rm file1.txt file2.txt

# Delete a directory and everything inside (BE CAREFUL!)
rm -r old_folder
# -r means "recursive" (delete folder and all contents)

# Delete with confirmation prompt (safer!)
rm -i important.txt
# It will ask: "remove regular file 'important.txt'?" - type 'y' or 'n'

# Delete empty directory only
rmdir empty_folder
```

**Beginner safety tips:**
1. Always double-check before using `rm -r`
2. Use `ls` first to see what you're about to delete
3. Use `rm -i` when learning (asks for confirmation)
4. NEVER run `rm -rf /` or `sudo rm -rf /` (this deletes EVERYTHING!)

---

## Understanding Permissions

Every file and directory in Linux has permissions that control who can read, write, or execute it.

### The Three Permission Types

1. **Read (r)**: Can view the file's contents or list directory contents
2. **Write (w)**: Can modify the file or add/remove files in a directory
3. **Execute (x)**: Can run the file as a program, or enter a directory

### The Three User Categories

1. **Owner (u)**: The user who owns the file
2. **Group (g)**: Users in the file's group
3. **Others (o)**: Everyone else

### Reading Permissions

When you run `ls -l`, you see permissions like this:
```
-rw-r--r--  myfile.txt
drwxr-xr-x  myfolder/
```

Let's decode `-rw-r--r--`:
```
-  rw-  r--  r--
│  │    │    └─ Others: read only
│  │    └─ Group: read only
│  └─ Owner: read and write
└─ File type: - (regular file), d (directory), l (link)
```

**Common permission patterns:**
- `-rw-r--r--` (644): Regular file - owner can edit, others can read
- `-rwxr-xr-x` (755): Program - owner can edit/run, others can run
- `-rw-------` (600): Private file - only owner can read/write
- `drwxr-xr-x` (755): Directory - owner full access, others can enter/list

### Changing Permissions

```bash
# Make a file executable (so you can run it)
chmod +x script.sh

# Remove write permission for everyone
chmod -w file.txt

# Set specific permissions using numbers
chmod 644 file.txt    # rw-r--r--
chmod 755 script.sh   # rwxr-xr-x
chmod 600 private.txt # rw-------
```

**Understanding permission numbers:**
- 4 = read (r)
- 2 = write (w)
- 1 = execute (x)

Add them up for each category:
- 7 = 4+2+1 = rwx (read, write, execute)
- 6 = 4+2 = rw- (read, write)
- 5 = 4+1 = r-x (read, execute)
- 4 = 4 = r-- (read only)
- 0 = --- (no permissions)

So `chmod 755` means:
- 7 (owner): rwx
- 5 (group): r-x
- 5 (others): r-x

### Changing Ownership

```bash
# Change owner of a file (requires sudo)
sudo chown newowner file.txt

# Change owner and group
sudo chown newowner:newgroup file.txt

# Change ownership recursively (folder and all contents)
sudo chown -R username:username my_folder/
```

**When you'll use this:**
- After extracting files as root (sudo) - change them back to your user
- Setting up shared folders for multiple users
- Fixing permission problems

---

## Text Viewing and Editing

### Viewing File Contents

```bash
# Display entire file
cat myfile.txt

# View file page by page (better for long files)
less myfile.txt
# Press Space to go down, 'b' to go up, 'q' to quit

# Show first 10 lines
head myfile.txt

# Show first 20 lines
head -n 20 myfile.txt

# Show last 10 lines
tail myfile.txt

# Follow a file in real-time (great for log files!)
tail -f /var/log/syslog
# Press Ctrl+C to stop
```

**Real example - watching logs:**
```bash
# Watch system logs as they happen
sudo tail -f /var/log/syslog

# Watch a web server log
tail -f /var/log/apache2/access.log
```

### Simple Text Editing with Nano

Nano is the easiest terminal text editor for beginners.

```bash
# Open or create a file
nano myfile.txt
```

**Nano basics:**
- Type normally to add text
- Arrow keys to move around
- `Ctrl+O` to save (then press Enter)
- `Ctrl+X` to exit
- `Ctrl+K` to cut a line
- `Ctrl+U` to paste
- `Ctrl+W` to search

**Practice exercise:**
```bash
nano practice.txt
# Type: "Hello, Linux!"
# Press Ctrl+O, then Enter (to save)
# Press Ctrl+X (to exit)
cat practice.txt  # Verify it worked
```

---

## Finding Files and Searching Content

### Finding Files by Name

```bash
# Find files in current directory and subdirectories
find . -name "myfile.txt"

# Find files case-insensitive
find . -iname "myfile.txt"
# This finds: myfile.txt, MyFile.txt, MYFILE.TXT, etc.

# Find all .txt files
find . -name "*.txt"

# Find files in a specific directory
find /home/username/Documents -name "*.pdf"

# Find files modified in last 7 days
find . -type f -mtime -7

# Find large files (bigger than 100MB)
find . -type f -size +100M
```

**Real examples:**
```bash
# Find all your photos
find ~ -name "*.jpg"

# Find files you edited today
find ~/Documents -type f -mtime -1

# Find that config file you lost
find /etc -name "*apache*"
```

### Searching Inside Files

```bash
# Search for text in a file
grep "error" logfile.txt

# Search case-insensitive
grep -i "error" logfile.txt

# Search recursively in all files
grep -r "TODO" .

# Show line numbers
grep -n "error" logfile.txt

# Show 2 lines before and after match (context)
grep -C 2 "error" logfile.txt
```

**Real examples:**
```bash
# Find which config file contains a setting
grep -r "port 8080" /etc/

# Find all TODOs in your code
grep -rn "TODO" ~/projects/

# Search log files for errors
grep -i "error\|warning\|fail" /var/log/syslog
```

### Using Ripgrep (Modern Alternative)

If installed, `rg` (ripgrep) is faster and easier:

```bash
# Install ripgrep
sudo apt install ripgrep

# Search (automatically recursive and smart)
rg "error"

# Search with context
rg -C 3 "error"

# Search specific file types
rg "function" --type python
```

---

## Managing Processes

### Viewing Running Processes

```bash
# Show all running processes
ps aux

# Show processes in a tree (parent-child relationships)
ps auxf

# Show processes for current user
ps ux

# Interactive process viewer (like Task Manager)
top
# Press 'q' to quit

# Better interactive viewer (if installed)
htop
# Press F10 or 'q' to quit
```

**Understanding `ps aux` output:**
```
USER  PID  %CPU %MEM    VSZ   RSS TTY   STAT START   TIME COMMAND
john  1234  0.5  2.1  12345  6789 ?     S    10:30   0:05 firefox
│     │    │    │     │     │    │     │    │       │    └─ program name
│     │    │    │     │     │    │     │    │       └─ CPU time used
│     │    │    │     │     │    │     │    └─ start time
│     │    │    │     │     │    │     └─ state (S=sleeping, R=running)
│     │    │    │     │     │    └─ terminal
│     │    │    │     │     └─ physical memory (KB)
│     │    │    │     └─ virtual memory (KB)
│     │    │    └─ memory percentage
│     │    └─ CPU percentage
│     └─ process ID
└─ user running it
```

### Controlling Processes

```bash
# Run a command in the background
firefox &

# Suspend current process (pause it)
# Press Ctrl+Z

# List background jobs
jobs

# Bring job to foreground
fg %1

# Resume job in background
bg %1

# Kill a process by PID
kill 1234

# Force kill a stubborn process
kill -9 1234

# Kill by program name
killall firefox

# Find process ID by name
pidof firefox
```

**Real example - dealing with a frozen program:**
```bash
# Find the process
ps aux | grep firefox

# Try gentle kill first
kill 1234

# If it doesn't work, force it
kill -9 1234

# Or use killall
killall -9 firefox
```

---

## Package Management

Package managers install, update, and remove software. On Debian-based systems (Ubuntu, Mint), we use `apt`.

### Basic Package Operations

```bash
# Update package list (do this first!)
sudo apt update

# Upgrade all installed packages
sudo apt upgrade

# Install a package
sudo apt install firefox

# Install multiple packages
sudo apt install vim git curl

# Remove a package
sudo apt remove firefox

# Remove package and its configuration files
sudo apt purge firefox

# Remove unneeded packages
sudo apt autoremove

# Search for a package
apt search "text editor"

# Show package information
apt show firefox
```

**Understanding the workflow:**
1. `sudo apt update` - Downloads the latest package lists
2. `sudo apt upgrade` - Installs available updates
3. `sudo apt install package` - Installs new software

**Why `sudo`?** Installing software affects the whole system, so you need administrator (root) privileges.

### Common Packages for Beginners

```bash
# Development tools
sudo apt install build-essential git

# Text editors
sudo apt install vim nano

# System utilities
sudo apt install htop tree curl wget

# Compression tools
sudo apt install zip unzip rar unrar

# Network tools
sudo apt install net-tools openssh-server
```

---

## Intermediate Topics

Now that you're comfortable with the basics, let's explore more powerful features.

---

### Shell Basics and Scripting

#### Understanding Exit Codes

Every command returns an exit code: 0 means success, anything else means failure.

```bash
# Run a command
ls /home

# Check its exit code
echo $?
# Output: 0 (success)

# Try a failing command
ls /nonexistent

# Check exit code
echo $?
# Output: 2 (error - directory doesn't exist)
```

**Why this matters:** Scripts can check if commands succeeded before continuing.

#### Command Chaining

```bash
# Run second command only if first succeeds
mkdir test && cd test
# If mkdir fails, cd won't run

# Run second command only if first fails
cd /root || echo "Access denied"
# If cd fails, the echo runs

# Run commands in sequence (regardless of success/failure)
command1; command2; command3
```

**Real examples:**
```bash
# Compile and run (only run if compile succeeds)
gcc program.c -o program && ./program

# Try to connect, show error if it fails
ping -c 1 google.com || echo "No internet connection"

# Update and upgrade in one line
sudo apt update && sudo apt upgrade -y
```

#### Variables

```bash
# Create a variable (no spaces around =)
name="John"
age=25

# Use a variable (with $)
echo "Hello, $name"
echo "You are $age years old"

# Command output in a variable
current_dir=$(pwd)
echo "You are in: $current_dir"

# Environment variables (system-wide)
echo $HOME      # Your home directory
echo $USER      # Your username
echo $PATH      # Where the system looks for programs
```

**Real example - backup script:**
```bash
# Set variables
backup_dir="$HOME/backups"
date=$(date +%Y-%m-%d)

# Create backup
mkdir -p "$backup_dir"
cp -r ~/Documents "$backup_dir/Documents-$date"
echo "Backup created: $backup_dir/Documents-$date"
```

#### Quoting Rules

```bash
# Single quotes: everything is literal
echo 'My name is $USER'
# Output: My name is $USER

# Double quotes: variables expand
echo "My name is $USER"
# Output: My name is john

# No quotes: word splitting and globbing happen
echo *.txt
# Output: file1.txt file2.txt file3.txt

# Always quote variables to be safe
filename="my file.txt"
cat "$filename"    # Correct
cat $filename      # Wrong - treats "my" and "file.txt" as separate
```

---

### Pipes and Redirection

#### Understanding Streams

Every program has three streams:
- **stdin (0)**: Input (keyboard by default)
- **stdout (1)**: Normal output (screen by default)
- **stderr (2)**: Error messages (screen by default)

#### Redirection Basics

```bash
# Save output to a file (overwrites)
ls > filelist.txt

# Append output to a file
ls >> filelist.txt

# Redirect errors to a file
command 2> errors.txt

# Redirect both output and errors
command &> all_output.txt

# Redirect output to file, errors to another
command > output.txt 2> errors.txt

# Discard output (send to /dev/null, the "black hole")
command > /dev/null

# Discard errors
command 2> /dev/null
```

**Real examples:**
```bash
# Save directory listing
ls -lah > directory_contents.txt

# Keep a log of what you did
history > my_commands.txt

# Run a command silently
sudo apt update > /dev/null 2>&1
```

#### Pipes (Connecting Commands)

Pipes (`|`) send the output of one command as input to another.

```bash
# Count files in a directory
ls | wc -l

# Search process list
ps aux | grep firefox

# Sort and show unique items
cat names.txt | sort | uniq

# Show top 10 largest files
du -ah | sort -rh | head -10

# Page through long output
ls -la /usr/bin | less
```

**Real examples:**
```bash
# Find your most used commands
history | awk '{print $2}' | sort | uniq -c | sort -rn | head -10

# Monitor system logs for errors
sudo tail -f /var/log/syslog | grep -i error

# Count how many processes you're running
ps aux | grep $USER | wc -l
```

---

### Archives and Compression

#### Working with Tar Archives

`tar` bundles multiple files into one archive file.

```bash
# Create an archive
tar -cvf archive.tar folder/
# -c = create
# -v = verbose (show progress)
# -f = file (specify archive name)

# Create a compressed archive (gzip)
tar -czvf archive.tar.gz folder/
# -z = compress with gzip

# Create a compressed archive (bzip2, better compression)
tar -cjvf archive.tar.bz2 folder/
# -j = compress with bzip2

# List contents without extracting
tar -tvf archive.tar.gz

# Extract an archive
tar -xvf archive.tar.gz
# -x = extract

# Extract to specific directory
tar -xvf archive.tar.gz -C /destination/path/
```

**Real examples:**
```bash
# Backup your documents
tar -czvf documents-backup-$(date +%Y%m%d).tar.gz ~/Documents/

# Extract a downloaded archive
tar -xzvf downloaded-software.tar.gz

# Create a backup excluding certain files
tar -czvf backup.tar.gz --exclude='*.tmp' --exclude='cache' ~/project/
```

#### Working with Zip Files

```bash
# Create a zip file
zip -r archive.zip folder/

# Extract a zip file
unzip archive.zip

# List contents
unzip -l archive.zip

# Extract to specific directory
unzip archive.zip -d /destination/path/
```

---

### System Information

#### Hardware Information

```bash
# CPU information
lscpu

# Memory information
free -h

# Disk usage
df -h

# Disk usage of current directory
du -sh

# Disk usage of subdirectories
du -h --max-depth=1

# PCI devices (graphics card, network card, etc.)
lspci

# USB devices
lsusb

# Block devices (hard drives, USB drives)
lsblk
```

#### System Information

```bash
# Kernel version
uname -r

# All system information
uname -a

# Distribution information
cat /etc/os-release

# System uptime
uptime

# Current date and time
date

# Calendar
cal

# Who is logged in
who

# Login history
last
```

**Real example - system health check:**
```bash
echo "=== System Information ==="
uname -a
echo ""
echo "=== Uptime ==="
uptime
echo ""
echo "=== Memory Usage ==="
free -h
echo ""
echo "=== Disk Usage ==="
df -h
echo ""
echo "=== Top 5 Processes by CPU ==="
ps aux --sort=-%cpu | head -6
```

---

### Networking Basics

#### Network Configuration

```bash
# Show network interfaces (modern way)
ip addr show
# or shorter:
ip a

# Show routing table
ip route

# Show network interfaces (older way, still common)
ifconfig

# Test connectivity
ping google.com
# Press Ctrl+C to stop

# Ping a specific number of times
ping -c 4 google.com

# Trace route to a host
traceroute google.com

# DNS lookup
nslookup google.com
# or
dig google.com

# Show listening ports and connections
sudo ss -tulpn
# -t = TCP
# -u = UDP
# -l = listening
# -p = show process
# -n = numeric (don't resolve names)
```

#### Downloading Files

```bash
# Download with wget
wget https://example.com/file.zip

# Download with custom name
wget -O myfile.zip https://example.com/file.zip

# Download with curl
curl -O https://example.com/file.zip

# Download and save with custom name
curl -o myfile.zip https://example.com/file.zip

# Download and show progress
curl -# -O https://example.com/largefile.zip
```

#### SSH (Secure Shell)

Connect to remote computers securely:

```bash
# Connect to a remote server
ssh username@hostname

# Connect with specific port
ssh -p 2222 username@hostname

# Copy files to remote server
scp file.txt username@hostname:/remote/path/

# Copy files from remote server
scp username@hostname:/remote/file.txt /local/path/

# Copy entire directory
scp -r folder/ username@hostname:/remote/path/
```

**Real example - managing a remote server:**
```bash
# Connect to server
ssh admin@192.168.1.100

# Copy website files to server
scp -r website/ admin@192.168.1.100:/var/www/html/

# Copy logs from server
scp admin@192.168.1.100:/var/log/apache2/error.log ~/logs/
```

---

### User and Group Management

#### User Information

```bash
# Show current user
whoami

# Show user ID and groups
id

# Show all groups you belong to
groups

# Show information about a user
finger username
# or
getent passwd username
```

#### Switching Users

```bash
# Switch to another user
su - username

# Become root (not recommended, use sudo instead)
su -

# Run a single command as root
sudo command

# Run a command as another user
sudo -u username command

# Open a root shell (use sparingly!)
sudo -i

# Keep current directory when becoming root
sudo -s
```

#### Understanding sudo

`sudo` lets you run commands with administrator privileges.

```bash
# Run a command as root
sudo apt update

# Edit a system file
sudo nano /etc/hosts

# Run multiple commands as root
sudo bash
# Now you're in a root shell - be careful!
# Type 'exit' to return to normal user
```

**Beginner safety tips:**
- Always understand what a `sudo` command does before running it
- Don't copy-paste `sudo` commands from untrusted sources
- `sudo rm -rf /` will destroy your system - never run it!

---

### Environment and PATH

#### Understanding PATH

`PATH` tells Linux where to look for programs.

```bash
# Show your PATH
echo $PATH
# Output: /usr/local/bin:/usr/bin:/bin:/usr/games

# Show where a command is located
which python3
# Output: /usr/bin/python3

# Show all locations of a command
which -a python
```

#### Adding to PATH

```bash
# Add a directory to PATH (temporary, current session only)
export PATH="$HOME/.local/bin:$PATH"

# Make it permanent (add to ~/.bashrc)
echo 'export PATH="$HOME/.local/bin:$PATH"' >> ~/.bashrc

# Reload .bashrc
source ~/.bashrc
```

**Real example - installing local programs:**
```bash
# Create a local bin directory
mkdir -p ~/.local/bin

# Add it to PATH permanently
echo 'export PATH="$HOME/.local/bin:$PATH"' >> ~/.bashrc
source ~/.bashrc

# Now you can put scripts there and run them from anywhere
cp myscript.sh ~/.local/bin/
chmod +x ~/.local/bin/myscript.sh
myscript.sh  # Works from any directory!
```

#### Shell Configuration Files

```bash
# ~/.bashrc - runs for interactive shells (your terminal)
# ~/.bash_profile or ~/.profile - runs for login shells
# /etc/bash.bashrc - system-wide bashrc
# /etc/profile - system-wide profile
```

**Common customizations for ~/.bashrc:**
```bash
# Add aliases
alias ll='ls -lah'
alias update='sudo apt update && sudo apt upgrade'
alias ..='cd ..'

# Custom prompt
PS1='\u@\h:\w\$ '

# Add to PATH
export PATH="$HOME/.local/bin:$PATH"

# Set default editor
export EDITOR=nano
```

---

### Job Scheduling with Cron

Cron runs commands automatically at scheduled times.

#### Cron Basics

```bash
# Edit your crontab (cron table)
crontab -e

# List your cron jobs
crontab -l

# Remove all your cron jobs
crontab -r
```

#### Cron Syntax

```
* * * * * command
│ │ │ │ │
│ │ │ │ └─ Day of week (0-7, 0 and 7 are Sunday)
│ │ │ └─── Month (1-12)
│ │ └───── Day of month (1-31)
│ └─────── Hour (0-23)
└───────── Minute (0-59)
```

**Examples:**
```bash
# Run every day at 2:30 AM
30 2 * * * /home/user/backup.sh

# Run every hour
0 * * * * /home/user/check.sh

# Run every 15 minutes
*/15 * * * * /home/user/monitor.sh

# Run every Monday at 9 AM
0 9 * * 1 /home/user/weekly-report.sh

# Run on the 1st of every month at midnight
0 0 1 * * /home/user/monthly-cleanup.sh
```

**Real example - automated backup:**
```bash
# Edit crontab
crontab -e

# Add this line (backup documents daily at 2 AM)
0 2 * * * tar -czf $HOME/backups/docs-$(date +\%Y\%m\%d).tar.gz $HOME/Documents/
```

---

## Advanced Topics

These topics are for when you're comfortable with the intermediate material and want to dive deeper.

---

### Advanced Shell Scripting

#### Creating Your First Script

```bash
# Create a script file
nano myscript.sh
```

Add this content:
```bash
#!/bin/bash
# This is a comment

echo "Hello, World!"
echo "Current directory: $(pwd)"
echo "Current user: $USER"
```

Make it executable and run it:
```bash
chmod +x myscript.sh
./myscript.sh
```

**Understanding the shebang (`#!/bin/bash`):**
- The first line tells Linux which interpreter to use
- `#!/bin/bash` means "use bash to run this script"
- `#!/usr/bin/env python3` would use Python

#### Script with Arguments

```bash
#!/bin/bash
# Script that uses command-line arguments

echo "Script name: $0"
echo "First argument: $1"
echo "Second argument: $2"
echo "All arguments: $@"
echo "Number of arguments: $#"
```

Run it:
```bash
./myscript.sh hello world
# Output:
# Script name: ./myscript.sh
# First argument: hello
# Second argument: world
# All arguments: hello world
# Number of arguments: 2
```

#### Conditionals (if statements)

```bash
#!/bin/bash

if [ -f "myfile.txt" ]; then
    echo "File exists"
else
    echo "File does not exist"
fi
```

**Common test conditions:**
```bash
# File tests
[ -f file ]     # File exists and is a regular file
[ -d dir ]      # Directory exists
[ -e path ]     # Path exists (file or directory)
[ -r file ]     # File is readable
[ -w file ]     # File is writable
[ -x file ]     # File is executable

# String tests
[ -z "$var" ]   # String is empty
[ -n "$var" ]   # String is not empty
[ "$a" = "$b" ] # Strings are equal
[ "$a" != "$b" ]# Strings are not equal

# Numeric tests
[ "$a" -eq "$b" ] # Equal
[ "$a" -ne "$b" ] # Not equal
[ "$a" -lt "$b" ] # Less than
[ "$a" -gt "$b" ] # Greater than
[ "$a" -le "$b" ] # Less than or equal
[ "$a" -ge "$b" ] # Greater than or equal
```

**Real example - backup script with checks:**
```bash
#!/bin/bash

backup_dir="$HOME/backups"
source_dir="$HOME/Documents"

# Check if source directory exists
if [ ! -d "$source_dir" ]; then
    echo "Error: Source directory does not exist"
    exit 1
fi

# Create backup directory if it doesn't exist
if [ ! -d "$backup_dir" ]; then
    echo "Creating backup directory..."
    mkdir -p "$backup_dir"
fi

# Create backup
timestamp=$(date +%Y%m%d_%H%M%S)
backup_file="$backup_dir/documents_$timestamp.tar.gz"

echo "Creating backup: $backup_file"
tar -czf "$backup_file" "$source_dir"

if [ $? -eq 0 ]; then
    echo "Backup completed successfully"
else
    echo "Backup failed!"
    exit 1
fi
```

#### Loops

**For loop:**
```bash
#!/bin/bash

# Loop through a list
for item in apple banana cherry; do
    echo "Fruit: $item"
done

# Loop through files
for file in *.txt; do
    echo "Processing: $file"
done

# Loop through numbers
for i in {1..5}; do
    echo "Number: $i"
done
```

**While loop:**
```bash
#!/bin/bash

counter=1
while [ $counter -le 5 ]; do
    echo "Count: $counter"
    counter=$((counter + 1))
done
```

**Real example - process multiple files:**
```bash
#!/bin/bash

# Convert all .txt files to uppercase
for file in *.txt; do
    if [ -f "$file" ]; then
        echo "Processing: $file"
        tr '[:lower:]' '[:upper:]' < "$file" > "${file%.txt}_upper.txt"
    fi
done

echo "Conversion complete!"
```

#### Functions

```bash
#!/bin/bash

# Define a function
greet() {
    echo "Hello, $1!"
}

# Call the function
greet "Alice"
greet "Bob"

# Function with return value
add() {
    local result=$(($1 + $2))
    echo $result
}

sum=$(add 5 3)
echo "5 + 3 = $sum"
```

#### Error Handling

```bash
#!/bin/bash

# Exit on any error
set -e

# Exit on undefined variable
set -u

# Exit on pipe failure
set -o pipefail

# Combine all three (recommended for robust scripts)
set -euo pipefail

# Trap errors and cleanup
cleanup() {
    echo "Cleaning up..."
    rm -f /tmp/tempfile
}

trap cleanup EXIT

# Your script here
echo "Script running..."
```

---

### systemd Service Management

systemd is the system and service manager for most modern Linux distributions.

#### Understanding Services

Services are programs that run in the background (like web servers, databases, etc.).

```bash
# Check if a service is running
systemctl status apache2

# Start a service
sudo systemctl start apache2

# Stop a service
sudo systemctl stop apache2

# Restart a service
sudo systemctl restart apache2

# Reload configuration without restarting
sudo systemctl reload apache2

# Enable service to start at boot
sudo systemctl enable apache2

# Disable service from starting at boot
sudo systemctl disable apache2

# Enable and start in one command
sudo systemctl enable --now apache2
```

#### Viewing Logs with journalctl

systemd logs everything to the journal.

```bash
# View all logs
sudo journalctl

# View logs for a specific service
sudo journalctl -u apache2

# Follow logs in real-time (like tail -f)
sudo journalctl -u apache2 -f

# Show logs since last boot
sudo journalctl -b

# Show logs from today
sudo journalctl --since today

# Show logs from specific time range
sudo journalctl --since "2025-01-15 10:00:00" --until "2025-01-15 11:00:00"

# Show only errors
sudo journalctl -p err

# Show last 50 lines
sudo journalctl -n 50

# Show kernel messages
sudo journalctl -k
```

**Real example - troubleshooting a service:**
```bash
# Check if service is running
systemctl status nginx

# If it's not running, check recent logs
sudo journalctl -u nginx -n 100

# Try to start it
sudo systemctl start nginx

# Follow logs to see what happens
sudo journalctl -u nginx -f
```

#### Creating a Custom Service

Create a service file:
```bash
sudo nano /etc/systemd/system/myapp.service
```

Add this content:
```ini
[Unit]
Description=My Application
After=network.target

[Service]
Type=simple
User=myuser
WorkingDirectory=/home/myuser/myapp
ExecStart=/home/myuser/myapp/start.sh
Restart=on-failure
RestartSec=5

[Install]
WantedBy=multi-user.target
```

**Explanation:**
- `[Unit]` section: Describes the service
  - `Description`: Human-readable name
  - `After`: Start after network is available
- `[Service]` section: How to run the service
  - `Type=simple`: Service runs in foreground
  - `User`: Which user runs the service
  - `WorkingDirectory`: Where to run from
  - `ExecStart`: Command to start the service
  - `Restart=on-failure`: Restart if it crashes
  - `RestartSec=5`: Wait 5 seconds before restarting
- `[Install]` section: When to start
  - `WantedBy=multi-user.target`: Start in normal boot

Enable and start it:
```bash
# Reload systemd to see new service
sudo systemctl daemon-reload

# Enable and start
sudo systemctl enable --now myapp.service

# Check status
systemctl status myapp.service
```

---

### Advanced File Operations

#### Finding and Acting on Files

```bash
# Find and delete old log files (older than 30 days)
find /var/log -name "*.log" -mtime +30 -delete

# Find and change permissions
find ~/scripts -name "*.sh" -exec chmod +x {} \;

# Find large files and list them
find / -type f -size +100M -exec ls -lh {} \; 2>/dev/null

# Find files and copy them
find ~/Documents -name "*.pdf" -exec cp {} ~/PDFs/ \;
```

**Understanding the syntax:**
- `{}` is replaced with each found file
- `\;` ends the `-exec` command
- `2>/dev/null` hides "permission denied" errors

#### Advanced Text Processing with awk

`awk` is a powerful text processing tool.

```bash
# Print specific columns
ps aux | awk '{print $1, $11}'
# Prints username and command

# Print lines where column 3 > 50
ps aux | awk '$3 > 50 {print $0}'
# Shows processes using >50% CPU

# Sum a column
df -h | awk '{sum += $3} END {print sum}'

# Print with custom formatting
ls -l | awk '{print "File:", $9, "Size:", $5}'
```

**Real example - analyzing log files:**
```bash
# Count occurrences of each IP address in access log
awk '{print $1}' /var/log/apache2/access.log | sort | uniq -c | sort -rn | head -10

# Show requests that took longer than 1 second
awk '$NF > 1000 {print $0}' /var/log/app/response_times.log
```

#### Advanced Text Processing with sed

`sed` is a stream editor for filtering and transforming text.

```bash
# Replace text (first occurrence per line)
sed 's/old/new/' file.txt

# Replace all occurrences
sed 's/old/new/g' file.txt

# Replace and save to new file
sed 's/old/new/g' input.txt > output.txt

# Replace in-place (modify original file)
sed -i 's/old/new/g' file.txt

# Delete lines containing a pattern
sed '/pattern/d' file.txt

# Print only lines 10-20
sed -n '10,20p' file.txt

# Delete lines 5-10
sed '5,10d' file.txt
```

**Real examples:**
```bash
# Remove comments from a config file
sed '/^#/d' config.conf

# Change all http:// to https://
sed -i 's/http:\/\//https:\/\//g' urls.txt

# Remove blank lines
sed '/^$/d' file.txt

# Add line numbers
sed = file.txt | sed 'N;s/\n/\t/'
```

---

### Disk Management

#### Viewing Disk Information

```bash
# List all block devices
lsblk

# Show disk usage by filesystem
df -h

# Show disk usage with filesystem type
df -hT

# Show inode usage
df -i

# Disk usage of directories
du -h --max-depth=1 /home

# Find largest directories
du -h /home | sort -rh | head -10
```

#### Mounting and Unmounting

```bash
# Mount a USB drive
sudo mount /dev/sdb1 /mnt/usb

# Mount with specific filesystem type
sudo mount -t ntfs /dev/sdb1 /mnt/usb

# Unmount
sudo umount /mnt/usb

# Force unmount (if busy)
sudo umount -f /mnt/usb

# Lazy unmount (unmount when no longer busy)
sudo umount -l /mnt/usb

# Show all mounted filesystems
mount | column -t
```

#### Permanent Mounts with /etc/fstab

The `/etc/fstab` file defines filesystems to mount at boot.

```bash
# View current fstab
cat /etc/fstab
```

**Example fstab entry:**
```
# <device>  <mount point>  <type>  <options>  <dump>  <pass>
/dev/sdb1   /mnt/data      ext4    defaults   0       2
UUID=1234-5678  /mnt/backup  ext4  defaults   0       2
```

**Explanation:**
- Device: `/dev/sdb1` or `UUID=...` (UUID is more reliable)
- Mount point: Where to mount it
- Type: Filesystem type (ext4, ntfs, vfat, etc.)
- Options: Mount options (defaults, ro, rw, etc.)
- Dump: Backup with dump command (0=no, 1=yes)
- Pass: fsck check order (0=skip, 1=first, 2=after root)

**Finding UUID:**
```bash
# Show UUIDs of all devices
sudo blkid

# Show UUID of specific device
sudo blkid /dev/sdb1
```

---

### Networking Deep Dive

#### Network Configuration with ip Command

```bash
# Show all network interfaces
ip link show

# Show IP addresses
ip addr show

# Show specific interface
ip addr show eth0

# Add IP address to interface
sudo ip addr add 192.168.1.100/24 dev eth0

# Remove IP address
sudo ip addr del 192.168.1.100/24 dev eth0

# Bring interface up
sudo ip link set eth0 up

# Bring interface down
sudo ip link set eth0 down

# Show routing table
ip route show

# Add a route
sudo ip route add 192.168.2.0/24 via 192.168.1.1

# Delete a route
sudo ip route del 192.168.2.0/24
```

#### Checking Open Ports and Connections

```bash
# Show all listening ports
sudo ss -tulpn

# Show all TCP connections
ss -t

# Show all UDP connections
ss -u

# Show connections to specific port
ss -tn sport = :80

# Show process using a port
sudo lsof -i :8080

# Show all network connections by process
sudo lsof -i
```

**Real example - troubleshooting port conflicts:**
```bash
# Check if port 8080 is in use
sudo lsof -i :8080

# If something is using it, find the process
sudo ss -tulpn | grep :8080

# Kill the process if needed
sudo kill <PID>
```

#### Firewall with ufw (Uncomplicated Firewall)

`ufw` is a beginner-friendly firewall interface.

```bash
# Enable firewall
sudo ufw enable

# Disable firewall
sudo ufw disable

# Check status
sudo ufw status

# Verbose status
sudo ufw status verbose

# Allow a port
sudo ufw allow 22

# Allow a port with protocol
sudo ufw allow 80/tcp

# Allow a service by name
sudo ufw allow ssh

# Allow from specific IP
sudo ufw allow from 192.168.1.100

# Allow from IP to specific port
sudo ufw allow from 192.168.1.100 to any port 22

# Deny a port
sudo ufw deny 23

# Delete a rule
sudo ufw delete allow 80

# Reset firewall (remove all rules)
sudo ufw reset
```

**Real example - web server setup:**
```bash
# Enable firewall
sudo ufw enable

# Allow SSH (so you don't lock yourself out!)
sudo ufw allow 22/tcp

# Allow HTTP and HTTPS
sudo ufw allow 80/tcp
sudo ufw allow 443/tcp

# Check status
sudo ufw status numbered
```

---

### Process Management Deep Dive

#### Process Priority (nice and renice)

Process priority ranges from -20 (highest) to 19 (lowest). Default is 0.

```bash
# Start a process with low priority
nice -n 10 command

# Start a process with high priority (requires sudo)
sudo nice -n -10 command

# Change priority of running process
renice -n 5 -p <PID>

# Change priority of all processes by user
sudo renice -n 5 -u username
```

**Real example - running a backup without slowing down system:**
```bash
# Run backup with low priority
nice -n 15 tar -czf backup.tar.gz /home/user/Documents/
```

#### Background Jobs and nohup

```bash
# Run command in background
command &

# Run command that continues after logout
nohup command &

# Run command in background and redirect output
nohup command > output.log 2>&1 &

# List background jobs
jobs

# Bring job to foreground
fg %1

# Send job to background
bg %1

# Disown a job (detach from shell)
disown %1
```

**Real example - long-running task:**
```bash
# Start a long download that continues after logout
nohup wget -c https://example.com/largefile.iso > download.log 2>&1 &

# Check progress later
tail -f download.log
```

#### Monitoring System Resources

```bash
# Interactive process viewer
htop

# Show processes in tree format
pstree

# Show processes by CPU usage
ps aux --sort=-%cpu | head -20

# Show processes by memory usage
ps aux --sort=-%mem | head -20

# Monitor specific process
watch -n 1 'ps aux | grep processname'

# System resource summary
vmstat 1

# I/O statistics
iostat -x 1

# Network statistics
netstat -i
```

---

### Security Basics

#### File Permissions Deep Dive

**Special permissions:**

```bash
# Setuid (s in user position)
# File runs with owner's permissions
chmod u+s file
chmod 4755 file

# Setgid (s in group position)
# File runs with group's permissions
# New files in directory inherit group
chmod g+s directory
chmod 2755 directory

# Sticky bit (t in others position)
# Only owner can delete files in directory
chmod +t directory
chmod 1755 directory
```

**Real example - shared project directory:**
```bash
# Create shared directory
sudo mkdir /shared/project
sudo chgrp developers /shared/project

# Set permissions: group writable + setgid + sticky
sudo chmod 2775 /shared/project

# Now all files created here belong to 'developers' group
# and only file owners can delete their own files
```

#### SSH Key Authentication

More secure than passwords!

```bash
# Generate SSH key pair
ssh-keygen -t ed25519 -C "your_email@example.com"

# Copy public key to server
ssh-copy-id user@hostname

# Or manually:
cat ~/.ssh/id_ed25519.pub | ssh user@hostname 'cat >> ~/.ssh/authorized_keys'

# Connect (no password needed)
ssh user@hostname

# Use specific key
ssh -i ~/.ssh/custom_key user@hostname
```

**SSH config file (~/.ssh/config):**
```
Host myserver
    HostName 192.168.1.100
    User admin
    Port 2222
    IdentityFile ~/.ssh/myserver_key

Host github
    HostName github.com
    User git
    IdentityFile ~/.ssh/github_key
```

Now you can just type:
```bash
ssh myserver
```

#### Checking for Rootkits and Security Issues

```bash
# Install security tools
sudo apt install rkhunter chkrootkit

# Scan for rootkits
sudo rkhunter --check

# Check for rootkits with chkrootkit
sudo chkrootkit

# Check for failed login attempts
sudo grep "Failed password" /var/log/auth.log

# Check for sudo usage
sudo grep "sudo" /var/log/auth.log

# List all users with login shells
cat /etc/passwd | grep -v nologin | grep -v false

# Check for files with setuid bit
sudo find / -perm -4000 -type f 2>/dev/null
```

---

### Performance Tuning

#### Monitoring Performance

```bash
# Real-time system monitor
top
# Press '1' to show all CPUs
# Press 'M' to sort by memory
# Press 'P' to sort by CPU
# Press 'k' to kill a process

# Better alternative
htop

# I/O wait and CPU stats
iostat -x 1

# Memory statistics
vmstat 1

# Disk I/O by process
sudo iotop

# Network usage by process
sudo nethogs

# Overall system performance
dstat
```

#### Analyzing Disk Performance

```bash
# Test disk read speed
sudo hdparm -t /dev/sda

# Test disk cache read speed
sudo hdparm -T /dev/sda

# Detailed disk info
sudo hdparm -I /dev/sda

# I/O statistics
iostat -x 1

# Show which processes are using disk
sudo iotop -o
```

#### Memory Management

```bash
# Show memory usage
free -h

# Show detailed memory info
cat /proc/meminfo

# Clear page cache (safe, but usually unnecessary)
sudo sync && sudo sysctl -w vm.drop_caches=3

# Show swap usage
swapon --show

# Add swap file (if needed)
sudo fallocate -l 2G /swapfile
sudo chmod 600 /swapfile
sudo mkswap /swapfile
sudo swapon /swapfile

# Make swap permanent
echo '/swapfile none swap sw 0 0' | sudo tee -a /etc/fstab
```

---

### Troubleshooting Guide

#### System Won't Boot

1. Boot from live USB
2. Mount your system:
```bash
sudo mount /dev/sda1 /mnt
sudo mount --bind /dev /mnt/dev
sudo mount --bind /proc /mnt/proc
sudo mount --bind /sys /mnt/sys
sudo chroot /mnt
```
3. Fix the problem (reinstall bootloader, fix fstab, etc.)
4. Exit and reboot:
```bash
exit
sudo umount /mnt/dev /mnt/proc /mnt/sys /mnt
sudo reboot
```

#### High CPU Usage

```bash
# Find the culprit
top
# or
ps aux --sort=-%cpu | head -20

# Check what the process is doing
sudo strace -p <PID>

# Check open files
sudo lsof -p <PID>

# Kill if necessary
kill <PID>
# or force kill
kill -9 <PID>
```

#### High Memory Usage

```bash
# Check memory usage
free -h

# Find memory hogs
ps aux --sort=-%mem | head -20

# Check for memory leaks
sudo pmap <PID>

# Clear cache if needed (usually not necessary)
sudo sync && sudo sysctl -w vm.drop_caches=3
```

#### Disk Full

```bash
# Find what's using space
df -h

# Find large directories
sudo du -h / | sort -rh | head -20

# Find large files
sudo find / -type f -size +100M -exec ls -lh {} \; 2>/dev/null

# Clean package cache
sudo apt clean

# Remove old kernels
sudo apt autoremove

# Clean journal logs
sudo journalctl --vacuum-time=7d
```

#### Network Issues

```bash
# Check if interface is up
ip link show

# Check IP address
ip addr show

# Check routing
ip route show

# Test connectivity
ping -c 4 8.8.8.8

# Test DNS
nslookup google.com

# Check if service is listening
sudo ss -tulpn | grep :80

# Check firewall
sudo ufw status

# View network traffic
sudo tcpdump -i eth0
```


# Linux Command Reference

A quick reference guide for essential Linux commands and shortcuts.


## Command Line Shortcuts

### Navigation Shortcuts
```
Ctrl+A    Move to beginning of line
Ctrl+E    Move to end of line
Alt+B     Move back one word
Alt+F     Move forward one word
Ctrl+XX   Toggle between start of line and current position
```

### Editing Shortcuts
```
Ctrl+U    Delete from cursor to beginning of line
Ctrl+K    Delete from cursor to end of line
Ctrl+W    Delete word before cursor
Ctrl+Y    Paste (yank) deleted text
Alt+D     Delete word after cursor
Alt+T     Swap current word with previous word
Ctrl+T    Swap last two characters before cursor
```

### Control Shortcuts
```
Ctrl+L    Clear screen (same as 'clear' command)
Ctrl+C    Cancel/kill current command
Ctrl+Z    Suspend current command (use 'fg' to resume)
Ctrl+D    Exit shell or end input (EOF)
Ctrl+S    Stop output to screen (freeze)
Ctrl+Q    Resume output to screen
```

### History Shortcuts
```
Ctrl+R    Search command history (reverse search)
Ctrl+G    Escape from history search
Ctrl+P    Previous command (same as Up arrow)
Ctrl+N    Next command (same as Down arrow)
!!        Repeat last command
!$        Last argument of previous command
!*        All arguments of previous command
!n        Execute command number n from history
!string   Execute most recent command starting with 'string'
^old^new  Replace 'old' with 'new' in last command
```

### Completion
```
Tab       Auto-complete file/command names
Tab Tab   Show all possible completions
Alt+?     Show possible completions (same as Tab Tab)
Alt+*     Insert all possible completions
```

---

## Essential Commands

### File Operations
```bash
ls          # List files
ls -la      # List all files with details
cd dir      # Change directory
pwd         # Print working directory
mkdir dir   # Create directory
rmdir dir   # Remove empty directory
rm file     # Remove file
rm -r dir   # Remove directory recursively
cp src dst  # Copy file
mv src dst  # Move/rename file
touch file  # Create empty file or update timestamp
cat file    # Display file contents
less file   # View file with pagination
head file   # Show first 10 lines
tail file   # Show last 10 lines
tail -f     # Follow file updates in real-time
```

### File Permissions
```bash
chmod 755 file      # Change permissions (rwxr-xr-x)
chmod +x file       # Add execute permission
chown user file     # Change owner
chown user:group    # Change owner and group
chgrp group file    # Change group
```

### Search & Find
```bash
find . -name "*.txt"        # Find files by name
find . -type f -size +100M  # Find large files
grep "pattern" file         # Search in file
grep -r "pattern" dir       # Recursive search
locate filename             # Fast file search (uses database)
which command               # Show command location
whereis command             # Show binary, source, manual
```

### Text Processing
```bash
cat file                # Display file
head -n 20 file         # First 20 lines
tail -n 20 file         # Last 20 lines
wc file                 # Count lines, words, characters
wc -l file              # Count lines only
sort file               # Sort lines
uniq file               # Remove duplicate lines
cut -d: -f1 file        # Cut field 1 (delimiter :)
sed 's/old/new/g' file  # Replace text
awk '{print $1}' file   # Print first column
```

### Archives & Compression
```bash
tar -czf archive.tar.gz dir/    # Create compressed archive
tar -xzf archive.tar.gz         # Extract archive
tar -tzf archive.tar.gz         # List archive contents
zip -r archive.zip dir/         # Create zip archive
unzip archive.zip               # Extract zip
gzip file                       # Compress file
gunzip file.gz                  # Decompress file
```

### Process Management
```bash
ps aux              # Show all processes
ps aux | grep name  # Find specific process
top                 # Interactive process viewer
htop                # Better process viewer
kill PID            # Kill process by ID
kill -9 PID         # Force kill process
killall name        # Kill by process name
pkill name          # Kill by pattern
bg                  # Resume job in background
fg                  # Bring job to foreground
jobs                # List background jobs
nohup command &     # Run immune to hangups
```

### System Information
```bash
uname -a            # System information
hostname            # Show hostname
uptime              # System uptime
date                # Current date/time
cal                 # Calendar
whoami              # Current user
id                  # User ID and groups
w                   # Who is logged in
last                # Login history
df -h               # Disk space
du -sh dir          # Directory size
free -h             # Memory usage
lscpu               # CPU information
lsblk               # Block devices
```

### Network Commands
```bash
ip addr             # Show IP addresses
ip route            # Show routing table
ping host           # Test connectivity
traceroute host     # Trace route to host
nslookup domain     # DNS lookup
dig domain          # DNS lookup (detailed)
ss -tulpn           # Show listening ports
netstat -tulpn      # Show listening ports (older)
curl url            # Transfer data from URL
wget url            # Download file
ssh user@host       # Connect to remote host
scp file user@host: # Copy file to remote
```

### Package Management (Debian/Ubuntu)
```bash
sudo apt update             # Update package lists
sudo apt upgrade            # Upgrade packages
sudo apt install package    # Install package
sudo apt remove package     # Remove package
sudo apt search keyword     # Search packages
apt show package            # Show package info
```

### User Management
```bash
sudo command        # Run command as root
su - user           # Switch user
passwd              # Change password
useradd user        # Add user
userdel user        # Delete user
usermod -aG group   # Add user to group
groups              # Show groups
```

### File System
```bash
mount               # Show mounted filesystems
mount /dev/sdb1 /mnt    # Mount device
umount /mnt         # Unmount
lsblk               # List block devices
fdisk -l            # List partitions
```

### Pipes & Redirection
```bash
cmd1 | cmd2         # Pipe output to input
cmd > file          # Redirect output (overwrite)
cmd >> file         # Redirect output (append)
cmd 2> file         # Redirect errors
cmd &> file         # Redirect output and errors
cmd < file          # Input from file
cmd | tee file      # Output to screen and file
```

### Command Chaining
```bash
cmd1 ; cmd2         # Run sequentially
cmd1 && cmd2        # Run cmd2 if cmd1 succeeds
cmd1 || cmd2        # Run cmd2 if cmd1 fails
cmd &               # Run in background
```

---

## Useful Aliases

Add these to `~/.bashrc`:

```bash
# Navigation
alias ..='cd ..'
alias ...='cd ../..'
alias ....='cd ../../..'

# Listing
alias ll='ls -lah'
alias la='ls -A'
alias l='ls -CF'

# Safety
alias rm='rm -i'
alias cp='cp -i'
alias mv='mv -i'

# System
alias update='sudo apt update && sudo apt upgrade'
alias install='sudo apt install'
alias ports='sudo ss -tulpn'

# Shortcuts
alias h='history'
alias c='clear'
alias e='exit'
```

---

## Common Patterns

### Find and Execute
```bash
# Find and delete old files
find . -name "*.log" -mtime +30 -delete

# Find and change permissions
find . -name "*.sh" -exec chmod +x {} \;

# Find large files
find / -type f -size +100M -exec ls -lh {} \; 2>/dev/null
```

### Text Processing Pipelines
```bash
# Count unique lines
sort file.txt | uniq -c

# Top 10 most common lines
sort file.txt | uniq -c | sort -rn | head -10

# Extract column and count
awk '{print $1}' file.txt | sort | uniq -c

# Search and count matches
grep "error" logfile.txt | wc -l
```

### System Monitoring
```bash
# Watch disk space
watch -n 5 df -h

# Monitor log file
tail -f /var/log/syslog | grep --color error

# Top CPU processes
ps aux --sort=-%cpu | head -10

# Top memory processes
ps aux --sort=-%mem | head -10
```

### Backup & Archive
```bash
# Backup with timestamp
tar -czf backup-$(date +%Y%m%d).tar.gz /path/to/dir

# Sync directories
rsync -av --delete source/ destination/

# Remote backup
rsync -avz /local/dir user@host:/remote/dir
```

---

## Special Variables

```bash
$0      # Script name
$1-$9   # Script arguments
$@      # All arguments
$#      # Number of arguments
$?      # Exit status of last command
$$      # Current process ID
$!      # PID of last background job
$HOME   # Home directory
$USER   # Current username
$PATH   # Command search path
$PWD    # Current directory
$OLDPWD # Previous directory
```

---

## File Permissions

### Permission Numbers
```
7 = rwx (read, write, execute)
6 = rw- (read, write)
5 = r-x (read, execute)
4 = r-- (read only)
0 = --- (no permissions)
```

### Common Patterns
```
644 = rw-r--r--  # Regular file
755 = rwxr-xr-x  # Executable/directory
600 = rw-------  # Private file
700 = rwx------  # Private directory
```

---

## Quick Tips

1. **Use Tab completion** - Save time typing
2. **Use Ctrl+R** - Search command history
3. **Use `man` pages** - `man command` for help
4. **Use `--help`** - Quick command help
5. **Quote variables** - Always use `"$var"`
6. **Check exit codes** - `echo $?` after commands
7. **Use `sudo` carefully** - Understand what you're doing
8. **Backup before changes** - `cp file file.bak`
9. **Test in safe environment** - Use VMs for experiments
10. **Read error messages** - They tell you what's wrong


#### One-Liners That Save Time

```bash
# Find and replace in multiple files
find . -name "*.txt" -exec sed -i 's/old/new/g' {} \;

# Create directory and cd into it
mkdir -p new_project && cd new_project

# Backup with timestamp
cp file.txt file.txt.$(date +%Y%m%d_%H%M%S)

# Extract any archive
extract() {
    if [ -f $1 ]; then
        case $1 in
            *.tar.bz2)   tar xjf $1     ;;
            *.tar.gz)    tar xzf $1     ;;
            *.bz2)       bunzip2 $1     ;;
            *.rar)       unrar x $1     ;;
            *.gz)        gunzip $1      ;;
            *.tar)       tar xf $1      ;;
            *.tbz2)      tar xjf $1     ;;
            *.tgz)       tar xzf $1     ;;
            *.zip)       unzip $1       ;;
            *.Z)         uncompress $1  ;;
            *.7z)        7z x $1        ;;
            *)           echo "'$1' cannot be extracted" ;;
        esac
    else
        echo "'$1' is not a valid file"
    fi
}

# Quick web server in current directory
python3 -m http.server 8000

# Monitor file changes
watch -n 1 cat file.txt

# Show directory tree
tree -L 2

# Find duplicate files
fdupes -r /path/to/directory
```

---

## Additional Resources

### Official Documentation
- [Linux Documentation Project](https://tldp.org/)
- [Ubuntu Documentation](https://help.ubuntu.com/)
- [Arch Wiki](https://wiki.archlinux.org/) (excellent even if you don't use Arch)
- [GNU Coreutils Manual](https://www.gnu.org/software/coreutils/manual/)

### Learning Resources
- [Linux Journey](https://linuxjourney.com/) - Interactive tutorials
- [OverTheWire Wargames](https://overthewire.org/) - Learn through challenges
- [Explain Shell](https://explainshell.com/) - Understand any command

### Command Reference
- `man` pages - Built into your system
- [tldr pages](https://tldr.sh/) - Simplified man pages
- [cheat.sh](https://cheat.sh/) - Community cheatsheets

---

## Practice Exercises

### Beginner Exercises

1. **File Management**
   - Create a directory structure: `~/practice/docs/2025/january`
   - Create 5 text files in the january folder
   - Copy them to a backup folder
   - Rename them with a prefix "backup_"

2. **Permissions**
   - Create a script file
   - Make it executable
   - Run it
   - Change its permissions to read-only

3. **Text Processing**
   - Create a file with 10 lines of text
   - Display only lines 3-7
   - Count the number of words
   - Replace a word throughout the file

### Intermediate Exercises

1. **Scripting**
   - Write a script that backs up a directory
   - Add timestamp to backup filename
   - Check if backup was successful
   - Log the result

2. **Process Management**
   - Find the process using the most CPU
   - Find the process using the most memory
   - Start a long-running process in the background
   - Monitor it with `top` or `htop`

3. **System Administration**
   - Install a package
   - Create a systemd service for a simple script
   - Enable it to start at boot
   - Check its logs

### Advanced Exercises

1. **Automation**
   - Create a cron job that runs daily
   - Write a script that monitors disk space
   - Send an alert if space is low
   - Log all activities

2. **Networking**
   - Set up SSH key authentication
   - Configure SSH to use a non-standard port
   - Set up a simple firewall with ufw
   - Monitor network connections

3. **Performance**
   - Identify a performance bottleneck
   - Use `strace` to debug a slow program
   - Optimize a script to run faster
   - Monitor system resources over time

---

## Conclusion

Congratulations on making it through this guide! Linux is a vast ecosystem, and this guide has covered the essentials and beyond. Remember:

1. **Practice regularly** - The more you use the command line, the more natural it becomes
2. **Read man pages** - They're your best friend for understanding commands
3. **Don't be afraid to experiment** - Use a virtual machine or test system to try new things
4. **Join the community** - Forums, IRC, Discord - Linux users love to help
5. **Keep learning** - Technology evolves, and there's always something new to discover

The journey from beginner to expert is gradual. Don't try to learn everything at once. Focus on what you need, practice it until it's comfortable, then move on to the next topic.

Happy Linux-ing! 🐧

---
# Linux Quick Reference Card

## Navigation & File System

### Directory Navigation
```bash
pwd                      # Print working directory
cd /path/to/dir         # Change to absolute path
cd relative/path        # Change to relative path
cd ~                    # Go to home directory
cd -                    # Go to previous directory
cd ..                   # Go up one level
cd ../..                # Go up two levels
pushd /path             # Save current dir and change
popd                    # Return to saved directory
dirs                    # Show directory stack
```

### Listing Files
```bash
ls                      # List files
ls -l                   # Long format with details
ls -a                   # Show hidden files (starting with .)
ls -lh                  # Human-readable sizes
ls -lah                 # All files, long format, human-readable
ls -lt                  # Sort by modification time (newest first)
ls -ltr                 # Sort by time (oldest first)
ls -lS                  # Sort by size (largest first)
ls -R                   # Recursive listing
ls -d */                # List only directories
ls -i                   # Show inode numbers
tree                    # Display directory tree
tree -L 2               # Tree with max depth 2
```

### File Operations
```bash
touch file.txt          # Create empty file or update timestamp
cp file1 file2          # Copy file
cp -r dir1 dir2         # Copy directory recursively
cp -a dir1 dir2         # Copy preserving all attributes
cp -i file1 file2       # Interactive (prompt before overwrite)
cp -u file1 file2       # Copy only if source is newer
mv file1 file2          # Move or rename file
mv -i file1 file2       # Interactive move
mv *.txt dir/           # Move multiple files
rm file                 # Remove file
rm -i file              # Interactive remove
rm -r dir               # Remove directory recursively
rm -rf dir              # Force remove (dangerous!)
rmdir dir               # Remove empty directory
mkdir dir               # Create directory
mkdir -p path/to/dir    # Create parent directories as needed
mkdir -p dir/{sub1,sub2,sub3}  # Create multiple subdirs
ln -s target link       # Create symbolic link
ln target link          # Create hard link
readlink link           # Show where symlink points
```

### File Viewing
```bash
cat file                # Display entire file
cat file1 file2         # Concatenate multiple files
cat -n file             # Show line numbers
tac file                # Display file in reverse
less file               # Page through file (q to quit)
more file               # Page through file (older)
head file               # Show first 10 lines
head -n 20 file         # Show first 20 lines
tail file               # Show last 10 lines
tail -n 20 file         # Show last 20 lines
tail -f file            # Follow file updates (Ctrl+C to stop)
tail -F file            # Follow with retry (if file rotates)
wc file                 # Count lines, words, characters
wc -l file              # Count lines only
wc -w file              # Count words only
wc -c file              # Count bytes
nl file                 # Number lines
```

## File Permissions & Ownership

### Permission Commands
```bash
chmod 755 file          # rwxr-xr-x
chmod 644 file          # rw-r--r--
chmod 600 file          # rw-------
chmod +x file           # Add execute permission
chmod -w file           # Remove write permission
chmod u+x file          # Add execute for user
chmod g+w file          # Add write for group
chmod o-r file          # Remove read for others
chmod a+r file          # Add read for all
chmod -R 755 dir        # Recursive permission change
chown user file         # Change owner
chown user:group file   # Change owner and group
chown -R user:group dir # Recursive ownership change
chgrp group file        # Change group only
umask                   # Show default permission mask
umask 022               # Set default mask
```

### Permission Numbers
```bash
# Read (r) = 4, Write (w) = 2, Execute (x) = 1
# User Group Others
  7    7     7     # rwxrwxrwx (777) - all permissions
  7    5     5     # rwxr-xr-x (755) - standard executable
  7    0     0     # rwx------ (700) - private executable
  6    4     4     # rw-r--r-- (644) - standard file
  6    0     0     # rw------- (600) - private file
  4    4     4     # r--r--r-- (444) - read-only
```

### Special Permissions
```bash
chmod u+s file          # Set SUID (runs as owner)
chmod g+s dir           # Set SGID (inherit group)
chmod +t dir            # Set sticky bit (only owner can delete)
chmod 4755 file         # SUID + 755
chmod 2755 dir          # SGID + 755
chmod 1777 dir          # Sticky + 777
find / -perm -4000      # Find SUID files
find / -perm -2000      # Find SGID files
```

## Text Processing

### Searching & Filtering
```bash
grep pattern file       # Search for pattern
grep -i pattern file    # Case-insensitive search
grep -v pattern file    # Invert match (exclude pattern)
grep -r pattern dir     # Recursive search
grep -n pattern file    # Show line numbers
grep -c pattern file    # Count matches
grep -l pattern files   # Show only filenames
grep -w word file       # Match whole word
grep -A 3 pattern file  # Show 3 lines after match
grep -B 3 pattern file  # Show 3 lines before match
grep -C 3 pattern file  # Show 3 lines context
grep -E 'pat1|pat2'     # Extended regex (OR)
egrep 'pat1|pat2'       # Same as grep -E
fgrep string file       # Fixed string (no regex)
rg pattern              # Ripgrep (faster alternative)
```

### Text Manipulation
```bash
sed 's/old/new/' file   # Replace first occurrence per line
sed 's/old/new/g' file  # Replace all occurrences
sed -i 's/old/new/g' f  # Replace in-place
sed -n '10,20p' file    # Print lines 10-20
sed '5d' file           # Delete line 5
sed '/pattern/d' file   # Delete lines matching pattern
awk '{print $1}' file   # Print first column
awk '{print $1,$3}'     # Print columns 1 and 3
awk -F: '{print $1}'    # Use : as delimiter
awk '$3 > 50' file      # Print lines where col 3 > 50
cut -d: -f1 file        # Cut field 1 (delimiter :)
cut -c1-10 file         # Cut characters 1-10
sort file               # Sort lines alphabetically
sort -r file            # Reverse sort
sort -n file            # Numeric sort
sort -k2 file           # Sort by column 2
sort -u file            # Sort and remove duplicates
uniq file               # Remove adjacent duplicates
uniq -c file            # Count occurrences
uniq -d file            # Show only duplicates
tr 'a-z' 'A-Z'          # Translate lowercase to uppercase
tr -d 'chars'           # Delete characters
tr -s ' '               # Squeeze repeated spaces
paste file1 file2       # Merge files side by side
join file1 file2        # Join files on common field
diff file1 file2        # Show differences
diff -u file1 file2     # Unified diff format
comm file1 file2        # Compare sorted files
```

### Text Editors
```bash
nano file               # Simple editor (Ctrl+X to exit)
vim file                # Vi improved (:q to quit, :wq to save)
vi file                 # Classic vi editor
emacs file              # Emacs editor
```

## Finding Files

### Find Command
```bash
find . -name "*.txt"    # Find by name
find . -iname "*.txt"   # Case-insensitive name
find . -type f          # Find files only
find . -type d          # Find directories only
find . -type l          # Find symbolic links
find . -size +100M      # Files larger than 100MB
find . -size -1M        # Files smaller than 1MB
find . -empty           # Find empty files/dirs
find . -mtime -7        # Modified in last 7 days
find . -mtime +30       # Modified more than 30 days ago
find . -atime -7        # Accessed in last 7 days
find . -ctime -7        # Changed in last 7 days
find . -mmin -60        # Modified in last 60 minutes
find . -user username   # Files owned by user
find . -group groupname # Files owned by group
find . -perm 644        # Files with exact permissions
find . -perm -644       # Files with at least these perms
find . -name "*.log" -delete  # Find and delete
find . -name "*.txt" -exec cat {} \;  # Find and execute
find . -name "*.sh" -exec chmod +x {} \;  # Make scripts executable
```

### Locate Command
```bash
locate filename         # Fast file search (uses database)
locate -i filename      # Case-insensitive
locate -c filename      # Count matches
updatedb                # Update locate database
```

### Which & Whereis
```bash
which command           # Show path to command
which -a command        # Show all paths
whereis command         # Show binary, source, manual
type command            # Show command type
type -a command         # Show all definitions
command -v command      # Show command path
```

## Process Management

### Viewing Processes
```bash
ps                      # Show your processes
ps aux                  # Show all processes
ps aux | grep name      # Find specific process
ps -ef                  # Full format listing
ps -u username          # Processes by user
ps -p PID               # Show specific process
ps auxf                 # Show process tree
ps aux --sort=-%cpu     # Sort by CPU usage
ps aux --sort=-%mem     # Sort by memory usage
pstree                  # Display process tree
pgrep name              # Find process ID by name
pidof program           # Get PID of program
top                     # Interactive process viewer
htop                    # Better interactive viewer
```

### Controlling Processes
```bash
command &               # Run in background
jobs                    # List background jobs
fg                      # Bring job to foreground
fg %1                   # Bring job 1 to foreground
bg                      # Resume job in background
bg %1                   # Resume job 1 in background
Ctrl+Z                  # Suspend current process
Ctrl+C                  # Kill current process
kill PID                # Terminate process
kill -9 PID             # Force kill process
kill -TERM PID          # Graceful termination
kill -HUP PID           # Hangup (reload config)
killall name            # Kill by process name
killall -9 name         # Force kill by name
pkill name              # Kill by pattern
nice -n 10 command      # Run with low priority
renice -n 5 -p PID      # Change priority
nohup command &         # Run immune to hangups
disown %1               # Detach job from shell
```

### System Monitoring
```bash
uptime                  # System uptime and load
w                       # Who is logged in
who                     # Show logged in users
last                    # Login history
free -h                 # Memory usage
free -m                 # Memory in MB
vmstat 1                # Virtual memory stats
iostat                  # I/O statistics
iotop                   # I/O by process
mpstat                  # CPU statistics
dstat                   # Versatile resource stats
```

## Disk & Storage

### Disk Usage
```bash
df -h                   # Disk space (human-readable)
df -hT                  # Include filesystem type
df -i                   # Inode usage
du -h dir               # Directory size
du -sh dir              # Summary of directory
du -h --max-depth=1     # One level deep
du -ah | sort -rh | head -20  # Top 20 largest
ncdu                    # Interactive disk usage
```

### Mounting
```bash
mount                   # Show mounted filesystems
mount /dev/sdb1 /mnt    # Mount device
mount -t ntfs /dev/sdb1 /mnt  # Mount with type
umount /mnt             # Unmount
umount -f /mnt          # Force unmount
umount -l /mnt          # Lazy unmount
lsblk                   # List block devices
lsblk -f                # Include filesystem info
blkid                   # Show UUIDs
findmnt                 # Show mount tree
```

### Disk Operations
```bash
fdisk -l                # List partitions
parted -l               # List partitions (GPT support)
mkfs.ext4 /dev/sdb1     # Format as ext4
mkfs.ntfs /dev/sdb1     # Format as NTFS
fsck /dev/sdb1          # Check filesystem
e2fsck /dev/sdb1        # Check ext filesystem
dd if=/dev/sda of=/dev/sdb bs=4M  # Clone disk
dd if=file.iso of=/dev/sdb bs=4M status=progress  # Write ISO
sync                    # Flush filesystem buffers
```

## Archives & Compression

### Tar Archives
```bash
tar -cvf archive.tar dir/       # Create tar
tar -czvf archive.tar.gz dir/   # Create tar.gz
tar -cjvf archive.tar.bz2 dir/  # Create tar.bz2
tar -cJvf archive.tar.xz dir/   # Create tar.xz
tar -tvf archive.tar            # List contents
tar -xvf archive.tar            # Extract
tar -xzvf archive.tar.gz        # Extract tar.gz
tar -xvf archive.tar -C /dest/  # Extract to directory
tar -xvf archive.tar file.txt   # Extract specific file
tar --exclude='*.log' -czf archive.tar.gz dir/  # Exclude pattern
```

### Compression
```bash
gzip file               # Compress (creates file.gz)
gzip -d file.gz         # Decompress
gunzip file.gz          # Decompress
bzip2 file              # Compress (better ratio)
bzip2 -d file.bz2       # Decompress
bunzip2 file.bz2        # Decompress
xz file                 # Compress (best ratio)
xz -d file.xz           # Decompress
unxz file.xz            # Decompress
zip archive.zip files   # Create zip
zip -r archive.zip dir/ # Zip directory
unzip archive.zip       # Extract zip
unzip -l archive.zip    # List zip contents
7z a archive.7z files   # Create 7z archive
7z x archive.7z         # Extract 7z
```

## Networking

### Network Configuration
```bash
ip addr                 # Show IP addresses
ip a                    # Short form
ip link                 # Show network interfaces
ip route                # Show routing table
ip -s link              # Show interface statistics
ifconfig                # Show interfaces (older)
ifconfig eth0           # Show specific interface
ifconfig eth0 up        # Bring interface up
ifconfig eth0 down      # Bring interface down
```

### Network Testing
```bash
ping host               # Test connectivity
ping -c 4 host          # Ping 4 times
ping6 host              # Ping IPv6
traceroute host         # Trace route to host
tracepath host          # Trace path (no root needed)
mtr host                # Combined ping/traceroute
nslookup domain         # DNS lookup
dig domain              # DNS lookup (detailed)
dig +short domain       # Brief DNS lookup
host domain             # DNS lookup
whois domain            # Domain registration info
```

### Network Connections
```bash
ss -tulpn               # Show listening ports
ss -t                   # Show TCP connections
ss -u                   # Show UDP connections
ss -a                   # Show all sockets
netstat -tulpn          # Show listening ports (older)
netstat -an             # Show all connections
lsof -i                 # Show network connections
lsof -i :80             # Show what's using port 80
lsof -i TCP:80          # TCP connections on port 80
nc -zv host 80          # Test if port is open
telnet host 80          # Connect to port
```

### File Transfer
```bash
scp file user@host:/path/       # Copy to remote
scp user@host:/path/file .      # Copy from remote
scp -r dir user@host:/path/     # Copy directory
scp -P 2222 file user@host:     # Use specific port
rsync -av src/ dest/            # Sync directories
rsync -avz src/ user@host:dest/ # Sync to remote
rsync -av --delete src/ dest/   # Sync and delete extras
wget url                        # Download file
wget -c url                     # Continue download
wget -O file url                # Save as filename
curl url                        # Display URL content
curl -O url                     # Download file
curl -o file url                # Save as filename
curl -L url                     # Follow redirects
```

### SSH
```bash
ssh user@host           # Connect to remote host
ssh -p 2222 user@host   # Use specific port
ssh -i key user@host    # Use specific key
ssh-keygen              # Generate SSH key
ssh-keygen -t ed25519   # Generate ed25519 key
ssh-copy-id user@host   # Copy key to remote
```

## Package Management

### APT (Debian/Ubuntu/Mint)
```bash
sudo apt update         # Update package lists
sudo apt upgrade        # Upgrade packages
sudo apt full-upgrade   # Upgrade with dependency changes
sudo apt install pkg    # Install package
sudo apt install pkg1 pkg2  # Install multiple
sudo apt remove pkg     # Remove package
sudo apt purge pkg      # Remove package and config
sudo apt autoremove     # Remove unused dependencies
sudo apt clean          # Clear package cache
sudo apt autoclean      # Clear old package cache
apt search keyword      # Search for packages
apt show pkg            # Show package info
apt list --installed    # List installed packages
apt list --upgradable   # List upgradable packages
dpkg -l                 # List installed packages
dpkg -L pkg             # List files in package
dpkg -S /path/to/file   # Find package owning file
```

### DNF/YUM (Fedora/RHEL/CentOS)
```bash
sudo dnf update         # Update packages
sudo dnf install pkg    # Install package
sudo dnf remove pkg     # Remove package
sudo dnf search keyword # Search packages
dnf info pkg            # Show package info
dnf list installed      # List installed
```

### Snap
```bash
snap find pkg           # Search snaps
sudo snap install pkg   # Install snap
sudo snap remove pkg    # Remove snap
snap list               # List installed snaps
sudo snap refresh       # Update all snaps
```

## System Information

### Hardware Info
```bash
lscpu                   # CPU information
lspci                   # PCI devices
lspci -v                # Verbose PCI info
lsusb                   # USB devices
lsusb -v                # Verbose USB info
lsblk                   # Block devices
lshw                    # Hardware overview
lshw -short             # Brief hardware list
dmidecode               # DMI/SMBIOS info
hdparm -I /dev/sda      # Hard drive info
smartctl -a /dev/sda    # SMART disk info
sensors                 # Temperature sensors
```

### System Info
```bash
uname -a                # All system info
uname -r                # Kernel version
uname -m                # Machine architecture
hostname                # Show hostname
hostnamectl             # Show/set hostname
cat /etc/os-release     # Distribution info
lsb_release -a          # Distribution info
date                    # Current date/time
timedatectl             # Show/set time
cal                     # Calendar
uptime                  # System uptime
whoami                  # Current username
id                      # User ID and groups
groups                  # Show groups
```

### Kernel & Modules
```bash
lsmod                   # List loaded modules
modinfo module          # Module information
modprobe module         # Load module
modprobe -r module      # Remove module
dmesg                   # Kernel messages
dmesg | tail            # Recent kernel messages
journalctl -k           # Kernel logs
```

## User Management

### User Operations
```bash
whoami                  # Current user
id                      # User ID and groups
id username             # Info about user
groups                  # Show groups
groups username         # Show user's groups
who                     # Who is logged in
w                       # Who and what they're doing
last                    # Login history
lastlog                 # Last login per user
finger username         # User information
su - username           # Switch user
sudo -i                 # Root shell
sudo -s                 # Root shell (keep env)
sudo -u user command    # Run as user
passwd                  # Change password
passwd username         # Change user password
```

### User Administration
```bash
sudo useradd username   # Add user
sudo useradd -m username  # Add user with home dir
sudo userdel username   # Delete user
sudo userdel -r username  # Delete user and home
sudo usermod -aG group user  # Add user to group
sudo usermod -l newname old  # Rename user
sudo groupadd groupname # Create group
sudo groupdel groupname # Delete group
getent passwd           # List all users
getent group            # List all groups
```

## systemd Services

### Service Management
```bash
systemctl status service    # Check service status
systemctl start service     # Start service
systemctl stop service      # Stop service
systemctl restart service   # Restart service
systemctl reload service    # Reload config
systemctl enable service    # Enable at boot
systemctl disable service   # Disable at boot
systemctl enable --now service  # Enable and start
systemctl is-active service # Check if running
systemctl is-enabled service    # Check if enabled
systemctl list-units        # List all units
systemctl list-units --type=service  # List services
systemctl list-unit-files   # List unit files
systemctl daemon-reload     # Reload systemd config
```

### Journal Logs
```bash
journalctl                  # All logs
journalctl -u service       # Service logs
journalctl -f               # Follow logs
journalctl -u service -f    # Follow service logs
journalctl -b               # Current boot logs
journalctl -b -1            # Previous boot logs
journalctl --since today    # Today's logs
journalctl --since "1 hour ago"  # Last hour
journalctl --since "2025-01-15"  # Since date
journalctl -p err           # Error priority
journalctl -p warning       # Warning and above
journalctl -n 50            # Last 50 lines
journalctl -k               # Kernel messages
journalctl --disk-usage     # Journal disk usage
journalctl --vacuum-time=7d # Keep 7 days
journalctl --vacuum-size=1G # Keep 1GB
```

## Shell Features

### History
```bash
history                 # Show command history
history 20              # Show last 20 commands
!n                      # Execute command number n
!!                      # Repeat last command
!string                 # Repeat last command starting with string
!$                      # Last argument of previous command
!*                      # All arguments of previous command
^old^new                # Replace old with new in last command
Ctrl+R                  # Search history (interactive)
history -c              # Clear history
```

### Variables
```bash
VAR=value               # Set variable
echo $VAR               # Use variable
export VAR=value        # Set environment variable
env                     # Show environment variables
printenv                # Show environment variables
printenv VAR            # Show specific variable
unset VAR               # Remove variable
$HOME                   # Home directory
$USER                   # Username
$PATH                   # Command search path
$PWD                    # Current directory
$OLDPWD                 # Previous directory
$?                      # Exit status of last command
$$                      # Current shell PID
$!                      # PID of last background job
```

### Redirection & Pipes
```bash
command > file          # Redirect output (overwrite)
command >> file         # Redirect output (append)
command 2> file         # Redirect errors
command &> file         # Redirect output and errors
command 2>&1            # Redirect errors to output
command < file          # Input from file
command1 | command2     # Pipe output to input
command | tee file      # Output to screen and file
command > /dev/null     # Discard output
command 2> /dev/null    # Discard errors
command &> /dev/null    # Discard all output
```

### Command Chaining
```bash
cmd1 ; cmd2             # Run sequentially
cmd1 && cmd2            # Run cmd2 if cmd1 succeeds
cmd1 || cmd2            # Run cmd2 if cmd1 fails
cmd1 & cmd2             # Run cmd1 in background, then cmd2
(cmd1; cmd2)            # Run in subshell
{ cmd1; cmd2; }         # Run in current shell
```

## Shortcuts & Tips

### Terminal Shortcuts
```bash
Ctrl+A                  # Move to beginning of line
Ctrl+E                  # Move to end of line
Ctrl+U                  # Delete to beginning of line
Ctrl+K                  # Delete to end of line
Ctrl+W                  # Delete word before cursor
Ctrl+Y                  # Paste deleted text
Ctrl+L                  # Clear screen
Ctrl+C                  # Cancel current command
Ctrl+Z                  # Suspend current command
Ctrl+D                  # Exit shell / EOF
Ctrl+R                  # Search history
Ctrl+S                  # Stop output
Ctrl+Q                  # Resume output
Alt+B                   # Move back one word
Alt+F                   # Move forward one word
Tab                     # Auto-complete
Tab Tab                 # Show all completions
```

### Useful Aliases
```bash
alias ll='ls -lah'
alias la='ls -A'
alias l='ls -CF'
alias ..='cd ..'
alias ...='cd ../..'
alias grep='grep --color=auto'
alias df='df -h'
alias du='du -h'
alias free='free -h'
alias ports='ss -tulpn'
alias update='sudo apt update && sudo apt upgrade'
```

### Quick One-Liners
```bash
# Find large files
find / -type f -size +100M 2>/dev/null

# Find recently modified files
find . -type f -mtime -1

# Disk usage sorted
du -sh * | sort -rh

# Top 10 largest directories
du -h / 2>/dev/null | sort -rh | head -10

# Count files in directory
ls -1 | wc -l

# Find and kill process
ps aux | grep process | awk '{print $2}' | xargs kill

# Monitor log file
tail -f /var/log/syslog | grep --color error

# Create backup with timestamp
cp file.txt file.txt.$(date +%Y%m%d_%H%M%S)

# Extract any archive
tar -xvf archive.*

# Quick web server
python3 -m http.server 8000

# Generate random password
openssl rand -base64 32

# Check open ports
sudo lsof -i -P -n | grep LISTEN

# System resource usage
ps aux --sort=-%mem | head -10
```

## Emergency & Recovery

### System Recovery
```bash
# Boot to single user mode (add to kernel line)
single
# or
init=/bin/bash

# Remount root as read-write
mount -o remount,rw /

# Reset root password (in single user mode)
passwd root

# Check filesystem
fsck /dev/sda1

# Force fsck on next boot
touch /forcefsck
```

### Disk Space Emergency
```bash
# Find what's using space
du -sh /* | sort -rh
df -h

# Clear journal logs
journalctl --vacuum-time=1d

# Clear package cache
sudo apt clean

# Remove old kernels
sudo apt autoremove

# Find large files
find / -type f -size +100M 2>/dev/null
```

### Process Issues
```bash
# Kill all processes by user
pkill -u username

# Kill all processes by name
killall -9 processname

# Find and kill zombie processes
ps aux | grep 'Z'

# Reboot if system is frozen
echo b > /proc/sysrq-trigger
```

---

**Print this card and keep it handy!**

*Last updated: January 2026*
