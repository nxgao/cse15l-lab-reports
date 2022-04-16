# CSE15L Week 2 Lab Report
This is the Lab Report for Week 2 of CSE15L, due on the 10th of April, 2022. In this lab we utlilized ssh's for the first time.

## Installing VScode

First you need to download VScode, which I already did. Its a simple download, you just got to go to https://code.visualstudio.com/, follow the instructions and download it from there. Then, if you have Windows, you must go to https://docs.microsoft.com/en-us/windows-server/administration/openssh/openssh_install_firstuse, to find out how to Install OpenSSH. However, if you have a Mac then you already have SSH and can move on.

<img width="1440" alt="Screen Shot 2022-04-10 at 12 31 30 AM" src="https://user-images.githubusercontent.com/103228539/162650954-6a3c4f5b-00e8-4022-8ca5-9c178ec621f3.png">

## Remotely Connecting

The next step is then connecting to a remote host. First you need to open your terminal(Terminal → New Terminal menu option) in VScode and type in "ssh cs15lsp22zz@ieng6.ucsd.edu," of which the "zz" part will be different for everybody. If this is your first time then a message will pop up saying "Are you sure you want to continue connecting (yes/no/[fingerprint])?" and just type in "yes." Then type in your UCSD student login password(You will not be able to see it getting typed in for security reasons). Then you are logged in remotly to another computer.

<img width="1440" alt="Screen Shot 2022-04-10 at 12 33 57 AM" src="https://user-images.githubusercontent.com/103228539/162651118-fd1aae1f-0d6a-4cce-ba72-2789d5c0c7ff.png">

## Trying Some Commands

Next we're going to try some command options available to us. The most basic ones are:

● cd: moves you to your home directory

● cd ~: moves you to the directory specified, such as "cd Documents"

● ls: lists the files in the current directory

● ls -a: lists all files, including those normally invisible in UNIX

● ls -lat: lists all files and information of those files

● mkdir: it creates a new subdirectory named new_dir

● exit: to reutnr back to your computer

<img width="1440" alt="Screen Shot 2022-04-10 at 12 37 24 AM" src="https://user-images.githubusercontent.com/103228539/162651250-f121e6e7-52e8-4a9e-b90c-bdb1d4aa36fc.png">

## Moving Files with scp

Lets say we're trying to move the file "WhereAmI.java." What we are going to do is exit the remote control back into your computer, then type in the terminal "scp WhereAmI.java cs15lsp22zz@ieng6.ucsd.edu:~/." This will then require you to type in your login password again. Once you do that, login in to ssh again, and if you do ls -lat, you can see the file there and date of transfer. 

<img width="1440" alt="Screen Shot 2022-04-10 at 4 44 56 PM" src="https://user-images.githubusercontent.com/103228539/162650786-b879680c-7f19-4cda-9ca4-fd8947b6cf50.png">

## Setting an SSH Key

If your trying to same some time, then setting an SSH key will null the requirement of entering in the password everytime. First go back to your computer, then type in "ssh-keygen" in the terminal. The statement "Enter file in which to save the key (/Users/<user-name>/.ssh/id_rsa):" will appear, in which then just copy the text within the parentheses and paste it into the terminal and press enter. Then when it says "Enter passphrase," just press enter both times. After that it will pop up some text, and now the next time to hwn you try to connect to ssh, it will not require the password.

<img width="1440" alt="Screen Shot 2022-04-10 at 2 47 02 PM" src="https://user-images.githubusercontent.com/103228539/162651266-8149ab12-5b57-49f2-bd7f-23b60e9ce6ab.png">
  
## Optimizing Remote Running

However, we can still optimize the running time even further with these methods. First we can type in ssh cs15lsp22zz@ieng6.ucsd.edu " " with any command like "ls" within the quotation marks(if you have the SSH hey set up you won't have to write the password). Which then it will do the instucted command, while still staying on your computer. You can also put ";" inbetween commands to do then all at once: "javac WhereAmI.java;java WhereAmI."
  
<img width="1440" alt="Screen Shot 2022-04-10 at 7 37 55 PM" src="https://user-images.githubusercontent.com/103228539/162655873-58ea20dd-11cc-4d31-b25c-a35696ad4754.png">

## Conclusion

This then concluded our first CSE15L lab on SSH's and how they are opmtimized.
