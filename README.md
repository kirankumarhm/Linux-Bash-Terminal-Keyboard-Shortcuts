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

-  Displays information about active processes running on the system.
```
ps
```
-  Displays a hierarchical tree structure of processes.
```
pstree
```
-  Sends a signal to terminate or interrupt a process.
```
kill
```
-  Terminates all processes with a specific name.
```
killall
```
-  Sends a signal to terminate or interrupt processes based on their name.
```
pkill
```
-  Lists process IDs based on matching criteria.
```
pgrep
```
-  Launches a command with a specified priority level.
```
nice
```
-  Changes the priority level of a running process.
```
renice
```
-  Lists active jobs in the current shell session.
```
jobs
```
-  Brings a job to the foreground.
```
fg
```
-  Sends a job to the background.
```
bg
```
-  Runs a command that ignores hangup (HUP) signals.
```
nohup
```
-  Manages multiple terminal sessions within a single shell session.
```
screen
```
-  Displays detailed information about all active processes.
```
ps aux
```
-  Controls the systemd system and service manager.
```
systemctl
```
-  Provides real-time information about system resource usage and active processes.
```
top
```
-  Interactive process viewer that displays system resource usage and process information.
```
htop
```
-  Another interactive process viewer with additional features.
```
btop++
```
-  Lists open files and the processes that have them open.
```
lsof
```
- Executes a command in the background, allowing the user to continue using the terminal.
```
&
```