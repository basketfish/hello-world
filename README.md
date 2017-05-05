# hello-world
Yukai Tseng

Download : https://git-scm.com/download/win
Github tutorial video: https://www.youtube.com/watch?v=HVsySz-h9r4

ls -la
git --version
touch .gitignore   =>    can add a ignore fill

git init => track
rm -rf .git  => remove track

git status

git add .gitignore => put .gitignore file to staging area
---------------------------------------------------------------------------
git add -A  => put all files to staging area
git reset .gitignore => put .gitignore file to untrack (case sensitive)
git reset => remove everything
----------------------------------------------------------------------------
git commit -m "<YOUR_COMMENTS_ON_COMMIT>" => "" the message is important, 				you want to be as detail as possible.
git log 
git clone <url> <where to clone> => git clone https://github.com/../me.git .
				    the last dot means current directory
cd .. => go back to upper directory

rm -rf .* && git clone ssh://user@host.com/home/user/private/repos/project_hub.git .

git remote -v
git branch -a => list all the branch in the repository.
---------------------------------------------------------------------------
git pull origin master
git push origin master

git diff => show me the changes

----------------------
https://help.github.com/articles/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent/

---------------
git branch <name> => create a branch
git branch => list all the local branches
git checkout <name> => working on the branch
-----
git push -u origin <name of branch> => push branch to remote
git branch -a
-----------
git check out master
git branch --merged
git merge <name of branch>
git push origin master
-------------
git branch -d <branch name>
git branch -a => check branch
git push origin --delete <branch> => delete remote branch

-----------
work flow

git branch <branch name>
git checkout <branch name>
git status
git add -A
git commit -m "comment"
git push -u origin <branch name>
git checkout master
git pull origin master
git merge <branch name>
git push origin master


