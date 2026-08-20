# Lab 02 — Linux Filesystem Navigation

## 🎯 Objective

The objective of this lab was to practice navigating the Linux filesystem using basic terminal commands.

---

## 🧰 Environment

- **Operating System:** Kali Linux
- **Environment:** Personal learning lab
- **Focus:** Linux filesystem navigation

---

## 🧪 Commands Practiced

### 1. `ls`

```bash

ls
Purpose:
Lists files and directories in the current working directory.

Result:
The command displayed the contents of the home directory, including directories such as Documents, Downloads, Desktop, Pictures, and Videos.

cd Documents
Purpose:
Changes the current working directory to Documents.

Result:
Successfully entered the Documents directory.
ls
Purpose:
Displays the contents of the current directory.

Result:
The contents of the Documents directory were displayed.
cd ..
Purpose:
Moves to the parent directory.

Result:
Successfully returned from Documents to the home directory.
pwd
Purpose:
Displays the current working directory.

Result:
Confirmed the current location after returning to the home directory.

Personal username information has been omitted from this public documentation.
cd Downloads
Purpose:
Changes the current working directory to Downloads.

Result:
Successfully entered the Downloads directory.
pwd
Purpose:
Confirms the current working directory.

Result:
Confirmed that the terminal was operating inside the Downloads directory.
cd ..
Purpose:
Moves one level up to the parent directory.

Result:
Successfully returned from Downloads to the home directory.

🔐 Security Relevance

Filesystem navigation is an important Linux skill for cybersecurity professionals.

It is useful when:

Investigating files and directories
Locating configuration files
Reviewing logs
Examining suspicious files
Working with scripts
Navigating Linux servers
Managing cloud-based Linux systems

Understanding the filesystem also provides a foundation for later topics such as permissions, processes, logs, SSH, and security investigations.

The following screenshot shows the filesystem navigation commands practiced during this lab.

![Lab 02 - Linux Filesystem Navigation](../screenshots/lab-02-filesystem-navigation.png)

🧠 What I Learned

This lab helped me understand how Linux directories are structured and how to move between them using the terminal.

The key commands were:

ls
↓
View directory contents


cd directory
↓
Enter a directory


cd ..
↓
Move to the parent directory


pwd
↓
Confirm current location

These commands are fundamental for working effectively with Linux systems and will support future cybersecurity and cloud security exercises.

✅ Lab Status

Completed

Key Takeaway

Knowing where you are in a Linux filesystem is a basic but essential skill for cybersecurity work.



### Commit message


Use:


```text
Add Lab 02 filesystem navigation
