# processes_and_signals

Bash scripting project exploring Unix processes and signals: PIDs, listing
and filtering processes, backgrounding, sleep, and trapping/sending
signals (SIGINT, SIGTERM, SIGQUIT) to control long-running scripts.

## Tasks
0. 0-what-is-my-pid - displays its own PID
1. 1-list_your_processes - lists all processes, all users, hierarchy view
2. 2-show_your_bash_pid - shows process lines containing "bash"
3. 3-show_your_bash_pid_made_easy - shows PID + name for "bash" processes
4. 4-to_infinity_and_beyond - infinite loop printing a message
5. 5-dont_stop_me_now - stops it with kill
6. 6-stop_me_if_you_can - stops it without kill/killall
7. 7-highlander / 67-stop_me_if_you_can - survives SIGTERM
8. 8-beheaded_process - kills 7-highlander for real (SIGKILL)
9. 10-process_and_pid_file - PID file + SIGTERM/SIGINT/SIGQUIT handling
10. manage_my_process / 11-manage_my_process - start/stop/restart daemon
