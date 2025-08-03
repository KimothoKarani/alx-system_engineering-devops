# 0x03. Shell, init files, variables and expansions

This repository contains solutions to the `0x03. Shell, init files, variables and expansions` project, a foundational module in the ALX System Engineering & DevOps curriculum.

## Project Overview

This project served as a deep dive into the core functionalities of the Bash shell. The primary objective was to gain a comprehensive understanding of how the shell operates, manages its environment, and interprets commands. Through a series of hands-on tasks, I explored various aspects including:

*   **Shell Initialization:** Understanding files like `/etc/profile` and `~/.bashrc` and their roles in configuring the shell environment.
*   **Variables:** Differentiating between local and global (environment) variables, recognizing reserved variables (like `HOME`, `PATH`, `PS1`), and learning how to create, update, and delete them.
*   **Expansions:** Exploring different types of shell expansions (e.g., brace expansion, parameter expansion, command substitution) and the nuances of quoting.
*   **Shell Arithmetic:** Performing basic arithmetic operations directly within the shell.
*   **Aliases:** Creating and managing command shortcuts.

## My Approach and Learnings

For each task, the challenge was to implement the required functionality in a Bash script that was exactly two lines long and adhered to strict constraints (e.g., no `&&`, `||`, `;`, `bc`, `sed`, or `awk` allowed in mandatory tasks).

This project significantly enhanced my understanding of:

*   **Precise Scripting:** The two-line limit forced concise and efficient use of Bash commands and features.
*   **Debugging Shell Behavior:** Understanding how `PATH` works, the difference between executing a script and `sourcing` it, and how aliases modify command behavior.
*   **Environment Management:** How variables are set, exported, and accessed across different shell processes.
*   **Text Processing Fundamentals:** Using basic tools like `printf`, `tr`, `cut`, and `paste` for data manipulation (while adhering to the no-sed/awk rule).

Each script was developed and rigorously tested locally to ensure it produced the exact expected output before being pushed to the repository for automated checking.

## Repository Structure

The project files are located in the `0x03-shell_variables_expansions` directory. Each file corresponds to a specific task, named according to the project's naming convention (e.g., `0-alias`, `1-hello_you`, `100-decimal_to_hexadecimal`).

## List of Scripts (Mandatory & Advanced)

*   **0-alias**: Creates an alias for `ls` to `rm *`.
*   **1-hello_you**: Prints "hello user" where `user` is the current Linux user.
*   **2-path**: Appends `/action` to the `PATH` environment variable.
*   **3-paths**: Counts the number of directories in the `PATH`.
*   **4-global_variables**: Lists all environment variables.
*   **5-local_variables**: Lists all local variables, environment variables, and shell functions.
*   **6-create_local_variable**: Creates a local variable named `BEST` with value `School`.
*   **7-create_global_variable**: Creates a global (exported) variable named `BEST` with value `School`.
*   **8-true_knowledge**: Prints the result of `128 + TRUEKNOWLEDGE`.
*   **9-divide_and_rule**: Prints the result of `POWER / DIVIDE` (integer division).
*   **10-love_exponent_breath**: Prints the result of `BREATH` to the power of `LOVE`.
*   **11-binary_to_decimal**: Converts a binary number (`BINARY`) to decimal.
*   **12-combinations**: Prints all 675 unique two-letter combinations (aa-zz, excluding oo).
*   **13-print_float**: Prints a number (`NUM`) formatted to two decimal places.
*   **100-decimal_to_hexadecimal**: Converts a decimal number (`DECIMAL`) to hexadecimal.
*   **101-rot13**: Encodes/decodes text using ROT13 cipher.
*   **102-odd**: Prints every other line from input, starting with the first line, without `sed` or `awk`.
*   **103-water_and_stir**: *(Note: This task requires custom base conversion not natively supported by Bash within the strict 2-line and forbidden command constraints, making a general solution unfeasible using only allowed tools.)*

---
