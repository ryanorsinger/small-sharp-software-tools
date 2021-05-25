##Commands 
- `ps -ef` show all the running processes
- `cd`
- `pwd`
- `echo`
- `echo hello > greetings.txt`
- `cat`
- `less/more`
- `clear`
- `reset`
- `mkdir`
- `curl`
- `which`
- `man`
- `history`


## Vocabulary
filesystem
directory
path
redirection,


## Concepts
No visual feedback when things do as they're told.
We can programmatically, as opposed to manually, create files
Navigate less/more with spacebar, q, direction arrows
Redirection means to take the output of one command and direct it somewhere else
Redirecting streams of text to files
Redirecting streams of text to other commands
Imagine the data that flows as a stream of text that can be processed by programs
Tab autocomplete (single and double tab)
root user, privileges, elevated privileges
up arrow to access last commands

## Drills
echo hello > greetings.txt
cat /usr/share/dict/words
less /usr/share/dict/words
ps -ef
ps -ef > processes.txt
ps -f | less
man echo
man builtins
history
history | tail  
!!
sudo !!
ctrl + a
ctrl + e
ctrl + l
ctrl + r
ctrl + u
history > history.txt
curl -O https://media.pragprog.com/titles/bhcldev/code/bhcldev-code.zip then unzip bhcldev-code.zip


## Things to know
- `history > history.txt` writes the history.txt file w/ the contents of the history command
- `echo "hello" > hello.txt` creates or overwrites the file
- `echo "hello" >> hello.txt` creates or appends to the end of the file
- `ls -l > list.txt` creates a file named `list.txt` with the contents of the current working directory






## Big Lessons (to teach through repetition)
- "As you work on the command line, you’ll find yourself taking the output of one program and sending it off to another program, which will then output something new." - Brian P. Hogan
- When the terminal does what it's told without error, you will often NOT get a notification. The command runs.
- Workflow
	- Relative vs. absolute paths
	- tab autocomplete