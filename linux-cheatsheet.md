# 🐧 Linux Commands Cheat Sheet

> A concise reference for essential Linux/Unix commands. Useful for beginners and as a quick refresher for power users.

---

## 📁 File and Directory Management

| Command | Description |
|--------|-------------|
| `ls` | List files in current directory |
| `ls -l` | Long listing with permissions |
| `ls -a` | Show hidden files |
| `cd dir/` | Change directory |
| `pwd` | Print working directory |
| `mkdir dir` | Create a new directory |
| `rm file` | Delete a file |
| `rm -r dir/` | Recursively delete a directory |
| `cp file1 file2` | Copy file |
| `mv old new` | Rename or move file |
| `touch file` | Create an empty file |

---

## 📄 Viewing and Editing Files

| Command | Description |
|--------|-------------|
| `cat file` | Show file content |
| `less file` | Scroll through file content |
| `head file` | First 10 lines of file |
| `tail file` | Last 10 lines of file |
| `nano file` | Edit file with Nano |
| `vim file` | Edit file with Vim |
| `wc -l file` | Count lines in file |

---

## 🔍 Searching

| Command | Description |
|--------|-------------|
| `find /path -name "file"` | Find file by name |
| `grep "text" file` | Search for text in file |
| `grep -r "text" dir/` | Recursively search text |
| `locate file` | Quickly find file path |
| `which command` | Show path of a command |

---

## 📦 Package Management

### Debian/Ubuntu (APT)
| Command | Description |
|--------|-------------|
| `sudo apt update` | Refresh package index |
| `sudo apt upgrade` | Upgrade all packages |
| `sudo apt install pkg` | Install package |
| `sudo apt remove pkg` | Remove package |

---

## 🔧 System Monitoring

| Command | Description |
|--------|-------------|
| `top` / `htop` | Live process monitor |
| `ps aux` | Detailed process list |
| `df -h` | Disk usage |
| `du -sh *` | Folder size summary |
| `free -h` | RAM usage |

---

## 👤 User Management

| Command | Description |
|--------|-------------|
| `whoami` | Current user |
| `id` | User ID info |
| `adduser user` | Add new user |
| `passwd user` | Set user password |
| `su user` | Switch user |
| `sudo command` | Run as root |

---

## 🌐 Networking

| Command | Description |
|--------|-------------|
| `ip a` | Show IP address |
| `ping domain` | Test network connectivity |
| `curl url` | Fetch web content |
| `wget url` | Download file |
| `netstat -tulpn` | Listening ports |
| `ss -tuln` | Faster netstat alternative |

---

## 🔥 Permissions

| Command | Description |
|--------|-------------|
| `chmod +x file` | Make file executable |
| `chmod 755 file` | Change permission to rwxr-xr-x |
| `chown user:group file` | Change ownership |
| `ls -l` | Check permissions |

---

## 🧪 Miscellaneous

| Command | Description |
|--------|-------------|
| `man command` | Manual for command |
| `alias ll='ls -la'` | Create command alias |
| `history` | Show command history |
| `!!` | Repeat last command |
| `clear` | Clear terminal |
| `reboot` | Reboot system |
| `shutdown now` | Shutdown immediately |

---

## 🔐 Bonus: Permission Numbers

| Value | Meaning |
|-------|--------|
| `7` | read + write + execute (rwx) |
| `6` | read + write (rw-) |
| `5` | read + execute (r-x) |
| `4` | read only (r--) |
| `0` | no permissions (---) |

---

**📎 Tip:** Use `man <command>` anytime you're unsure. For example: `man find`.

---

**🧠 Maintained by [@RhyzInit](https://github.com/RhyzInit)**  
**📁 Part of the [cheatsheets](https://github.com/RhyzInit/cheatsheets) repo**
