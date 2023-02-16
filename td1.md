# TD1

## Exo1

#### 1
``` 
cd /
``` 
#### 2
``` 
ls
``` 
#### 3
``` 
pwd
```
#### 4
``` 
mkdir test
``` 
#### 5
``` 
cd /home
``` 
#### 6
``` 
cd ~
``` 
#### 7
``` 
cd ..
``` 
#### 8
``` 
cd ..
``` 
#### 9
``` 
cd
``` 
#### 10
``` 
mkdir test
``` 
#### 11
``` 
cd test
``` 
#### 12
``` 
pwd
``` 

## Exo 2

#### 1
```
cd ~
```
#### 2
```
pwd
```
#### 3
```
mkdir linux_ex_1
```
#### 4
```
cd linux_ex_1
```
#### 5
```
touch benoit_gras.txt
```
#### 6
```
mkdir notes
```
#### 7
```
mv benoit_gras.txt notes/
```
#### 8
```
mv benoit_gras.txt benoit_gras_2023.txt
```
#### 9
```
cp -r notes notes_2023
```
#### 10
```
rm -rv notes
```

## Exo 3

#### 1
```
touch script1.sh
```
#### 2
```
nano script1.sh 

->Echo "Script running please wait...
->Echo "Done!"
```
#### 4
```
cat script1.sh
```
#### 5
```
chmod +x script1.sh
./script1.sh
```
## Exo 4
### Exo4.1
#### 1
```
touch credentials.txt
nano credentials.txt
cat credentials.txt
ls -la credentials.txt
```
#### 2
```
chmod a=r credentials.txt
ls -la crendentials.txt
nano credentials.txt
cat credentials.txt
```
#### 3
```
chmod a=wr credentials.txt
ls -la credentials.txt
nano credentials.txt
cat credentials.txt
```
#### Others
```
#add executable to owner
chmod u+x credentials.txt

#remove read permission for others
chmod go-r credentials.txt

#change to rwx for all
chmod 777 credentials.txt
```

### Exo 4.2
#### 1
```
cd /
```
#### 2
```
sudo touch .private_file
sudo nano .private_file
cat .private_file
ls -la
```
#### 3
```
nano .private_file
"Permission denied"
cat .private_file
```
#### 4
```
sudo nano .private_file
cat .private_file
```
#### 5
```
sudo chmod 777 .private_file
nano .private_file
"permission denied"
cat .private_file
```
### Exo 4.3
#### 1
```
chmod a=rw .private_file
"Operation not permitted"
```
#### 2
```
sudo chown $USER .private_file
```
#### 3
```
chmod a=rw .private_file
```






















