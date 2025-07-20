
# Processes and Signals

This project explores process management and signal handling in Linux systems through a series of Bash scripts.

## Scripts

### 1-list_your_processes
Displays a comprehensive list of all running processes with hierarchy.

**Usage:**
```bash
./1-list_your_processes
```

**Features:**
- Shows processes from all users
- Includes processes without a controlling terminal
- Displays process hierarchy with indentation
- Shows detailed process information (USER, PID, CPU%, MEM%, VSZ, RSS, TTY, STAT, STARTED, TIME, COMMAND)

### 4-to_infinity_and_beyond
Creates an infinite loop that prints "To infinity and beyond" every 2 seconds.

**Usage:**
```bash
./4-to_infinity_and_beyond
```

### 5-dont_stop_me_now
Stops the 4-to_infinity_and_beyond process.

**Usage:**
```bash
./5-dont_stop_me_now
```

### 6-stop_me_if_you_can
Stops the 4-to_infinity_and_beyond process.

**Usage:**
```bash
./6-stop_me_if_you_can
```

### 7-highlander
Creates an infinite loop that handles SIGTERM signals gracefully.

**Usage:**
```bash
./7-highlander
```

**Features:**
- Prints "To infinity and beyond" every 2 seconds
- When receiving SIGTERM, prints "I am invincible!!!" but continues running
- Demonstrates custom signal handling

### 67-stop_me_if_you_can
Sends SIGTERM to the 7-highlander process.

**Usage:**
```bash
./67-stop_me_if_you_can
```

## Key Concepts

- **Process Management:** Understanding how processes work in Linux
- **Signals:** Handling different signals sent to processes
- **Process Hierarchy:** Viewing parent-child process relationships
- **Infinite Loops:** Creating and managing never-ending processes
- **Signal Trapping:** Customizing how processes respond to signals

## Requirements

All scripts:
- Must be executable (`chmod +x <filename>`)
- Must pass Shellcheck verification
- Must start with `#!/usr/bin/env bash`
- Must include descriptive comments

## Testing

To test the signal handling functionality:
1. In Terminal 1: `./7-highlander`
2. In Terminal 2: `./67-stop_me_if_you_can`
3. Observe "I am invincible!!!" messages in Terminal 1

## Author
[Your Name]

## License
This project is licensed under the MIT License.
```

This README:
1. Provides clear documentation for each script
2. Includes usage examples
3. Explains key concepts covered
4. Lists requirements
5. Includes testing instructions
6. Has sections for author and license
