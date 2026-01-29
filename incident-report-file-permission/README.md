# Incident Report – File Access Issue (Linux)

## Overview
This incident report documents the investigation and resolution of a file access issue on a Linux system.  
The issue was caused by misconfigured file permissions, resulting in a **“Permission denied”** error for the user.

This scenario reflects a common **Junior IT Support** task involving access troubleshooting and permission management.

---

## Incident Information

- **Incident ID:** IR-001  
- **Date:** 29 January 2026  
- **Reported By:** End User  
- **System:** Ubuntu Linux  
- **User Type:** Standard (non-root)

---

## Incident Description
The user reported being unable to access a required text file used for daily work tasks.  
When attempting to open the file, the system returned a **Permission denied** error.

---

## Initial Assessment
Based on the error message, a file permission issue was suspected rather than file corruption or application failure.

---

## Investigation Steps

1. Checked the file permissions:
   ```bash
   ls -l file.txt
Identified that the file permissions restricted access for the user.

Confirmed that the user required read access to the file to perform job-related tasks.

Root Cause
The file permissions were misconfigured, preventing authorized access.
This resulted in reduced usability while attempting to enforce security controls.

Resolution
Updated the file permissions to allow appropriate access:

chmod 640 file.txt
Verified the updated permissions:

ls -l file.txt
Confirmed that the user could successfully access the file.

Security Considerations
Access was granted following the principle of least privilege

Unauthorized users retained no access

Risk of accidental data exposure was minimized

Outcome
The incident was resolved successfully.
Normal file access was restored, and no data loss or security breach occurred.

Lessons Learned
Incorrect permissions can significantly impact user productivity

Proper permission management balances usability and security

Documented incident handling improves response efficiency in future cases

Skills Demonstrated
Linux file permission management

Incident investigation and documentation

Troubleshooting access-related issues

Security best practices (least privilege)
