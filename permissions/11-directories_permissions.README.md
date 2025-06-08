# 11-directories_permissions

This script adds execute permission (`+x`) to all **subdirectories** in the current directory for the **owner**, **group**, and **others**.

## Example

Before running the script:

drwx------ 2 julien julien 4096 ...
drwx------ 2 julien julien 4096 ...
-rw-rw-r-- 1 julien julien   23 ...

After running the script:

drwx--x--x 2 julien julien 4096 ...
drwx--x--x 2 julien julien 4096 ...
-rw-rw-r-- 1 julien julien   23 ...


Only directories are affected; regular files remain unchanged.

~                                    
