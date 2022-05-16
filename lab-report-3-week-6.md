# CSE15L Week 6 Lab Report
This is the Lab Report for Week 4 of CSE15L, due on the 8th of May, 2022. In this lab we were Streamlining ssh Configuration, Setup Github Access from ieng6, and Copy whole directories with scp -r


## Streamlining ssh Configuration

We first opened our terminal where we typed ```cd .ssh``` to go into our ```.ssh```  files. We then used the ```vim```command to make a new file called ```"config"``` where we typed in our ssh username and host.

<img width="249" alt="Screen Shot 2022-05-06 at 7 13 18 AM" src="https://user-images.githubusercontent.com/103228539/167195635-ba860551-6473-4493-8d1b-7be9b8946faf.png">

We saved and exited the new file. At that point, all we needed to do was type in ```"ssh ieng6"``` into the command line, and it automatically connects us to the other server.

<img width="681" alt="Screen Shot 2022-05-05 at 8 16 49 PM" src="https://user-images.githubusercontent.com/103228539/167195651-ed2671f0-afda-46a5-895a-3707062ef651.png">

## Setup Github Access from ieng6

First we needed to get our ssh public key. So in order to do that you first while in your ```ieng6```, type in ```cd .ssh``` and then ```ls.``` If any of the files named: ```id_rsa.pub, id_ecdsa.pub, id_ed25519.pub``` are there; then just type ```pbcopy<~/.ssh/(filename)``` to copy it. Mine was ```pbcopy<~/.ssh/id_rsa.pub```. Note that the ones with ```.pub``` are the public SSH keys.

<img width="1015" alt="Screen Shot 2022-05-06 at 1 50 26 PM" src="https://user-images.githubusercontent.com/103228539/167214735-04bd5172-33bd-43ce-b5e4-f7ad4fdc7278.png">

If you don't have these files then you have to make them by typing ```ssh-keygen -t ed25519 -C (your github e-mail)```, where it will prop up "```Enter a file in which to save the key (/Users/you/.ssh/id_rsa):```", then typing in the name of what you want the file to be, don't input anything when it asks for a passphrase(just press enter). Then you shold have 2 files named after what you inputed, one private and one public SSH Key, with the public one haveing the ```.pub``` at the end.

Then in your Github, click on your top right profile picture and then click on settings. In your settings go to your "SSH and GPG keys" tab on the left, and click on the green "New SSH key" button. It will then ask you for the title(which can be anything), and the actual key itself, which is the thing you just copied. 

<img width="1440" alt="Screen Shot 2022-05-06 at 11 09 12 AM" src="https://user-images.githubusercontent.com/103228539/167196041-e5ee7794-31db-49a5-b5ee-b75efed1e5c9.png">

Then in ```.ssh``` in your ```ieng6```, create a ```config``` file using ```vim config```, where you will create a file using this format:

<img width="331" alt="Screen Shot 2022-05-14 at 11 54 18 AM" src="https://user-images.githubusercontent.com/103228539/168501125-aaf78b99-b35f-40dc-9942-c813142bb41c.png">

Now we can finally edit a file. Go to your repository, and type in ```vim (filename)``` to access and make changes to the file. After you make the edit and save, type in ```git commit -a -m "(summary of what you did to the file)"``` and then ```git push origin main```. 

<img width="1440" alt="Screen Shot 2022-05-12 at 6 17 02 PM" src="https://user-images.githubusercontent.com/103228539/168408179-35e3fe12-361b-4110-8b78-80b2a041eefc.png">

(This is the added commit)[https://github.com/nxgao/markdown-parser-main/blob/main/Added_Commit]

## Copy whole directories with scp -r

While in your own computer's command line, type in ```scp -r . cs15lsp22zz@ieng6.ucsd.edu:~/markdown-parser-main```, where it will copy the files.

<img width="1440" alt="Screen Shot 2022-05-12 at 6 19 15 PM" src="https://user-images.githubusercontent.com/103228539/168408174-c1fc56f9-5a8f-4a75-beb7-76daffd35cbe.png">

## Conclusion

This then concluded our 5rd CSE15L lab on Streamlining ssh Configuration, Setup Github Access from ieng6, and Copy whole directories with scp -r.
