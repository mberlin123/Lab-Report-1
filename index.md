# How to Login to ieng6

## Step 1: Installing VSCode
VSCode is a program and code editor that can be used to create and edit programs both locally and on a server. It can be installed from it's [website](https://code.visualstudio.com/). After installing, open the program. It should look like this: ![Image](Screenshot 2023-01-16 205810.png)

## Step 2: Connecting remotely to ieng6
You can connect to UCSD servers for CSE 15L remotely through a program called ssh in the command window. Open the command window by clicking View -> Terminal in the top bar. You can remotely connect through ssh to UCSD servers using the following command:
```
ssh cs15lwi23[XX]@ieng6.ucsd.edu
``` 
[XX] should be replaced with the unique letters for your username. After entering this command, you will be prompted for your password. If you successfully login, you should see this window:
![Image](Screenshot 2023-01-16 205737.png)

## Step 3: Trying some commands
You can try some commands to move around the filesystem in the server you have connected to:

pwd : prints the directory you are currently in
ls : lists the files in the directory you are currently in
cd folder: move to a sub directory called folder (or a parent directory using cd ..)
mkdir fileName : make a new directory called fileName
cat fileName : prints the contents of a file called filename

Here are some examples of what commands should look like and do in ssh:
![Image](Screenshot 2023-01-16 205830.png)

## Conclusion

In conclusion, connecting to a server through VSCode and ssh is both convienent and useful! Have fun and explore what you can do!
 
 
