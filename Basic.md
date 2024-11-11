# Learning red hat
## Basic commands
- su -l  :-- login as root user
- login  :-- to login
- pwd :-- present working directory.
- man :-- used for accessing manual.
- ping sitelink :-- used for checking connection with a site.
- whoami :--name of user.
- hwclock :-- to access the hardware clock. 
- date :-- to show system date and time.
- time:-- to check time difference between system time and others.
- clear :-- used for clearing the interface commands.
- free :-- used for checking free memory.
- ip addr:-- Display all IP addresses for all interfaces.
- ip addr show eth0:-- Display only IP address information for the eth0 interface.
- ip help :-- Display basic help about the ip command.
- ip link help :-- Display help about the ip link subcommand.
- echo $((expression)) :-- calculate arthemetic expressions like addition, substraction, multiplication and so on.
## Operators
- ">" :-- this operator is used with commands like cat, echo, etc. when user wants to overwrite already written file.
- ">>" :-- appends new data or text at the end of the file.
- "|" :-- known as pipe operator, this operator is used for joining more than one commands in linux.
- "||" :-- this operator is used when one of the command used is to be run. If first command fails, then the second command runs and error message for first command is printed also. It is used inside <b>subshell</b>.
- "&&" :-- it is used to make sure that second command runs if and only if first one runs smoothly.  It is used inside <b>subshell</b>.
- "()" :-- it can be used to create a <b>subshell</b> where the commands entered in the brackets run without effecting the main shell.
## ls commands
- ls :-- used for listing all the directories present.
- ls –color=none :-- used for listing directories and files without any color.
- ls -ltr :-- used for listing all the directories order by time of modification.
- ls -l:-- list the directories in long format.
- ls -la:-- to display all(-a) contents of dictionary in long(-l) format.
- tree:-- list all directories and contents in a tree format.
## File Management
- touch f1:-- used for creating a new file.
- echo “text”>f1:-- used for writing text in a file(overwrites).
- cat f1:-- used for reading contents of a file.
- cat > f1 :-- overwrites the data present in f1.
- cat >> f1 :-- appends the new entered data to f1 file.
- cat f1 f2 > f3 :-- concatenates the content of f1 and f2 into f3 and overwrites the already present text in f3.
- tac f1 :-- reverse the file data vertically.(output can be stored using same way as in cat).
- rev f1 :-- reverses the file data horizontally.
- mkdir :-- used for making directories.
- rm :-- removes a file.
- rm -d:-- to remove a directory.
- rm -r:-- remove a directory along with all the folders and files inside it.
- cp :-- copies one or more files from source to destination.
- cp -r:-- copies directories from source to destination.
- mv :-- moves one or more files from source to destination.
- mv -r:-- moves directories from source to destination.
(NOTE:-- mv and cp can also rename the file. Just put a new name for the file in destination. Ex:-- <i>mv name.txt xyz/abc.txt</i> , will move the file name.txt to xyz folder with the new name "abc.txt")
- head f1 :-- shows first 10 lines of the file by default. With option -n , we can give number of lines to be shown on the screen.
- tail f1 :-- just like head command shows first n lines, tail command shows last n lines.
- less f1 :-- shows only that much data of the file which can be easily shown on one single page. Use arrow keys , up and down , to navigate through the file.
- sort :-- sorts the data , files or directories.
- sort -u :-- removes duplicates while sorting.
- sort -r :-- sort the data in reverse order.
- sort -n :-- sort the numbers.
- sort -k(and a number) :-- sort according to nth part of the line separated by space.
- grep [option] "pattern" f1 :-- search a particular pattern in a file or multple files. Use pipe operator to find a pattern in files.
- wc -l :-- gives the word count of the given file.

- Note :-- 
1. f1,f2,..etc are file names.
2. "> f1" can be used with any command to store the output of the command into a file. Use "2" before ">" to store the error into the file.
