# Bandit: Level 6 -> 7

![image](https://github.com/zkbyqd/Write-ups/assets/90260119/6df34705-335e-4c52-988b-14240866c341)

```
ssh bandit6@bandit.labs.overthewire.org -p 2220
```

- Enter Password:
```
P4L4vucdmLnm8I7Vl7jG1ApGSfjYKqJU
```

```
find / -type f -user bandit7 -group bandit6 -size 33c 2>/dev/null
```

> find: searches for files. \
> /: starting from the root directory. \
> type f: in the entire filesystem. \
> user bandit7: owned by the user bandit7. \
> group bandit6: belonging to the group bandit6. \
> size 33c: having a size of exactly 33 bytes. \
> 2>/dev/null: redirecting error messages to /dev/null, which essentially discards any error messages that might occur during the search. \
> This can be useful to avoid cluttering the output with permission-denied messages for directories where the user running the command doesn't have access.

![image](https://github.com/zkbyqd/Write-ups/assets/90260119/843dac82-65f6-481a-80b4-f99d2ee35bd4)

```
cat /var/lib/dpkg/info/bandit7.password
```

![image](https://github.com/zkbyqd/Write-ups/assets/90260119/c7383a4e-881a-4835-b375-66af89fd2f4b)

> z7WtoNQU2XfjmMtWA8u5rN4vzqu4v99S

```
exit
```
