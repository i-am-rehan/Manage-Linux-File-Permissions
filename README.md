# 🔐 Manage Linux File Permissions

## 📝 Project Overview

In this project, I conducted a permissions audit and applied secure configurations to files and directories in a shared Linux environment. This task simulates real-world responsibilities of a cybersecurity professional ensuring that only appropriate users have access to sensitive assets. Key commands like `ls -la` and `chmod` were used to inspect and update permissions in alignment with the organization's access control policies.

---

## ⚙️ Skills Demonstrated

- Interpreting file permission strings in Linux (e.g., `-rw-r--r--`)
- Modifying file and directory permissions using `chmod`
- Managing hidden files and secure folders
- Enforcing the principle of least privilege
- Working with real Linux command-line tools

---

## 📁 Tasks Completed

- 🔍 Inspected file and directory permissions using `ls -la`, including hidden files
- 🛡️ Removed group and other write access where not permitted
- 🗂️ Applied read-only access to the hidden file `.project_x.txt` for user and group
- 🔒 Restricted `drafts/` directory access to owner only using precise `chmod` settings

---

## 🧪 Example Commands Used

```bash
ls -la
chmod g-w,o-w project_t.txt
chmod u=r,g=r,o= .project_x.txt
chmod u=rwx,g=,o= drafts
```

---

## 📄 Documentation

- [✔️ Final Project Report](https://docs.google.com/document/d/1ewon9CFn6aUjInVRI2XKHJ1xMD2pbG06Su4j7LBrKMU/edit?usp=sharing) – Full documentation of the permissions audit and changes  
- [📂 Current File Permissions](https://docs.google.com/document/d/19yWs_jiX5N2nlXmkal4Q6ZCBks1D_hvwmrpe8nAe21A/edit?usp=sharing) – Baseline audit report before changes were applied


