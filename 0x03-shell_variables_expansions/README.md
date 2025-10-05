# 0x03 - Shell variables, expansions and substitutions

This folder contains small exercises from the ALX System Engineering & DevOps curriculum focused on shell variables, expansions, and substitutions. Each file is a standalone exercise (script or command) that demonstrates a concept or solves a tiny task.

## Goals

-   Learn how to create and use shell aliases and variables.
-   Understand local vs global variable scope in shells.
-   Practice manipulating the `PATH` and running scripts.
-   Use parameter expansion, command substitution, arithmetic expansion, and printf formatting.

## Structure

Files are named with a leading number and a short description. Typical file names and purposes:

-   `0-alias` — create or show an alias for a command.
-   `1-hello_you` — simple script that prints a greeting using variables.
-   `2-path` — modify or print the `PATH` environment variable.
-   `3-paths` — another task involving `PATH` handling.
-   `4-global_variables` — demonstrate exporting variables so child processes inherit them.
-   `5-local_variables` — show local-only variables inside functions or subshells.
-   `6-create_local_variable` — create and use a local variable.
-   `7-create_global_variable` — create and export a global variable.
-   `8-true_knowledge` — small scripting or logic exercise.
-   `9-divide_and_rule` — arithmetic or division handling in shell.
-   `10-love_exponent_breath` — uses expansions or string manipulation.
-   `11-binary_to_decimal` — convert a binary number to decimal using shell tools.
-   `12-combinations` — list or compute combinations (script tasks may vary).
-   `13-print_float` — format and print floating point numbers using printf or bc.

Open each file to see its specific instructions and required behavior. Many ALX exercises include an automated checker (on the learning platform) that expects exact output or return codes, so follow file headers closely when running them.

## How to run exercises

From the repo root or inside this folder, run a script in one of these ways:

Make executable and run:

```pwsh
# from repo root
cd 0x03-shell_variables_expansions
chmod +x 1-hello_you
./1-hello_you
```

Or run with bash explicitly:

```pwsh
bash 1-hello_you
```

Notes:

-   Use WSL or Git Bash on Windows for best compatibility with these exercises.
-   Avoid running scripts that change system-wide configuration unless you understand the effect — prefer a disposable environment.

## Examples

Show `PATH` (example):

```pwsh
# prints the PATH value
bash -lc 'echo "$PATH"'
```

Convert binary to decimal (example using exercise file):

```pwsh
bash 11-binary_to_decimal 1011
# expected output: 11
```

## Testing and verification

-   These exercises are intended for manual practice. If you want to automate checks, write small wrapper scripts that compare expected stdout or exit codes.

## Contributing

If you improve or add scripts, keep each file focused and include a short header describing expected input/output. Open a PR with your changes and include examples or tests.

---

Happy learning — work through the files in numeric order to build your skills progressively.
