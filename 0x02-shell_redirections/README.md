You will learn how to:
- Redirect standard input, output, and error streams.
- Chain commands using pipes.
- Filter content with commands like `grep`, `cut`, `sort`, `uniq`, and more.
- Use commands like `head`, `tail`, and `wc`.
- Manage files using redirection and filtering.

---

## Requirements

- All scripts are written for Ubuntu 20.04 LTS.
- All scripts use the `/bin/bash` shell.
- Scripts must be executable (`chmod +x filename`).
- No use of `&&`, `||`, or `;` unless specifically instructed.

---

## Files

| Filename | Description |
|----------|-------------|
| `0-hello_world` | Prints "Hello, World", followed by a new line to the standard output |
| `1-confused_smiley` | Displays a confused smiley `"(Ôo)'` |
| `2-hellofile` | Displays the content of `/etc/passwd` |
| `3-twofiles` | Displays the content of `/etc/passwd` and `/etc/hosts` |
| `4-lastlines` | Displays the last 10 lines of `/etc/passwd` |
| `5-firstlines` | Displays the first 10 lines of `/etc/passwd` |
| `6-third_line` | Displays the third line of the file `iacta` |
| `7-file` | Creates a file named `\*\'"Best School"\'\*$?****\*\*:)` |
| `8-cwd_state` | Writes the result of `ls -la` into a file named `ls_cwd_content` |
| `9-duplicate_last_line` | Duplicates the last line of the file `iacta` |
| `10-no_more_js` | Deletes all regular files with a `.js` extension in the current directory and subfolders |
| `11-directories` | Counts the number of directories and sub-directories in the current directory |
| `12-newest_files` | Displays the 10 newest files in the current directory |
| `13-unique` | Takes a list of words and prints only words that appear once |
| `14-findthatword` | Displays lines containing the pattern "root" from the file `/etc/passwd` |
| `15-countthatword` | Displays the number of lines that contain the pattern "bin" in `/etc/passwd` |
| `16-whatsnext` | Displays lines containing the pattern "root" and 3 lines after them in the file `/etc/passwd` |
| `17-hidethisword` | Displays all lines in `/etc/passwd` that do not contain the pattern "bin" |
| `18-letteronly` | Displays all lines of a file starting with a letter |
| `19-AZ` | Replaces all characters `A` and `c` from input to `Z` and `e` respectively |
| `20-hiago` | Removes all letters `c` and `C` from input |
| `21-reverse` | Reverses its input |
| `22-users_and_homes` | Displays all users and their home directories from `/etc/passwd` |

---

