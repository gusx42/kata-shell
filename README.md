# kata-shell

## shell commands reference
### Navigations
- cd : change directory
- cd : go to home
- cd {dir_path} : go to directory path
- cd .. : on directory above
- cd - : back to last directory path
- ls -a : list all (include hidden file and folder)
- ls -l : long list
- ls -la : long list all
- pwd : print working directory
### Directory / file management
- mkdir : create a new folder
- rm : remove
- rm {file_name} : delete a file
- rm -r {dir_name} : delete a folder
- rmdir : remove directory, only allows to delete empty - directory
- cp : copy
- cp {old_file} {new_file} : copy a file
- cp -r {old_dir} {new_dir} : copy a folder and all sub folder
- mv : move
- mv {old_file_path} {new_file_path} : move a file or folder
- mv {old_file_name} {new_file_name} : rename a file or folder
- locate {file_name} : search a file or folder
- locate -i {file_name} : search file with case sensitive
- find {dir_path} {file_name} : search a file or folder inside - a directory
- tar : archive multiple files into a tarball
- zip : compress files into a zip archive
- unzip : extract the zipped files
### File view and editing
- nano : view and edit with nano
- vim : view and edit with vim
- cat : view file
- cat > {file_name} : create a new file
- cat {file_1} > {file_2} : copy file 1to file 2
- cat {file_1} >> {file_2} : append file 1 content to file 2
- grep {keyword} {file_name} : search through all the text in a - given file
- head : view the first lines of any text file, by default it will showing first 10 lines
- head -n 5 {file_name} : display first 5 lines of the file
- tail : view the last lines of any text file, by default it - will showing - first 10 lines
- tail -n 5 {file_name} : display last 5 lines of the file
### Manual guide
- man : manual
- man cp : display full guide for copy command
- --help : help
- cp --help : display short guide for copy command
### System commands
- sudo : SuperUser Do, enables to perform tasks that require - administrative or root permissions
- command1; command2; command3 : run multiple commands
- command1 && command2 && command3 : run the next commands - after the first one is successful
- useradd {username} : add a new user
- passwd {password} : set the password
- userdel : delete a user
- chmod {options} {file_name} : change the read, write, and - execute permissions of files and directories
- chmod u=rwx,g=rx,o=r {file_name}
    - u : user
    - g : group
    - o : other
    - r : read
    - w : write
    - x : execute
- chown {username} {file_name} : change or transfer the - ownership of a file
- uname : print detailed information about your Linux system
- hostname : display the name of host/network
- hostname -i : display the IP address of the network
- wget {link} : download from the internet
- ps : display information about the currently running - processes, including their process identification numbers - (PIDs)
- kill {pid} : terminate an unresponsive program
- df : get a report on the system’s disk space usage
- df -h : display disk space statistics
- df -m : display disk space statistics in megabytes
- du -h : display disk usage
- free -m : show free memory
- cat /proc/cpuinfo : display cpu info
- htop / top : monitor system resources
- history : review the commands we’ve entered before
- clear : clean out the terminal
### Keyboard shourcut
- ctrl + C : safe kill
- ctrl + Z : sometimes there are child processes that still - running in the background
- ctrl + A : moves to the beginning of the line
- ctrl + E : moves to the end of the line