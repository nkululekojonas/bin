# Shell Utilities

A collection of Bash scripts and utilities for automating tasks and streamlining workflows on macOS. This repository includes various scripts for system administration, development, and other automation needs.

## Table of Contents

- [Overview](#overview)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Available Scripts](#available-scripts)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Overview

This repository serves as a hub for various Bash scripts designed to enhance productivity and simplify system management on macOS. Whether you're a developer, system administrator, or someone looking to automate repetitive tasks, you'll find useful scripts here to streamline your workflow.

## Getting Started

### Prerequisites

To use the scripts in this repository, you'll need:

- macOS operating system
- Bash shell (pre-installed on macOS)
- Any specific tools or dependencies mentioned in individual script descriptions

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/nkululekojonas/shell-utilities.git
   ```

2. Navigate to the project directory:
   ```bash
   cd shell-utilities
   ```

3. Make the scripts executable:
   ```bash
   chmod +x *.sh
   ```

## Available Scripts

Here's a list of scripts currently available in this repository:

| Script Name | Description |
|-------------|-------------|
| `battery.sh` | Displays battery information (cycle count, health) on macOS |
| `init-repo.sh` | Initializes a Git repository in a specified location and adds a default `.gitignore` file |
| `hw.sh` | Prints Hello, Wold! |

## Usage

To run any script, use the following command format:

```bash
./script-name.sh
```

For example:

```bash
./battery.sh
```

For detailed usage instructions for each script, please refer to the comments within the script files or run the script with the `--help` flag.

## Contributing

Contributions are welcome and appreciated! If you have a useful script or improvements to existing ones, please follow these steps:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/AmazingFeature`)
3. Make your changes
4. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
5. Push to the branch (`git push origin feature/AmazingFeature`)
6. Open a Pull Request

Please ensure your code adheres to the existing style and includes appropriate documentation.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

For any questions or issues, please open an issue on the GitHub repository.
