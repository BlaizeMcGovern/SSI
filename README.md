# P1



## SSI

This is a simple SSI for CSC360, to compile and run this program: Clone the repo, run the Makefile by using "make", run the program using ./ssi

## Forground Execution

- My ssi can execute ls without additional parameters and output the content correctly within the current directory.
- My ssi can execute ls with parameters, such as ls -alh, ls -alh ./, ls -l /usr/bin and output the content within the corresponding directory correctly.
- My ssi can execute long-running programs in the foreground, and it can respond to Ctrl-C to stop the program. For example, ping 1.1.1.1.
- My ssi can execute arbitrary external programs, and prints <name>: No such file or directory when the requested external program doesn't exist.


## Changing Directories

- My ssi can print the current working directory by pwd.
- My ssi can change to directories by specifying absolute directory paths, such as cd /usr/bin, cd /tmp.
- My ssi can handle relative directory paths, such as cd ., cd .., cd ../...
- My ssi can change to the user's home directory if no parameters are given to the cd command, and it can handle the special ~.


## Background Execution

- My ssi can use bg to execute programs in the background, such as bg cat foo.txt, bg ping 1.1.1.1.
- When putting a job into the background using bg, my ssi can still accept user input in the foreground.
- My ssi can use bglist to list the currently running background jobs.
- When a background job is finished, my ssi outputs <pid>: <program> <parameters> has terminated. when processing the next user input.
- My ssi can update background jobs correctly. For example, terminated background jobs should not appear in the bglist output.

##Yea thats right, I took an operating systems course. This is the proof
- I'm going to add the code after the due date for this assignemnt has passed...
