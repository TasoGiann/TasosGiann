# Linux File Permissions Lab

## Objective
Demonstrate how Linux file permissions can be configured to enforce the principle of least privilege and reduce unauthorized access to files.

---

## Environment
Operating System: Ubuntu Linux  
User Account: Local non-root user  

---

## Procedure

Step 1 – Review Current File Permissions

The existing permissions of the file were reviewed to assess the current access level.

ls -l file.txt


The output showed that the file had broader access permissions than required, allowing unnecessary access beyond authorized users.

Step 2 – Modify File Permissions

The file permissions were updated to restrict access while maintaining usability for authorized users.

chmod 640 file.txt


After applying the change, the permission configuration was as follows:

Owner access: read, write
Group access: read
Other users: no access

Step 3 – Verify Updated Permissions

The file permissions were reviewed again to confirm that the changes were successfully applied.

ls -l file.txt

Security Impact

The updated configuration prevents unauthorized access to sensitive files.
It reduces the risk of accidental data exposure.
It enforces the principle of least privilege.

Outcome

File access was successfully restricted to authorized users only, improving the overall security posture of the system.

Skills Demonstrated

Linux file permission management
Command-line access control
Application of security best practices
Entry-level system administration troubleshooting
