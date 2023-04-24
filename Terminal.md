


## **Output**

- [x] $ cat \<file> - output the contents of \<file>
- [x] $ less \<file> - output the contents of \<file> using the less command (which supports pagination etc.)
- [x] $ head \<file> - output the first 10 lines of \<file>
- [x] $ \<cmd> > \<file> - direct the output of \<cmd> into \<file>
- [x] $ \<cmd> >> \<file> - append the output of \<cmd> to \<file>
- [x] $ \<cmd1> | \<cmd2> - direct the output of \<cmd1> to \<cmd2>

- [x] $ clear - clear the command line window

## **Files** 
> __$ rm (file)__ 
>> _**Delete** (file)_        
>   
>__$ rm -r (directory)__    
>> _**Delete** (directory)_   
>   
>__$ rm -f (file)__     
>>_**Force-delete** (file) (add -r to force-
delete a directory)_    
>     
>__$ mv (file-old) (file-new)__     
>> ___Rename__ (file-old) to (file-new)_
>   
>__$ mv (file) (directory)__   
>>___Move__ (file) to (directory) (__possibly overwriting__ an existing file)_   
>
>__$ cp (file) (directory)__       
>>___Copy__ (file) to (directory) (__possibly overwriting__ an existing file)_       
>       
>__$ cp -r (directory1) (directory2)__      
>>___Copy__ (directory1) and __its contents__ to (directory2) (__possibly overwriting__ files in an existing directory)_      
>       
>__$ touch (file)__     
>___Update__ file access & modification time (and create (file) if it doesn’t exist)_

************+
# Command Line
- **cd**: Change directory. Use "cd" followed by the path to the directory you want to navigate to.
- **ls**: List files and directories in the current directory.
- **pwd**: Print the current working directory.
- **mkdir**: Create a new directory. Use "mkdir" followed by the name of the new directory.
- **touch**: Create a new file. Use "touch" followed by the name of the new file.
- **rm**: Remove a file or directory. Use "rm" followed by the name of the file or directory you want to remove. Add the "-r" flag to remove a directory and its contents recursively.
- **cp**: Copy a file or directory. Use "cp" followed by the name of the file or directory you want to copy, and the destination path.
- **mv**: Move a file or directory. Use "mv" followed by the name of the file or directory you want to move, and the destination path.
- **cat**: Print the contents of a file to the terminal.
- **grep**: Search for a pattern in a file or set of files. Use "grep" followed by the pattern you want to search for, and the name of the file(s) you want to search.
- **top**: Display information about running processes on your system, including CPU and memory usage.
-**ps**: Display information about currently running processes.
- **kill**: Terminate a running process. Use "kill" followed by the process ID (PID) of the process you want to terminate.
- **chmod**: Change the permissions of a file or directory. Use "chmod" followed by the desired permissions and the name of the file or directory.
- **sudo**: Run a command with administrative privileges.