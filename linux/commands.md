# Linux Commands - Week 1

# Chapter 1 Notes
## Navigation 
- `pwd` -  prints the full path of the folder I`m currently in.
- `cd <path>` - Absolute path ie cd /usr/bin 
- Relative path ie `cd /usr/bin` then `cd ../share`.
- `cd ~` / `cd` - Home command.
- `ls` - lists everything in the folder. 
- `cd ..` - Goes up the folder.
- `cd -` - Goes back to the previous directory.
- `ls -a` - lists the hidden files. 
-`ls /mnt/c` - Windows C drive.
-`ls /mnt/d` - Windows D drive.

## Gotchas 
- Commands and arguments need space between them (`cd ~` not `cd~`).
- Relative paths start from where I am. Absolute paths start with `/`.



# Chapter 2 notes 
## More Commands 
- `ls -l` - long format 
- `ls -la` - long format + hidden files. 
- `ls-lh` - long format with human readable values.
- `ls -lt` - newest file first. 
- `ls -ld ~/aws-prep` - details of the folder itself and what's in it.
- `file` - shows the actual contents ie ASCII. 
- `less ~/(file)` - reads files safely. Using /word to search, N to jump to the next match, G goes to the start or end, Space or B goes to the next page and Q quits.

## System Tour 
- `ls /etc` - shows configuration files.
- `less /etc/os-release` - shows the version of Linux you're on.
- `ls /var/log` - system logs. 
- `ls /home` - every user's home files.
- `ls /tmp` - temp files that are cleared on reboot.
- `ls /usr/bin` - most of the program you run.