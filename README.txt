'ssh' - SSH stands for secure shell. it is a network protocol that helps to establish secure connection over a insecure network between two hosts.

syntax : ssh [username]@[hostname or IP address]

'ls' - this command is used to list files in the current directory or at specified directory
       this does not shows the hiddent files
    -l flag - long listing flag - lists files and folders with permisions.
    -a flag - shows hidden files also

'cd' - this command is used to hover around directory.
    cd <location> to move to that directory
    cd .. to move to parent directory
    cd ~ to move to home directory

'cat' - this command is used to print read files, concatenate files, write into files.
        if you want to read files which start with - , then full path of the file is to be specified.

'file' - this command reads the file and tries to classify them by its type.
        file <filename>
        file * - to get type of all file in current directory

'find' - find command is used to search for a file  in a directory and its subdirectory.
        find <wheretofind> <attributes of file search>
    
'man' - man command is like manual for commands. it shows a description for the command     along with its attributes. 
        it does not give description of built-in commands. for this use help to get the description.

'grep' - gloal regual expression print - it searches for a pattern in each file and displays the line which matches.
        -i - ignore case
        -w - find exact match
        -c - count no of occurences of the pattern
        -l - to search patten in files
        
