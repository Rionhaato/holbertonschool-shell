11-directories_permissions

This script finds all directories in the current working directory and adds **execute permission** for the **owner**, **group**, and **others**.
Regular files are not affected.

---

## How it works

It uses the `find` command to target only directories:

```bash
find . -type d -exec chmod a+x {} \;
~                                    
