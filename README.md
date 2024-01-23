[中文版](README_SCH.md)

# TshLab15213

## Introduction

This project is part of the CMU 15-213 course Shell Lab. 
Tiny Shell (tsh) is a minimalistic shell implementation for Unix-based systems. It provides basic shell functionalities including executing commands, handling job control, and processing signals.

## Features

1. Execution of basic Unix commands.
2. Support for job control: foreground and background job execution.
3. Signal handling: SIGINT, SIGTSTP, and SIGCHLD.

## How to Run
Compile the shell using make:

```bash
make
```

Run the shell:
```bash
./tsh
```

## Built-in Commands
`bg <job>`: Resume a stopped job in the background.

`fg <job>`: Move a job to the foreground.

`jobs`: List all background jobs.

`quit`: Exit the shell.

>>Notes:
    `<job>` can be either a process ID (PID) or a job ID (JID) prefixed with %.