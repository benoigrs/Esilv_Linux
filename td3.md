# Td3
## Exercice 2
#### 2
```
cat cyberattacks.txt | grep meta
```
#### 3
```
cat cyberattacks.txt | grep -oP "meta\s\w+"
```
#### 4
```
cat cyberattacks.txt | grep -oP "(?<=meta\s)\w+"
```
#### 6 
```
cat cyberattacks.txt | grep -oP "(?<=<title>).*(?=</title>)"
cat cyberattacks.txt | grep -oP '(?<=mw-headline" id=").*?(?=</span>)' | head -n -2
```

penser à sauvegarder
