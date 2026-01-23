## Linux File Permissions & Ownership

### What I did
In this project, I practiced managing file permissions and ownership on a Linux system.
The goal was to understand how Linux controls access to files and how permissions affect security.

---

### Environment
- Operating System: Ubuntu Linux
- Terminal: Bash
- User account: Local user

---

### Steps Performed

1. Created a test file
```bash
touch file.txt
Checked file permissions

bash
Copy code
ls -l file.txt
Changed file permissions

bash
Copy code
chmod 640 file.txt
Changed file ownership

bash
Copy code
chown user:user file.txt
Permission Explanation
After running:

bash
Copy code
chmod 640 file.txt
The permissions mean:

Owner: read and write

Group: read

Others: no access

This follows the principle of least privilege, allowing only necessary access.

Security Relevance
Incorrect file permissions can lead to:

Unauthorized access to sensitive files

Accidental data modification

Security misconfigurations

By setting proper permissions, access to the file is restricted to authorized users only.

Outcome
File access is limited to the intended user

Unauthorized users cannot read or modify the file

System security is improved

Conclusion
This project demonstrates basic Linux permission management, which is an essential skill for cybersecurity and system security roles.

