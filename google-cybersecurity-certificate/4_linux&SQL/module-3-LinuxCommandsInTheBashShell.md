# 🐧 Linux Commands in the Bash Shell (Module 3)

## 📌 Security Analyst Responsibilities

Security analysts commonly use Linux commands to:

- Review and analyze server logs
- Navigate, manage, and analyze files remotely without a GUI
- Configure user and group access
- Set and verify file permissions

---

# 💻 Bash & Linux Basics

## Bash

- The default shell in many Linux distributions
- Provides a command-line interface (CLI) for interacting with the operating system

---

## Command

A **command** is an instruction given to the computer to perform a task.

- Linux commands are case-sensitive

---

## Argument

An **argument** provides extra information needed for a command to run correctly.

- Arguments are also case-sensitive

---

# 🌳 Linux File System Structure

## Filesystem Hierarchy Standard (FHS)

The **FHS** organizes files and directories in Linux.

- Structured similarly to a tree
- Everything branches from the root directory

---

## Root Directory

The **root directory** is the highest-level directory in Linux.

- Represented by `/`
- All other directories branch from it

### Example Path

```text
/home/analyst
```

### Path Breakdown

| Component | Meaning |
|---|---|
| `/` | Root directory |
| `home` | Standard directory |
| `analyst` | User directory |

---

# 📂 Navigation Commands

## `pwd`

Displays the current working directory.

### Example

```bash
pwd
```

---

## `ls`

Lists files and directories in the current location.

### Example

```bash
ls
```

---

## `cd`

Changes directories.

### Example

```bash
cd projects
```

Typing only `cd` returns the user to their home directory.

---

# 📄 Viewing File Contents

## `cat`

Displays the full contents of a file.

### Example

```bash
cat updates.txt
```

---

## `head`

Displays the beginning of a file.

- Default output: first 10 lines

### Example

```bash
head -n 5 updates.txt
```

---

## `tail`

Displays the end of a file.

- Commonly used for reviewing recent log activity

### Example

```bash
tail logs.txt
```

---

## `less`

Displays file contents one page at a time.

### Useful Controls

| Key | Action |
|---|---|
| `Spacebar` | Move forward one page |
| `b` | Move backward one page |
| `Down Arrow` | Move down one line |
| `Up Arrow` | Move up one line |
| `q` | Quit |

---

# 📁 Common Linux Directories

| Directory | Purpose |
|---|---|
| `/home` | User home directories |
| `/bin` | Executable files and binaries |
| `/etc` | System configuration files |
| `/tmp` | Temporary files |
| `/mnt` | Mounted drives and media |
| `man hier` | Information about the FHS |

---

# 🧭 File Paths

## Absolute File Path

A complete file path starting from the root directory.

### Example

```text
/home/analyst/projects
```

---

## Relative File Path

A file path based on the current directory.

### Examples

```text
../projects
./logs
```

| Symbol | Meaning |
|---|---|
| `.` | Current directory |
| `..` | Parent directory |

---

## Tilde Shortcut (`~`)

Represents the current user's home directory.

### Example

```text
~/logs
```

---

# 👤 User Commands

## `whoami`

Displays the current username.

### Example

```bash
whoami
```

---

# 🔍 Searching & Filtering

## `grep`

Searches files for specific text strings.

### Example

```bash
grep OS updates.txt
```

---

# 🔀 Piping (`|`)

The pipe operator sends the output of one command into another command.

### Example

```bash
ls /home/analyst/reports | grep users
```

This filters the `ls` results to only show entries containing `users`.

---

# 🔎 Finding Files

## `find`

Searches for files and directories matching specific criteria.

### Example

```bash
find /home/analyst/projects -iname "*log*"
```

---

## Common `find` Options

| Option | Purpose |
|---|---|
| `-name` | Case-sensitive search |
| `-iname` | Case-insensitive search |
| `-mtime` | Search by modification time (days) |
| `-mmin` | Search by modification time (minutes) |

### Example

```bash
find /home/analyst/projects -mtime -3
```

Returns files modified within the last 3 days.

---

# 🛠️ Creating & Managing Files

## `mkdir`

Creates a new directory.

### Example

```bash
mkdir projects
```

---

## `rmdir`

Deletes an empty directory.

### Example

```bash
rmdir projects
```

---

## `touch`

Creates a new file.

### Example

```bash
touch notes.txt
```

---

## `rm`

Deletes a file.

### Example

```bash
rm notes.txt
```

---

## `mv`

Moves or renames files/directories.

### Move Example

```bash
mv report.txt /home/analyst/reports/
```

### Rename Example

```bash
mv old.txt new.txt
```

---

## `cp`

Copies files or directories.

### Example

```bash
cp vulnerabilities.txt /home/analyst/projects/
```

---

# ✏️ Editing Files

## Nano Text Editor

A beginner-friendly Linux text editor.

### Open a File

```bash
nano notes.txt
```

---

## Important Nano Shortcuts

| Shortcut | Action |
|---|---|
| `CTRL + O` | Save |
| `CTRL + X` | Exit |

---

# 🔄 Redirecting Output

## `>`

Overwrites file contents.

### Example

```bash
echo "time" > permissions.txt
```

---

## `>>`

Appends content to the end of a file.

### Example

```bash
echo "last updated" >> permissions.txt
```

---

# 🔐 Linux Permissions

## Permissions

Permissions determine what actions users can perform on files or directories.

---

## Permission Types

| Permission | Meaning |
|---|---|
| `r` | Read |
| `w` | Write |
| `x` | Execute |

---

## Owner Types

| Owner | Meaning |
|---|---|
| `u` | User |
| `g` | Group |
| `o` | Other |

---

## Permission Example

```text
drwxrwxrwx
```

### Breakdown

| Section | Meaning |
|---|---|
| `d` | Directory |
| First `rwx` | User permissions |
| Second `rwx` | Group permissions |
| Third `rwx` | Other permissions |

---

## World-Writable Files

Files where all users can modify content.

- Considered a significant security risk

---

# 📋 Permission Commands

## `ls -l`

Displays file permissions.

### Example

```bash
ls -l
```

---

## Hidden Files

Files beginning with `.`

---

## `ls -a`

Displays hidden files.

---

## `ls -la`

Displays hidden files and permissions together.

---

# 🔧 Changing Permissions

## `chmod`

Changes file or directory permissions.

### Example

```bash
chmod g+w,o-r access.txt
```

### Breakdown

| Portion | Meaning |
|---|---|
| `g+w` | Add write permission to group |
| `o-r` | Remove read permission from others |

---

## Using `=`

Sets permissions exactly as specified.

### Example

```bash
chmod u=r,g=r,o=r login_sessions.txt
```

---

# 👑 Root & Elevated Privileges

## Root User

The root account has complete control over the system.

### Risks

- Common target for attackers
- Easy to make irreversible mistakes
- Difficult to track accountability

---

## `sudo`

Temporarily grants elevated privileges.

### Example

```bash
sudo useradd salesrep7
```

---

# 👥 User Management Commands

## `useradd`

Adds a new user.

### Example

```bash
sudo useradd salesrep7
```

### Group Examples

```bash
sudo useradd -g security fgarcia
sudo useradd -G finance,admin fgarcia
```

---

## `userdel`

Deletes a user.

### Example

```bash
sudo userdel -r fgarcia
```

---

## `usermod`

Modifies an existing user account.

### Examples

```bash
sudo usermod -g executive fgarcia
sudo usermod -a -G marketing fgarcia
```

---

## `chown`

Changes ownership of files/directories.

### Examples

```bash
sudo chown fgarcia access.txt
sudo chown :security access.txt
```

---

# 📚 Linux Help Commands

## `man`

Displays detailed manual pages.

### Example

```bash
man usermod
```

---

## `whatis`

Displays a short description of a command.

### Example

```bash
whatis tail
```

---

## `apropos`

Searches manual page descriptions for keywords.

### Example

```bash
apropos password
```

### More Specific Search

```bash
apropos -a change password
```

---

# 🧠 Key Takeaways

- Bash is the default shell used in many Linux systems
- Linux commands are case-sensitive
- The Linux file system follows a structured hierarchy
- Commands like `ls`, `cd`, `cat`, and `grep` are essential for navigation and analysis
- Linux permissions help control access to files and directories
- `sudo` provides temporary elevated privileges securely
- User management commands help administrators control system access
- Understanding Linux CLI tools is an essential cybersecurity skill
