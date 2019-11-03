Here are a few tips:

**Tip**: `stty -echo`

**Description**: Anything that is typed after this command does not appear on the screen (like when you type passwords on the terminal). This command can be undone by the `stty echo` command.

----

**Tip**: `touch filename.date +%d`

**Description**: Creates a file with the name filename.23 if the date on that day is the 23rd. You can add %m to also have the month or %y to include the year as well in the name. Helps to have a track of when you made a particular file. (date +%d must be within backticks. pls fix this if someone can.)

----

**Tip**: `!.`

**Description**: Short command for ./a.out.

----

**Tip**: `top -H -d <time> -p <PID>`

**Description**: The top command gives information about the currently running processes on the OS. -H flag is used to display threaad level information. -d <time> specifies the refresh rate of the command. -p <PID> is used to specify the process ID of the process about which you want top to display information about. 

----

**Tip**: `sudo !!`

**Description**: The `!!` command gets the last command. For example, when you forget to add sudo in front of the command` apt-get install <name>` running `sudo !!` lets you update without having to type the whole command again.

----

**Tip**: `history`

**Description**: The `history` command by itself will simply print out the bash history of the current user to the screen. Commands are numbered, with older commands at the top and newer commands at the bottom.

----

**Tip**: `tail /etc/passwd > abc.txt`

**Description**: Writes the bottom 10 lines into abc.txt.

----
