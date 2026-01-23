## Linux File Permissions & Ownership

### Overview
This project demonstrates the use of Linux file permissions and ownership to control access to files and directories.

The goal is to understand how access control works in Linux systems and how improper permissions can lead to security issues.

---

### Environment
- Operating System: Ubuntu Linux
- User type: Local user
- Terminal access

---

### Permission Model
Linux permissions are divided into three categories:
- **Owner**
- **Group**
- **Others**

Each category can have the following permissions:
- **Read (r)**
- **Write (w)**
- **Execute (x)**

---

### Commands Used

```bash
ls -l
chmod 640 file.txt
chown user:user file.txt
