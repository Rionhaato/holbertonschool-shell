# Permissions Project

This directory contains scripts related to Linux file permissions.

## Files

- `0-iam_betty`: Switches the user to `betty`
- `1-who_am_i`: Prints the effective user ID
- `15-symbolic_link_permissions`: Changes the owner and group of the symbolic link `_hello` to `vincent` and `staff`, without affecting the target file. It uses the `-h` flag with `chown` to affect only the symlink.
