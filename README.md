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


