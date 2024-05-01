# Bandit: Level 5 -> 6

![image](https://github.com/zkbyqd/Write-ups/assets/90260119/331e50fa-b42e-42de-8acd-9f3f18f94860)

- $ ssh bandit5@bandit.labs.overthewire.org -p 2220
  
- Enter Password: $ lrIWWI6bB37kxfiCQZqUdOIYfr6eEeqR
  
- $ ls
- $ cd inhere/
- $ ls

![image](https://github.com/zkbyqd/Write-ups/assets/90260119/ca4221ec-e01e-4801-b3b1-362b8bb15e3f)

- $ file */{.,}* | grep "ASCII text" | grep -v ', with very long lines'

> file */{.,}*: uses the file command to determine the type of files in the current directory and its subdirectories. The */{.,}* pattern expands to include all files and directories in the current directory and its subdirectories.
> grep "ASCII text": filters the output to include only lines that contain the text ASCII text.
> grep -v ', with very long lines': further filters the output to exclude lines that contain the text.

![image](https://github.com/zkbyqd/Write-ups/assets/90260119/202910eb-e3cd-456f-8295-ced52c66d2dc)

- $ du -b -a | grep 1033

> du -b -a: uses the du command to estimate file space usage. The options -b show sizes in bytes, and -a displays an entry for each file in the directory.
> grep 1033: filters the output to include only lines that contain the text "1033".

![image](https://github.com/zkbyqd/Write-ups/assets/90260119/27bef5d4-7465-4f7f-913a-869f8cda7a44)

- $ cat ./maybehere07/.file2

![image](https://github.com/zkbyqd/Write-ups/assets/90260119/6921e898-cb8c-41eb-aa4c-9f88ef8c8db6)

> P4L4vucdmLnm8I7Vl7jG1ApGSfjYKqJU

- $ exit
