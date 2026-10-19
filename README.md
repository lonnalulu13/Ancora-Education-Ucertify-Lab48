# Ancora-Education-Ucertify-Lab48
# Managing Files Using the Command Line

> **Original Lab Source**
> 
> This lab was available through:
>
> [https://ancoraeducation.ucertify.com/app/?func=navigate_items&item_sequence=1]

## Objective of the Lab 
In this lab, you will learn to manage files using the command line. You can modify your directory and files using the command touch data/passwd, which can be used to update the timestamp of the data/passwd file to the current date and time. 
## Instructions 
### STEP 1 
From the left sidebar, open the Terminal () icon. 
### STEP 2 
Execute the following command to display your current directory:
```bash
pwd
```
### STEP 3
Execute the following command to switch to the /etc directory:
```bash
cd /etc
```
### STEP 4
Execute the following command to move to the /etc/skel directory:
```bash
cd skel
```
### STEP 5
Execute the following command to move up one directory:
```bash
cd ..
```
### STEP 6
Execute the following command to list the files in the current directory:
```bash
ls
```
### STEP 7
Execute the following command to perform a "long display" listing of the files in the current directory:
```bash
ls -l
```
### STEP 8
Execute the following command to list all the files in the current directory that begin with the letter d:
```bash
ls d*
```
### STEP 9
Execute the following command to determine the type of contents in the /etc/group file:
```bash
file /etc/group
```
### STEP 10
Execute the following command to display only the last five lines of the /etc/group file:
```bash
tail -n 5 /etc/group
```
### STEP 11
Execute the following command to make a directory named data in the current directory:
```bash
mkdir data
```
### STEP 12
Execute the following command to copy the /etc/passwd file into the data directory:
```bash
cp /etc/passwd data
```
### STEP 13
Execute the following command to copy the /etc/ppp directory into the current directory:
```bash
cp -r /etc/ppp dest
```
### STEP 14
Execute the following command to rename the ppp directory that is located in the current directory to peers:
```bash
mv ppp peers
```
### STEP 15
Execute the following to update the timestamp of the data/passwd file to the current date and time:
```bash
touch data/passwd
```
### STEP 16
Execute the following command to create a new empty file named test in the data directory:
```bash
touch data/test
```
### STEP 17
Execute the following command to delete the data/passwd file:
```bash
rm data/passwd
```
### STEP 18
Execute the following command to delete the peers directory:
```bash
rm -r peers
```
## Disclaimer

This repository is for **educational and personal learning purposes only**.  

The original lab content belongs to **uCertify / Ancora Education** and remains their copyrighted material.  
This repository is not affiliated with, endorsed by, or sponsored by uCertify or Ancora Education.  

No copyright infringement is intended.  
Use of any tools or techniques mentioned here should only be performed in authorized, legal environments.
