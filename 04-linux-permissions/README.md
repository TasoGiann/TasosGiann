## 🐧 Linux File Permissions & Ownership

### 📌 Description
Hands-on practice with Linux file permissions and ownership to understand how access control works at the operating system level.

---

### 🖥️ Environment
- OS: Ubuntu Linux  
- Shell: Bash  
- User: Local user account  

---

### ⚙️ Commands Used

```bash
touch file.txt
ls -l file.txt
chmod 640 file.txt
chown user:user file.txt
🔍 Permission Breakdown
After applying:

bash
Copy code
chmod 640 file.txt
Owner: read, write

Group: read

Others: no access

This configuration follows the principle of least privilege.

🔐 Security Impact
Prevents unauthorized access to files

Reduces risk of accidental modification

Helps avoid privilege misconfigurations

✅ Result
File access restricted to authorized users

Improved system security posture
