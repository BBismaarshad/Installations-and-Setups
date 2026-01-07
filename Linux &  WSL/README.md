# Linux/WSL Commands

## 1️⃣ 📁 Linux Directory / Folder Commands
---

| Command             | What it does                                                      | Example               |
| ------------------- | ----------------------------------------------------------------- | --------------------- |
| `pwd`               | Shows the full path of the current directory                      | `pwd` → `/home/bisma` |
| `ls`                | Lists files and folders in the current directory                  | `ls`                  |
| `ls -l`             | Lists files/folders with details (permissions, size, owner, date) | `ls -l`               |
| `ls -a`             | Lists all files including hidden files (starting with `.`)        | `ls -a`               |
| `cd folder_name`    | Moves into a specific folder                                      | `cd Desktop`          |
| `cd ..`             | Moves one level up (parent directory)                             | `cd ..`               |
| `cd ~`              | Moves to the home directory                                       | `cd ~`                |
| `mkdir folder_name` | Creates a new folder                                              | `mkdir myFolder`      |
| `rmdir folder_name` | Deletes an empty folder                                           | `rmdir myFolder`      |
| `rm -r folder_name` | Deletes a folder along with all files inside it                   | `rm -r myFolder`      |

---

## ⚠️ Important Note

* Be **very careful** while using `rm -r` because deleted files **cannot be recovered**.
* Always double-check the folder name before running delete commands.

---

✅ This `.md` file can be used for:

* GitHub documentation
* Personal Linux notes
* Learning WSL / Ubuntu basics

---

## 2️⃣ File Commands

| Command                | What it does                                    | Example                 |
| ---------------------- | ----------------------------------------------- | ----------------------- |
| `touch file_name`      | Creates a new empty file                        | `touch app.js`          |
| `nano file_name`       | Edits a file in the terminal using Nano editor  | `nano app.js`           |
| `cat file_name`        | Displays the content of a file in the terminal  | `cat app.js`            |
| `cp file1 file2`       | Copies a file from one name/location to another | `cp app.js app-copy.js` |
| `mv old_name new_name` | Renames or moves a file                         | `mv app.js app_new.js`  |
| `rm file_name`         | Deletes a file                                  | `rm app.js`             |

---

## ⚠️ Important Notes

* `rm` permanently deletes files. There is **no undo**.
* While using `nano`, press:

  * `CTRL + O` → Save
  * `CTRL + X` → Exit

---

✅ You can keep adding more sections like:

* Permissions (`chmod`, `chown`)
* Git commands
* WSL + Ubuntu setup

---

## 3️⃣ Permissions / Ownership Commands

| Command                 | What it does                         | Example                      |
| ----------------------- | ------------------------------------ | ---------------------------- |
| `chmod 755 file`        | Changes file permissions             | `chmod 755 script.sh`        |
| `chown user:group file` | Changes file owner and group         | `chown bisma:bisma file.txt` |
| `ls -l`                 | Checks permissions, owner, and group | `ls -l`                      |

---

## 4️⃣ System / Information Commands

| Command    | What it does                                    | Example            |
| ---------- | ----------------------------------------------- | ------------------ |
| `whoami`   | Shows current logged-in user                    | `whoami` → `bisma` |
| `uname -a` | Shows complete system information               | `uname -a`         |
| `df -h`    | Shows disk space usage in human-readable format | `df -h`            |
| `top`      | Displays running processes and system usage     | `top`              |
| `free -h`  | Shows RAM and swap memory usage                 | `free -h`          |

---

## 5️⃣ Searching / Finding Commands

| Command                   | What it does                                            | Example                 |
| ------------------------- | ------------------------------------------------------- | ----------------------- |
| `find . -name "file.txt"` | Searches for a file in current directory and subfolders | `find . -name "app.js"` |
| `grep "text" file`        | Searches for text inside a file                         | `grep "hello" app.js`   |

---

## 6️⃣ Windows / WSL Specific Commands

| Command            | What it does                             | Example                         |
| ------------------ | ---------------------------------------- | ------------------------------- |
| `explorer.exe .`   | Opens current folder in Windows Explorer | `explorer.exe .`                |
| `/mnt/c/Users/...` | Access Windows folders from WSL          | `cd /mnt/c/Users/bisma/Desktop` |

---

## 7️⃣ Misc / Handy Commands

| Command       | What it does                       | Example        |
| ------------- | ---------------------------------- | -------------- |
| `clear`       | Clears the terminal screen         | `clear`        |
| `history`     | Shows previously executed commands | `history`      |
| `echo "text"` | Prints text in the terminal        | `echo "Hello"` |
| `exit`        | Closes terminal or logs out        | `exit`         |

---

## 💡 Tips for Beginners (Linux / WSL)

* Folder and file names are **case-sensitive** (`App.js` ≠ `app.js`).
* Linux uses **forward slash `/`**, not Windows backslash `\`.
* Use the **Tab key** for auto-completion of commands and file names.

---
