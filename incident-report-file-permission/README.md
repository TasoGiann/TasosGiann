### Linux File Permissions Lab


### Objective
Demonstrate how Linux file permissions can be configured to enforce the principle of least privilege.

---

### Environment
- OS: Ubuntu Linux  
- User: Local non-root user  

---

### Steps Performed

**1. Check current file permissions**
```bash
ls -l file.txt
2. Modify permissions

chmod 640 file.txt
Permission breakdown:

Owner: read, write

Group: read

Others: no access

Security Impact
Prevents unauthorized access

Reduces risk of accidental data exposure

Enforces the principle of least privilege

Outcome
File access was successfully restricted to authorized users only.

