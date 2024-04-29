In this file I learnt how to use github with push, pull and editting my current files.
first step is to make a ssh key{IF YOU DON'T HAVE ONE:
1: go to your github accound setting -> ssh and gdp -> new ssh key -> title: what ever you like to recognize it later -> key: copy paste from your terminal where you created.*

*: first open your terminal on your local host-> run code ls -al ~/.ssh to check if you have any active ssh -> if you don't have any, run this code to generate a ssh "ssh-keygen -t rsa -b 4096 -C "your_email@example.com" -> add new ssh by "eval "$(ssh-agent -s)" ssh-add ~/.ssh/id_rsa -> then write "cat ~/.ssh/id_rsa.pub" to check your public key for key part on step 1.

IF you have ssh just run your terminal and type "git clone <git@github.com:yourusername>" and then you should run git pull to download readme file and then use git add <name of your file wanna push> -> git commit -m "Your message" -> git push and DONE.

TO create a file you should write touch <name of your file>

git status is for to get the location of your current index file you are working on.
git push is to update your file from your local system to your github
git pull is to download your github file from github to your system.

git checkout -b "name" : it will make new branch in your repository.-> you use different branches for a file because many people maybe wanna adjust it so they can use the new branch and at the end merge to the main branch and modify the changes.

git branch: it shows in which branch you are.
git checkout main: it will direct you to the main branch user
git merge style: here style is my branch name which i wanna merge the file to the main branch.

TO DELETE A FILE FROM YOUR GITHUB REPOSRITIRY{
{1:git rm --cache <name of the file> it will remove the file from your github repository, but not from your filesystem.
  2: git commit -m "your comment like remove the name of the file"
  3: git push <name of the branch> : for me is git push main
  }
  
