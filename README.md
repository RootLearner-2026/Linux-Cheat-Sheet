# 🐧 My Linux Cheat Sheet

Welcome! This is a collection of essential commands and security notes documented by **RootLearner2026**. This guide is designed to help beginners master the terminal and secure their systems.

---

## 🛡️ Security & Permissions
| Command | Purpose |
| :--- | :--- |
| `sudo [command]` | Run a command with administrative (root) privileges. |
| `passwd` | Change your current user password. |
| `chmod 600 [file]` | Restrict a file so only you (the owner) can read/write it. |
| `chown [user]:[group] [file]` | Change the owner of a specific file or folder. |
| `ssh-keygen` | Generate secure keys for password-less, encrypted login. |

## 👥 Multi-User Management
| Command | Purpose |
| :--- | :--- |
| `whoami` | Displays the username you are currently logged in as. |
| `sudo useradd -m [name]` | Create a new user account with a home directory. |
| `sudo deluser [name]` | Safely remove a user from the system. |
| `groups [name]` | List which groups a user belongs to (e.g., sudo, admin). |
| `last` | Show a history of who has logged into the system. |

## 📁 File & System Navigation
| Command | Purpose |
| :--- | :--- |
| `pwd` | "Print Working Directory" — shows exactly where you are. |
| `ls -la` | List all files, including hidden ones (like .bashrc). |
| `cd [folder]` | Change your current directory. |
| `mkdir [name]` | Create a new folder. |
| `rm -i [file]` | Remove a file (with a prompt to prevent accidents). |

## 🌐 Network & Connectivity
| Command | Purpose |
| :--- | :--- |
| `ip addr` | Show your local IP address and network interfaces. |
| `ping [website.com]` | Test the connection to a remote server. |
| `curl -I [url]` | Fetch the header of a website to check its status. |
| `ssh [user]@[ip]` | Securely connect to a remote Linux machine. |

## 📝 Reading & Searching Files
| Command | Purpose |
| :--- | :--- |
| `cat [file]` | Display the entire content of a file. |
| `grep "[text]" [file]` | Search for a specific word or pattern inside a file. |
| `tail -f [file]` | Follow a file in real-time (perfect for watching security logs). |
| `nano [file]` | A beginner-friendly text editor for the terminal. |

## 🔄 The REPL & Advanced Tools
- **Python REPL:** Type `python3` to enter an interactive math/logic environment.
- **Node REPL:** Type `node` to test JavaScript code instantly.
- **The Pipe (`|`):** Use this to send the output of one command to another. 
  - *Example:* `history | grep "sudo"` (Finds every time you used sudo).

---
### 🎯 Learning Progress for 2026
- [x] Master basic navigation
- [x] Understand multi-user permissions
- [x] Learn Shell Scripting (.sh files)
- [x] Understand the difference between Virtual and Bare Metal (Physical) environments.
- [x] Practice "Log Analysis" by importing text files into a Spreadsheet.
- [x] Understand how Pivot Tables help identify security anomalies.
- [x] Learn the difference between a "Vulnerability" and a "Threat" 
- [x] Set up a firewall (UFW)

> "The root of all knowledge begins with a single command."
