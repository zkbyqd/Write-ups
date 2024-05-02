# Bandit: Level 11 -> 12

![image](https://github.com/zkbyqd/Write-ups/assets/90260119/17f02d22-212e-455d-8982-3a640729c2e0)

```
ssh bandit11@bandit.labs.overthewire.org -p 2220
```

- Enter Password:
```
6zPeziLdR2RKNdNYFNb6nVCKzphlXHBM
```

```
ls
```

```
cat data.txt | tr 'A-Za-z' 'N-ZA-Mn-za-m'
```

> tr 'A-Za-z' 'N-ZA-Mn-za-m': used to translate the first set of characters ‘A-Za-z’ to ‘N-ZA-Mn-za-m’ which is a rotation of 13 positions of the first set.

![image](https://github.com/zkbyqd/Write-ups/assets/90260119/7a5ab115-7330-4c2f-b03f-dabee8ae30ee)

> JVNBBFSmZwKKOP0XbFXOoW8chDz5yVRv

```
exit
```
