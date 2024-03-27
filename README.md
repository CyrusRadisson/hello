In this file I learnt how to use github with push, pull and editting my current files.
first step is to make a ssh key{IF YOU DON'T HAVE ONE:
1: go to your github accound setting -> ssh and gdp -> new ssh key -> title: what ever you like to recognize it later -> key: copy paste from your terminal where you created.*

*: first open your terminal on your local host-> run code ls -al ~/.ssh to check if you have any active ssh -> if you don't have any, run this code to generate a ssh "ssh-keygen -t rsa -b 4096 -C "your_email@example.com" -> add new ssh by "eval "$(ssh-agent -s)" ssh-add ~/.ssh/id_rsa -> then write "cat ~/.ssh/id_rsa.pub" to check your public key for key part on step 1.

IF you have ssh just run your terminal and type "git clone <and your github repository ssh lin>" and then you should run git pull to download readme file and then use git add <name of your file wanna push> -> git commit -m "Your message" -> git push and DONE.

TO create a file you should write touch <name of your file>

git status is for to get the location of your current index file you are working on.
git push is to update your file from your local system to your github
git pull is to download your github file from github to your system.
