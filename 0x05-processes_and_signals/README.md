##0x05-processes_and_signals
###0.What_is_my-PID
Write a Bash script that displays its own PID.
Files-->0-what-is-my-pid
###1.List_your_processes
Write a Bash script that displays a list of currently running processes.

Requirements:

Must show all processes, for all users, including those which might not have a TTY
Display in a user-oriented format
Show process hierarchy
Files-->1-list_your_processes
###2-show_your_bash_pid
Using your previous exercise command, write a Bash script that displays lines containing the bash word, thus allowing you to easily get the PID of your Bash process.

Requirements:

You cannot use pgrep
The third line of your script must be # shellcheck disable=SC2009 (for more info about ignoring shellcheck error here)
Files--> 2-show_your_bash_pid 
###3-show_your_bash_pid_made_easy
Write a Bash script that displays the PID, along with the process name, of processes whose name contain the word bash.

Requirements:

You cannot use ps
Files--> 3-show_your_bash_pid_made_easy
###4-to_infinity_and_beyond
Write a Bash script that displays To infinity and beyond indefinitely.

Requirements:

In between each iteration of the loop, add a sleep 2
Files--> 4-to_infinity_and_beyond
###5-dont_stop_me_now
We stopped our 4-to_infinity_and_beyond process using ctrl+c in the previous task, there is actually another way to do this.

Write a Bash script that stops 4-to_infinity_and_beyond process.

Requirements:

You must use kill
Terminal #0
Files--> 5-dont_stop_me_now
###6-stop_me_if_you_can
Write a Bash script that stops 4-to_infinity_and_beyond process.

Requirements:

You cannot use kill or killall
Terminal #0
Files--> 6-stop_me_if_you_can
~
~

