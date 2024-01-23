[ENGLISH](README.md)

# TshLab15213

## Introduction

这个小项目是基于CMU15-213课程的。 
Tiny Shell (tsh) 是一个基于 Unix 系统的简易 shell 实现。它提供了基本的 shell 功能，包括执行命令、处理作业控制和信号处理。

## 功能

1. 执行基本的 Unix 命令。
2. 支持作业控制：前台和后台作业执行。
3. 信号处理：SIGINT、SIGTSTP 和 SIGCHLD。

## 如何运行
编译 shell:

```bash
make
```

运行 shell:
```bash
./tsh
```

## 内置命令
`bg <job>`：在后台恢复一个停止的作业。

`fg <job>`：将一个作业移到前台。

`jobs`：列出所有后台作业。

`quit`：退出 shell。

>>注意事项:
    <job> 可以是进程 ID (PID) 或以 % 为前缀的作业 ID (JID)。