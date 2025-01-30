# CMD CHALLENGE

## website https://cmdchallenge.com/ 


### Challenge 1


#### Your first challenge is to print "hello world" on the terminal in a single command.

Hint: There are many ways to print text on the command line, one way is with the 'echo' command. Try it below and good luck!

Solution : 
 ```bash
 echo "hello world"
 ```

### Challenge 2

#### Print the current working directory.

Solution : 
 ```bash
pwd
 ```
### Challenge 3

#### List names of all the files in the current directory, one file per line..

Solution : 
 ```bash
 ls
 ```
 ### Challenge 4

#### There is a file named access.log in the current directory. Print the contents.

Solution : 
 ```bash
 cat access.log
 ```

 ### Challenge 5

#### Print the last 5 lines of "access.log".

Solution : 
 ```bash
 tail -n 5 access.log 
 ```

 ### Challenge 6

#### Create an empty file named take-the-command-challenge in the current working directory.

Solution : 
 ```bash
 touch take-the-command-challenge 
 ```

 ### Challenge 7

#### Create a directory named tmp/files in the current working directory

Solution : 
 ```bash
 mkdir -p tmp/files
 ```

 ### Challenge 8

####  Copy the file named take-the-command-challenge to the directory tmp/files


Solution : 
 ```bash
 cp take-the-command-challenge tmp/files
 ```

 ### Challenge 9

#### Move the file named take-the-command-challenge to the directory tmp/files

Solution : 
 ```bash
 mv take-the-command-challenge tmp/files
 ```

 ### Challenge 10

#### Delete all of the files in this challenge directory including all subdirectories and their contents.

Hint: There are files and directories that start with a dot ".", "rm -rf *" won't work here!

Solution : 
 ```bash
 rm -rf ./* ./.*
 ```
