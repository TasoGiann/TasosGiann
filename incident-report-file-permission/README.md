# Linux File Permissions Lab

## Objective
Demonstrate how Linux file permissions can be configured to enforce the principle of least privilege and reduce unauthorized access to files.

---

## Environment
Operating System: Ubuntu Linux  
User Account: Local non-root user  

---

## Procedure

### Step 1 – Review Current File Permissions
The existing permissions of the file were reviewed to assess the current access level.

```bash
ls -l file.txt
The output showed that the file had broader access permissions than required.

Step 2 – Modify File Permissions
The file permissions were updated to restrict access while maintaining usability for authorized users.

chmod 640 file.txt
Permission breakdown:

Owner: read, write
Group: read
Others: no access

Step 3 – Verify Updated Permissions
The permissions were reviewed again to confirm that the changes were successfully applied.

ls -l file.txt
Security Impact
Prevents unauthorized access to sensitive files.
Reduces the risk of accidental data exposure.
Enforces the principle of least privilege.

Outcome
File access was successfully restricted to authorized users only, improving the overall security posture of the system.

Skills Demonstrated
Linux file permission management
Use of command-line tools for access control
Application of security best practices
Entry-level system administration troubleshooting
