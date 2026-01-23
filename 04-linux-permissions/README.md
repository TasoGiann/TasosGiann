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

Explanation of Commands

ls -l
Displays file permissions, ownership, and metadata.

chmod 640 file.txt
Sets the following permissions:

Owner: read and write

Group: read

Others: no access

chown user:user file.txt
Changes the owner and group of the file to the specified user.

Security Perspective

Improper file permissions can allow:

Unauthorized access to sensitive files

Accidental modification or deletion of data

Privilege escalation opportunities

Applying the principle of least privilege helps reduce these risks by granting only the minimum permissions required.

Outcome

After applying the correct permissions:

Access to the file is restricted

Only authorized users can modify the file

System security is improved

Conclusion

Understanding and managing Linux file permissions is a fundamental skill in cybersecurity.
This project demonstrates how basic permission controls contribute to system hardening and access control.

---
