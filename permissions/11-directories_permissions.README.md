# 11-directories_permissions

This script adds execute permission to all subdirectories of the current directory.

- It loops through each item in the current directory.
- It uses `[ -d "$entry" ]` to check if the item is a directory.
- `chmod a+X` is used to add execute permission only to directories (and not files).
- Regular files are not affected.

This ensures directories are accessible (can be entered with `cd`) without changing files unintentionally.

