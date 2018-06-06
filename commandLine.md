# Commands

## pwd
Lists the present working directory
## cd <directoryName>
changes present working directory
## mkdir <directoryName>
makes a new directory in the PWD
## rmdir <directoryName>
Removes the drectory called directoryName
## rm <filename>
removes a filename
## touch <fileName>
Makes a new file in the PWD
## ls  <directoryName?>
lists all files in the PWD
## clear
Clears the text off the terminal

### Special Directories

~ home
.. Up a level
. same level
/ root directory

# GIT Commands

## clone <repoURL>
Downloads repository to your local PWD

## init 
Starts a local git repository

## add <files> 
Tracks file or folders (you can use git.add to track everything)

## commit <-m> <message>
takes a snapshot of the directory 

## push <server?> <branch?>
send your commits to the server

## pull <server?> <branch?>
Recieves commits from the server 

## When pushing to github
1.  git add <filename>
    -this adds Filename to the changelist
    -Use git add . or git add -A to add everything to the changelist
    
2. git commit -m "some commit message"
        -if you forget -m you will be in vi (a comand line text editor).
        type "i", then type your msessage, then press "esc, then ":wq" and finally enter

3. git push <server> <branch>
        -you can usually just use "git push"





