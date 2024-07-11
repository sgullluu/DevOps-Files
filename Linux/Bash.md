
Linux Commands and Concepts

LS Commands

- ls / - List the contents of the root directory
- ls -a - List all files, including hidden files
- ls -l - List files with detailed information, including permissions
- ls -t - List files sorted by modification time
- ls -h - List files with human-readable file sizes (MB, KB, GB)
- ls -F - Mark executable files with * and list directories with / at the end
- ls -1 - List one file per line
- ls -S - Sort files by size

Memory and Cache Commands

- sync; echo 1 > /proc/sys/vm/drop_caches - Clear cache memory

User Management Commands

- adduser <username> - Create a new user
- passwd <username> - Set the password for the new user
- su - <username> - Switch to the new user account

Package Management Commands

- rpm -ivh <package_url> - Install a package from a URL

Make Utility

- make - Automatically determine and recompile program pieces

Virtualization Command

- yum install tree virtualization - Install virtualization software

System Information Commands

- sudo cat /etc/centos-release - Display the CentOS release version
- sudo cat /proc/meminfo | grep Mem - Display memory information
- sudo cat /proc/cpuinfo | grep cpu - Display CPU information

Special Permissions

- SUID (Set User ID): allows a user to execute a file with the permissions of the file's owner
- SGID (Set Group ID): allows a group to execute a file with the permissions of the file's group
- Sticky Bit: prevents a file from being deleted or renamed by a user who doesn't own it

Links

- Hard Link: a reference to a file on disk, similar to a Windows shortcut
- Soft Link (Symbolic Link): a reference to a file or directory that can be resolved at runtime

Inode

- A unique identifier for a file or directory on a Linux file system
- Stores metadata, such as ownership, permissions, and timestamps

I hope this helps! Let me know if you need anything else.
