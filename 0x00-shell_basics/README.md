
# 0. Where Am I?

## Objective

In Linux, every process is always "located" in a specific directory. This directory is known as the **current working directory** (CWD). Knowing the absolute path of your current working directory is fundamental to navigating the filesystem and executing commands effectively.

The objective of this task is to write a Bash script that prints the **absolute path name** of the current working directory.

## Task

Write a script that prints the absolute path name of the current working directory when executed.

### Example

Given the following script execution:

```bash
$ chmod +x ./0-current_working_directory
$ ./0-current_working_directory
/root/system_engineering-devops/0x00-shell_basics
$
````

### Notes

* The absolute path starts from the root directory (`/`), and it shows the full path to the current working directory.
* Make sure to execute the script with appropriate permissions. Use `chmod +x` to make it executable.
* This task ensures you understand how to identify the absolute path of your working directory using a simple Bash command.

