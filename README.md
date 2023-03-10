# ALX Zero Day — Git Workflow & Shell Scripting

> Hands-on Git workflow practice and shell scripting fundamentals from the ALX Software Engineering pre-course.

## Overview

This module is part of the ALX **Zero Day** onboarding. While the pre-course introduces Git and Bash for the first time, this set of tasks goes deeper into daily Git operations — branching, ignoring files, staying synchronized with remotes — and reinforces shell scripting patterns used throughout the curriculum.

Each task produces a Bash script or compiled C file.

## Skills covered


- Git repository management with `.gitignore` rules that exclude build artifacts and editor files
- Portable Bash scripting following POSIX conventions (shebang, permissions, exit codes)
- Keeping a local branch synchronized with its upstream remote
- C program compilation and execution from the command line
- Understanding the relationship between working directory, staging area, and committed history

## Tech Stack

| Tool | Purpose |
|---|---|
| Git | Branch management, `.gitignore`, remote sync |
| Bash | Shell scripting |
| GCC | C compilation |
| Linux (Ubuntu) | Development environment |

## Project Structure

| Module | Topic | What Was Practiced |
|---|---|---|
| `0x03-git` | Git workflow | `.gitignore` configuration, Bash scripts, C compilation, remote branch synchronization |

### Key files in `0x03-git`

| File | Description |
|---|---|
| `bash/alx` | Formatted greeting script — reinforces shebang and executable conventions |
| `bash/school` | Output formatting and basic script structure |
| `bash/98` | Multi-line output script |
| `c/c_is_fun.c` | C source file compiled with `gcc` |
| `up_to_date` | Demonstrates merging or rebasing to stay current with the remote branch |
| `.gitignore` | Excludes compiled binaries, editor swap files, and OS-specific artifacts |

## Getting Started

```bash
git clone https://github.com/mgn-dev/alx-zero_day.git
cd alx-zero_day

chmod +x 0x03-git/bash/alx
./0x03-git/bash/alx

gcc 0x03-git/c/c_is_fun.c -o c_is_fun
./c_is_fun
```

**Requirements:** Ubuntu, Git, GCC, Bash.

## Curriculum Context

Builds directly on the Git and Bash foundations from the pre-course.

| Previous | Next |
|---|---|
| [alx-pre_course](https://github.com/mgn-dev/alx-pre_course) | [zero_day](https://github.com/mgn-dev/zero_day) — Vagrant VM setup |
| — | [alx-system_engineering-devops](https://github.com/mgn-dev/alx-system_engineering-devops) — shell and DevOps project |
