In this file I learnt how to use github with push, pull and editting my current files.
first step is to make a ssh key{
1: go to your github accound setting -> ssh and gdp -> new ssh key -> title: what ever you like to recognize it later -> key: copy paste from your terminal where you created.*

*: first open your terminal on your local host-> run code ls -al ~/.ssh to check if you have any active ssh -> if you don't have any, run this code to generate a ssh "ssh-keygen -t rsa -b 4096 -C "your_email@example.com" -> add new ssh by "eval "$(ssh-agent -s)" ssh-add ~/.ssh/id_rsa -> then write "cat ~/.ssh/id_rsa.pub" to check your public key for key part on step 1.

ssh-add ~/.ssh/id_rsa
to connect your terminal with your github account first is type git clone < your repository https from your code section> and enter 
to create a file use touch like: touch hello.html
git add < your file name>
git commit -m "message to show what you have modified"
git status
git push
