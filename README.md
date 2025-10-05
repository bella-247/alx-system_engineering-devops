# alx-system_engineering-devops

This repository contains learning exercises for the ALX System Engineering & DevOps curriculum. The exercises are focused on shell scripting, environment variables, and basic Unix/Linux command-line techniques used to build practical DevOps skills.

## Repository layout

Top-level files and folders you'll find in this repo:

- `0x03-shell_variables_expansions/` - Exercises that explore shell variables, expansions, and simple shell scripting patterns.
  - `0-alias` through `13-print_float` - Individual exercise scripts and programs (see the folder for full list).
- `README.md` - This file.

## Purpose

The goal of these exercises is to provide small, focused tasks that help you practice shell fundamentals: creating aliases, manipulating the `PATH`, creating and using local and global variables, doing numeric and string operations, and learning command substitution and expansions.

## How to use

Requirements:

- A Unix-like shell (bash/sh). On Windows, use WSL, Git Bash, or a compatible terminal.

Quick start:

1. Open a terminal and navigate to the repository root.
2. Change into the exercises directory:

	cd 0x03-shell_variables_expansions

3. Make a script executable (if needed) and run it. Example:

	chmod +x 1-hello_you
	./1-hello_you

Or run it with the shell explicitly:

	bash 1-hello_you

Notes:

- Many files are small scripts intended to be run directly from the command line. They may expect no arguments, or they may be interactive — inspect the script header or comments for usage.
- If a script requires root privileges or modifies system configuration, it will be documented in the script itself. Prefer running exercises in a safe, disposable environment.

## Exercises overview (0x03 - Shell variables & expansions)

The `0x03-shell_variables_expansions` folder contains exercises named with a leading number and a short title. Examples include:

- `0-alias` — create a short alias for a command.
- `1-hello_you` — simple script demonstrating output and variables.
- `2-path`, `3-paths` — working with the `PATH` variable.
- `4-global_variables`, `5-local_variables`, `6-create_local_variable`, `7-create_global_variable` — create and use shell variables with different scopes.
- `8-true_knowledge`, `9-divide_and_rule` — small logic/arithmetics tasks.
- `10-love_exponent_breath` through `13-print_float` — additional exercises demonstrating expansions, conversions, and formatting.

See each file's header comments for the exact task and expected behavior.

## Testing and validation

- There are no automated tests in this repository by default. You can manually run the scripts as described in "How to use". For learning purposes, add simple assertions or compare outputs when you want to verify behavior.

## Contributing

Contributions are welcome. Suggested workflow:

1. Fork the repository.
2. Create a feature branch: `git checkout -b feature/my-improvement`.
3. Make your changes and add tests or examples where appropriate.
4. Open a pull request describing what you changed and why.

Please keep changes focused and include clear commit messages.

## License

No license file is included in this repository. If you want to add a license, add a `LICENSE` file at the repository root (MIT is commonly used for personal exercise repos).

## Contact / Author

This repo is a personal collection of ALX exercises. For questions or suggestions, open an issue or pull request.
    