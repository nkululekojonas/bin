# Shell Utilities

Welcome to my bin, a collection of Bash scripts and utilities for automating tasks and streamlining workflows on macOS. This repository includes various scripts for system administration, development, and other automation needs.

## Getting Started

### Prerequisites

To use the scripts in this repository, you'll need:

- macOS operating system
- Bash shell (pre-installed on macOS)
- Any specific tools or dependencies mentioned in individual script descriptions

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/nkululekojonas/bin.git ~/bin
   ```
   Note: this assumes `~/bin` doesn't already exist or is empty. 
   If you already have a non empty `~/bin` directory change destination location when cloning.

2. Navigate to the project directory:
   ```bash
   cd ~/bin
   ```

### Optional

Make the scripts executable: (they should already to be executable)
   ```bash
   chmod +x *
   ```

## Available Scripts

Here's a list of scripts currently available in this repository:

| Script Name | Description |
|-------------|-------------|
| `battery` | Displays battery information (cycle count, health) on macOS |
| `empty` | Empty a directory if it exists |
| `search` | Quick search in a directory for a string |
| `dns-flush` | Flush DNS settings on macOS |
| `longest` | Find the longest line in files of given extension |
| `update` | Update macos, brew, mas and omz (see usage instructions) |
| `netcheck` | Use ping to check for an internet connection |
| `backup` | Backup given directories to target directory |
| `extract` | Extract various formats |
| `hw` | Print Hello, username! |
| `mxc` | Create a file and set executable permissions on it |
| `init-pr` | Create a project directory with a README and initialise version control for it |

## Usage

If your `$PATH` contains `~/bin` use the following command format to run any script:

```bash
script-name
```

For example:

```bash
hw
```

For detailed usage instructions for each script, please refer to the comments within the script files or run the script with the `--help` flag.

## Contributing

Contributions are welcome and appreciated!

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
