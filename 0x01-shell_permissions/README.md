## Overview

In this project, you will learn about:

- File permissions (read, write, execute).
- Changing file permissions using `chmod`.
- Changing file ownership and group ownership using `chown`.
- Understanding symbolic and numeric modes for setting permissions.
- Managing user groups with `chgrp`.

By the end of this project, you should be comfortable with Linux file permissions and how to apply them correctly in different scenarios.

## Directory Structure

- `0x01-shell_permissions/`: Contains exercises focused on shell permissions.
  - **Files and exercises** in this directory:
    - `README.md`: This file.
    - Shell scripts for various tasks to manage file permissions.

## Tasks

This directory covers the following tasks:

1. **Permissions Basics**
   - Set file permissions for a user, group, and others.
   - Learn how to read and interpret permission strings like `rwxr-xr-x`.

2. **Changing Permissions**
   - Use `chmod` to change the permissions of files and directories.
   - Explore both symbolic and numeric representations of file permissions.

3. **Changing Ownership**
   - Use `chown` to change the owner of a file or directory.
   - Use `chgrp` to change the group ownership of a file.

4. **Set UID, GID, and Sticky Bit**
   - Understand the `setuid`, `setgid`, and sticky bits and how they affect file behavior.

## Key Concepts

- **File Permissions**: Each file or directory in Linux has three types of permissions:
  - **r (read)**: Allows reading the contents of a file or listing the contents of a directory.
  - **w (write)**: Allows modifying the contents of a file or adding/removing files in a directory.
  - **x (execute)**: Allows running a file as a program or entering a directory.

- **Owner, Group, Others**: Each file has three categories of permissions:
  - **Owner**: The user who owns the file.
  - **Group**: The group that owns the file.
  - **Others**: All other users on the system.

- **`chmod`**: Change file mode (permissions) for a file.
  - **Symbolic mode**: `chmod u+x filename`
  - **Numeric mode**: `chmod 755 filename`

- **`chown`**: Change file owner and group.
  - Example: `chown user:group filename`

- **`chgrp`**: Change the group ownership of a file.
  - Example: `chgrp group filename`

## Requirements

- This project is designed to be completed on a Linux-based system or a virtual machine that simulates a Linux environment.
- You must be familiar with basic terminal commands such as `ls`, `chmod`, `chown`, `chgrp`, and `touch`.

## How to Use

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/<username>/system_engineering-devops.git
````

2. Navigate to the `0x01-shell_permissions` directory:

   ```bash
   cd system_engineering-devops/0x01-shell_permissions
   ```

3. Follow the tasks in the directory by executing the respective shell scripts. For example:

   ```bash
   chmod +x <task_filename>
   ./<task_filename>
   ```

## Contributions

Feel free to contribute to the repository by submitting pull requests. Ensure that your code adheres to the project guidelines and that all tests pass.

## License

This project is open-source and available under the MIT License.

