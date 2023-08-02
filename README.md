# Linux Bash Terminal Keyboard Shortcuts

1. Move to the start of the command line


    ```
    Ctrl + A
    ```
2. Move to the end of the command line

    ```
    Ctrl + E
    ```

3. Move one character forward
    ```
    Ctrl + F
    ```

4. Move one character backward
    ```
    Ctrl + B
    ```

5. Switch cursor position between start of the command line and the current position

    ```
    Ctrl + XX
    ```
6. Moves the cursor one word forward

    ```
    Alt + F / Esc + F
    ```

7. Moves the cursor one word forward

    ```
    Alt + B / Esc + B
    ```

8. Similar to clear command, clears the terminal screen

    ```
    Ctrl + L
    ```
9. Stops command output to the screen

    ```
    Ctrl + S
    ```

10. Suspends current command execution and moves it to the background

    ```
    Ctrl + Z
    ```

11. Resumes suspended command

    ```
    Ctrl + Q
    ```

12. Sends SIGI signal and kills currently executing command

    ```
    Ctrl + C
    ```

13. Closes the current terminal

    ```
    Ctrl + D
    ```

14.  Bash History

    ```
    Ctrl + R
    ```

15. Non-incremental reverse search of bash history

    ```
    Ctrl + J
    ```

16. Ends history search at current command

    ```
    Ctrl + _
    ```

17. Undo previous command

    ```
    Ctrl + P / Up arrow
    ```

18. Moves to previous command

    ```
    Ctrl + N / Down arrow
    ```

19. Runs last command

    ```
    !!
    ```

20. Runs previous command except its first word

    ```
    !*
    ```


## Linux process management commands cheatsheet

- `ps`: Displays information about active processes running on the system.
- `pstree`: Displays a hierarchical tree structure of processes.
- `kill`: Sends a signal to terminate or interrupt a process.
- `killall`: Terminates all processes with a specific name.
- `pkill`: Sends a signal to terminate or interrupt processes based on their name.
- `pgrep`: Lists process IDs based on matching criteria.
- `nice`: Launches a command with a specified priority level.
- `renice`: Changes the priority level of a running process.
- `jobs`: Lists active jobs in the current shell session.
- `fg`: Brings a job to the foreground.
- `bg`: Sends a job to the background.
- `nohup`: Runs a command that ignores hangup (HUP) signals.
- `screen`: Manages multiple terminal sessions within a single shell session.
- `ps aux`: Displays detailed information about all active processes.
- `systemctl`: Controls the systemd system and service manager.
- `top`: Provides real-time information about system resource usage and active processes.
- `htop`: Interactive process viewer that displays system resource usage and process information.
- `btop++`: Another interactive process viewer with additional features.
- `lsof`: Lists open files and the processes that have them open.
- `&`: Executes a command in the background, allowing the user to continue using the terminal.