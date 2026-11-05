# OS Lab Experiments

This repository contains a collection of experiments related to Operating Systems concepts. The experiments cover basic Linux commands, shell scripting, C programming for process management, and system resource monitoring.

## 📂 Repository Structure

Here is a brief overview of the files and the concepts they demonstrate:

### 1. Shell Scripting & Linux Basics
*   **`exp1`**: Demonstrates basic Linux command usage and syntax.
*   **`exp2`**: Examples of displaying dates and using the `sed` command for text processing.
*   **`exp3a.sh`**: Introduction to basic shell scripting logic.
*   **`exp3b.sh`**: Extended shell scripting experiment.
*   **`exp4a.sh`**, **`exp4b.sh`**, **`exp4c.sh`**: Various shell scripts covering specific logic or command-line operations.

### 2. C Programming & String Handling
*   **`exp5.c`**: Implementation of C programs for calculating string length and extracting substrings.
*   **`exp5.sh`**: A shell wrapper/script to run the string manipulation program.
*   **`exp10.c`**: A program to print the Process ID (PID) and address of a variable (demonstrates address space).

### 3. Memory & Process Management (C)
*   **`exp6.c`**: Demonstrates memory allocation strategies in C (likely using `malloc`/`calloc`).
*   **`exp7a.c`**: An infinite counter program designed to run in the background with periodic output.
*   **`exp7b.c`**: An I/O bound task that continuously writes to a file (`dummy.txt`).
*   **`exp9.c`**: Implementation of `fork()` and `wait()` system calls to create and manage child processes.

### 4. System Monitoring & Analysis
*   **`exp8.sh`**: A script designed to observe the process memory map using the `pmap` command.

## 🛠️ Prerequisites

To run these experiments, you will need:
*   **Linux Environment** (Ubuntu, Debian, or WSL).
*   **GCC Compiler** (for `.c` files): `sudo apt install build-essential`
*   **Bash Shell** (for `.sh` files).

## 🚀 How to Use

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/Suvansh0miet/your-repo-name.git
    cd your-repo-name
