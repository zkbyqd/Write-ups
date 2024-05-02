# Bandit: Level 10 -> 11

![image](https://github.com/zkbyqd/Write-ups/assets/90260119/f83f3e6d-a59a-4612-9e1c-a07273ffa119)

```
ssh bandit10@bandit.labs.overthewire.org -p 2220
```

- Enter Password:
```
G7w8LIi6J3kTb8A7j9LgrywtEUlyyp6s
```

```
ls
```

```
cat data.txt
```

![image](https://github.com/zkbyqd/Write-ups/assets/90260119/39a51196-ade7-4d90-8496-c8c2375e02ef)

```
cat data.txt | base64 -d
```

> cat data.txt | base64 -d: reads the data.txt and redirect the output to the base64 command. The -d argument is used to decode the string.

![image](https://github.com/zkbyqd/Write-ups/assets/90260119/c77c5f7b-72b3-4aba-bbdc-41e3c0f18416)

> 6zPeziLdR2RKNdNYFNb6nVCKzphlXHBM

```
exit
```
