Here are a few tips:

**Tip**: `stty -echo`

**Description**: Anything that is typed after this command does not appear on the screen (like when you type passwords on the terminal). This command can be undone by the `stty echo` command.

----

**Tip**: `touch filename.date +%d`

**Description**: Creates a file with the name filename.23 if the date on that day is the 23rd. You can add %m to also have the month in the name. Helps to have a track of when you made a particular file. (date +%d must be within backticks. pls fix this if someone can.)

----

**Tip**: `!.`

**Description**: Short command for ./a.out.

----

**Tip**: `top -H -d <time> -p <PID>`

**Description**: The top command gives information about the currently running processes on the OS. -H flag is used to display threaad level information. -d <time> specifies the refresh rate of the command. -p <PID> is used to specify the process ID of the process about which you want top to display information about. 

----

**Tip**: `sudo !!`

**Description**: When you forget to add sudo infront of your ` apt-get install name`
                 `!!` gets the last command.

----
