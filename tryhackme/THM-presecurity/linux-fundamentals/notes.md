## Common directories
- "/etc": stores system files that are used by the OS.
- "etc/passwd" and "etc/shadow": stores user credentials in encrypted formatting.
- "/var": stores frequently accessed data by services or applications.
- "/root": home for the root system user.
- "/tmp": stores temporary data.

## Operators
- "&": run the command in the background.
- "&&": combines multiple commands in one line.
- ">": redirector from an input to an output, replacing when duplicate.
- ">>": redirector from an input to an output, appending instead of replacing.

## Frequent commands
- "ls": lists content of the location you are in.
- "cd": changes directory.
- "cat": prints file content.
- "pwd": prints your location full path.
- "man" command: prints a manual of the command.
- command "--help": quick reference to the command options.
- "touch": creates a file.
- "mkdir": creates a folder directory.
- "cp" origin destination: copy a file or a folder to the destination.
- "mv" origin destination: move a file or a folder to the destination.
- "rm": remove a file or a folder.
- "file" file: determines the type of the file.
- "su" user: switches to the user determined.
- "nano" file: creates or edits a file. Features accessed via CTRL such as CTRL+X to exit.
- "wget" link: downloads files from the web via HTTP.
- "python3 -m http.server": turns the machine into a web server to serve files to be downloaded by another computer.
- "ps": list all running processes in our user's session and some additional information.
- "ps aux": lists processes running by other users or without a session.
- "kill" SIGTERM/SIGKILL/SIGSTOP PID (process ID): terminate processes, sigterm for clean kill, sigkill for no cleanup, and sigstop to stop or suspend a process.

## Important commands
- "find -name" file.extension: finds the file searching through every folder in our CURRENT directory.
- "wc -l" file.extension: counts the number of lines of the specified file, where wc is word count and 'l' would be line count only.
- "grep" entry file.extension: searches the entire content of the file and finds the entry value specified.
- "ssh" user@machine_IP: connects to the targeted machine via ssh.
- "scp" origin/file destination/file or "scp" destination/file origin/file: securely copy file using SSH protovol.
- "crontab -e": allows to edit the file used by cron process to automate actions or tasks. Use it along Crontab Generator or Cron Guru.
- "add-apt-repository": adds additional repositories to the OS. To remove is "--remove" repository.

---

## Examples
- "ls -a": lists every content, including hidden folders and directories.
- "ls -lh": lists directory content but -l determines a long listing format, and -h determines the output to be human-readable sizes.
- "su -l" user: Switches user and loads the whole environment and variables.
- "rm -R": removes an entire directory.
- "cd ..": changes directory to the parent directory.
- "find -name *.txt": finds every .txt file in the folders of our current directory.
- "wget http://machine_IP:port/file": downloads the file from a web server hosted on a remote machine.
- "scp fileexample.txt user@machine_IP:/home/ubuntu/filetransfer.txt": copies a file from the current machine to the remote machine.
- "scp user@machine_IP:/home/ubuntu/remotefile.txt local.txt": copies a file from the remote machine to the current machine.