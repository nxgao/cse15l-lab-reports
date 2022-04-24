# CSE15L Week 4 Lab Report
This is the Lab Report for Week 4 of CSE15L, due on the 24th of April, 2022. In this lab we were debugging and improving a program, by making a total of 3 changes to it.

## First Change

First you need to download VScode, which I already did. Its a simple download, you just got to go [here](https://code.visualstudio.com/), follow the instructions and download it from there. Then, if you have Windows, you must then go this [link](https://docs.microsoft.com/en-us/windows-server/administration/openssh/openssh_install_firstuse), to find out how to Install OpenSSH. However, if you have a Mac then you already have SSH and can move on.

<img width="1440" alt="Screen Shot 2022-04-10 at 12 31 30 AM" src="https://user-images.githubusercontent.com/103228539/162650954-6a3c4f5b-00e8-4022-8ca5-9c178ec621f3.png">

## Second Change

The next step is then connecting to a remote host. First you need to open your terminal(Terminal → New Terminal menu option) in VScode and type in "```ssh cs15lsp22zz@ieng6.ucsd.edu```," of which the "```zz```" part will be different for everybody. If this is your first time then a message will pop up saying "```Are you sure you want to continue connecting (yes/no/[fingerprint])?```" and just type in "```yes```." Then type in your UCSD student login password(You will not be able to see it getting typed in for security reasons). Then you are logged in remotly to another computer.

<img width="1440" alt="Screen Shot 2022-04-10 at 12 33 57 AM" src="https://user-images.githubusercontent.com/103228539/162651118-fd1aae1f-0d6a-4cce-ba72-2789d5c0c7ff.png">

## Third Change

Next we're going to try some command options available to us. The most basic ones are:

● ```cd```: moves you to your home directory

● ```cd ~```: moves you to the directory specified, such as "cd Documents"

● ```ls```: lists the files in the current directory

● ```ls -a```: lists all files, including those normally invisible in UNIX

● ```ls -lat```: lists all files and information of those files

● ```mkdir```: it creates a new subdirectory named new_dir

● ```exit```: to reutnr back to your computer

<img width="1440" alt="Screen Shot 2022-04-10 at 12 37 24 AM" src="https://user-images.githubusercontent.com/103228539/162651250-f121e6e7-52e8-4a9e-b90c-bdb1d4aa36fc.png">


## Conclusion

This then concluded our 3rd CSE15L lab on the process and significance there was on debugging. It really was us a look in to the tediousness and length of time needed into getting a program to work.
