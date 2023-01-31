# Processes and signals
In this project, I learned about handling process ID's and signals in Bash with ps, pgrep, pkill, pkill, exit, and trap.

# Tasks 📃
• 0. What is my PID

    ° 0-what-is-my-pid: Bash script that displays its own PID.

• 1. List your processes

    ° 1-list_your_processes: Bash script that displays a list of currently running processes.
    ° Shows all processes for all users, including those not featuring a TTY.
    ° Processes are displayed in a user-oriented hierarchy.

• 2. Show your Bash PID

    ° 2-show_your_bash_pid: Bash script that displays lines containing the bash keyword based on the script defined in 1-list_your_processes.

• 3. Show your Bash PID made easy

    ° 3-show_your_bash_pid_made_easy: Bash script that displays the PID along with the process name of processes who name contains the word bash.

• 4. To infinity and beyond

    ° 4-to_infinity_and_beyond: Bash script that displays To infinity and beyond indefinitely with a sleep 2 in between each iteration.

• 5. Kill me now

    ° 5-kill_me_now: Bash script that kills the 4-to_infinity_and_beyond process using kill.

• 6. Kill me now made easy

    ° 6-kill_me_now_made_easy: Bash script that kills the 4-to_infinity_and_beyond process using pkill.

• 7. Highlander

    ° 7-highlander: Bash script that displays To infinity and beyond indefinitely with a sleep 2 in between each iteration.
    ° Displays I am invincible!!! upon receiving a SIGTERM signal.

• 8. Beheaded process

    ° 8-beheaded_process: Bash script that kills the process 7-highlander.

• 9. Process and PID file

    ° 100-process_and_pid_file: Bash script that creates the file /var/run/holbertonscript.pid containing its PID and displays To infinity and beyond indefinitely.
    ° Displays I hate the kill command upon receiving a SIGTERM signal.
    ° Displays Y U no love me?! upon receiving a SIGINT signal.
    ° Deletes the file /var/run/holbertonscript.pid and terminates itself upon receiving the SIGQUIT or SIGTERM signal.

• 10. Manage my process

    ° manage_my_process: Bash script that writes I am alive! to the file /tmp/my_process indefinitely.
        •Sleeps two seconds in between each write.
    ° 101-manage_my_process: Bash script that manages the manage_my_process script.
    ° When passed the argument start:
        •Starts manage_my_process.
        •Creates a file containing its PID in /var/run/my_process.pid.
        •Displays manage_my_process started.
    ° When passed the argument stop:
        •Stops manage_my_process.
        •Deletes the file /var/run/my_process.pid.
        •Displays manage_my_process stopped.
    ° When passed the argument restart:
        •Stops manage_my_process.
        •Deletes the file /var/run/my_process.pid.
        •Starts manage_my_process.
        •Creates a file containing its PID in /var/run/my_process.pid.
        •Displays manage_my_process started.
    ° Otherwise, displays Usage: manage_my_process {start|stop|restart}.

• 11. Zombie

    ° 102-zombie.c: C program that creates five zombie processes.
    ° For every zombie created, displays Zombie process created, PID: <ZOMBIE_PID>.
