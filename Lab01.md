## Lab 01

- Name: Devin Shepherd 
- Email: shepherd.112@wright.edu

## Part 1 Answers

1. mkdir DirA
2. mkdir Dir B
3. Use cd to go into Dir B
4. pwd, will allow you to change directory by saying RENAME.
5. mv DirB

## Part 2 Answers

1. touch test.txt
2. File contents:
 
```
Joe Burrow, Trey Hendrickson, Zac Taylor
```

## Part 3 Answers

1. cp DirA .hiddentext.txt
2. mv .hiddentext.txt DirA

## Part 4 Answers

1. sudo adduser bob
2. Use cd to return to bob's home directory
3. Yes, bob is not the root account. The root account has all access to information. 
4. su bob
5. pwd bob
6. Yes, because bob is the root owner of the directoy.
7. su root
8. exit 

## Part 5 Answers

1. sudo addgroup crew
2. usermod -aG sudo bob
3. sudo chown DirA
4. sudo su bob 
5. touch file.txt
6. Because bob is a user in DirA

## Part 6 Answers

1. sudo touch sudowho.txt
2. Read and Write 
3. Added text into sudowho.txt without changing any permissions 

## Extra Credit

1. sudo touch mydiary.txt
2. Add the new user sally into the directory to allow her to edit the file. This will give permission without adujusting the permission. 
3. bob would also need to be added into the directory to allow him to edit the file. 
