##commands

- ssh - SSH stands for secure shell. it is a network protocol that helps to establish secure connection over a insecure network between two hosts.
  ssh [username]@[hostname or IP address]

- pwd - tells the directory in which we are present

- ls - this command is used to list files in the current directory or at specified directory
  
       this does not shows the hiddent files
  
    -l flag - long listing flag - lists files and folders with permisions.
    -a flag - shows hidden files also

- cd - this command is used to hover around directory.
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

'tar' - it is used to compress file
        tar -zcf <archive.zip> <files to be compressed>
        tar -xvf <compressed file name> -C <folder where to be extracted>

'man' - man command is like manual for commands. it shows a description for the command     along with its attributes. 
        it does not give description of built-in commands. for this use help to get the description.

'grep' - gloal regual expression print - it searches for a pattern in each file and displays the line which matches.
        -i - ignore case
        -w - find exact match
        -c - count no of occurences of the pattern
        -l - to search patten in files

'sort' - this command sort each line in ascending order based on characters.

'uniq' - it compares consecutive lines and deletes line that repeats.
        -c - displays no of times line appears
        -u - displays unrepeated lines

'strings' - it extracts printable characters from non-printable characters.
        string <filename>

'base64' - it is a encoding decoding command. it can encode a file using base64 or decode a file into normal text which was coded using base64.
         base64 <filename> - to encode
         base64 -d <filename> - to decode

'tr' - it is used to translate one character scheme to another. 

       tr <what-to-translate> <to-what-to-translate>

'telnet' - it is used to communicate to remote systems over TCP/IP network. it is not secure network as data sent though it is unencrypted. thus ssh is more preferably used.

# VIM

vim is a text editor provided by any unix based OS.

- to exit from vim - esc + :q

- to open  a file with vim - vi <filename>

- :wq - to save and exit from file

#### Modes in VIM

- INSERT mode - in this mode you can move around file and make changes to it 
  
  - i - to enter to INSERT mode

- NORMAL mode - in this mode you can move around the file but cannot make changes to it.
  
  - l or right key to move right 
  
  - h or left key to move left
  
  - k or up key to move up
  
  - j or down key to move down
  
  - dd to delete a line
  
  - gg to move to filrst line of file
  
  - G to move to last line of file
  
  - w to jump words
  
  - :%s/foo/bar/ - to replace all occurence of foo with bar
  
  - yw to copy a word
  
  - yy to copy a line
  
  - p to paste

- COMMAND mode  - allows you to execute commands.

- 