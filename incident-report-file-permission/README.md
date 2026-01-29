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

The output indicated that the file had broader access permissions than required, allowing unnecessary access beyond authorized users.

Step 2 – Modify File Permissions

The file permissions were updated to restrict access while maintaining usability for authorized users.

chmod 640 file.txt


Permission configuration after the change:

Owner access: read, write
Group access: read
Other users: no access
