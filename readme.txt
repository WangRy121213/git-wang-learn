How to use the git

1. create a new repository
2. open a command of git bash dans the repository
3. input "git init"
4. create a new file or open an old file to compile and save it
5. input "git add 'the name of file'" in command of git bush
6. input "git commit -m '(the word)'"

always remember that: first git add,second git commit
                                  
waite a minute
git status: show the status of your repository
git diff:show that whether you have changed the content of file 
************************************************************************************************************
the white word is the content that have been commit to the git
the green word is the content that have been changed but not beencommit to the git
*************************************************************************************************************
git log:
to show all the version that have been changed
the result of git log:
from up to down(latest to furthest): it's the information of every changed:the Author the date and the message
git log --pretty==online
**************************************************************************************************************
how to turn back to the last version?  
Firstly,git must to know which version it is now.
HEAD:represent the latest version
HEAD^:represent the last version
HEAD~100:represent the lasr 100 version
the method to return to the last version:
git reset --hard HEAD^
show the content of the file:
car readme.txt
**************************************************************************************************************
if you want to return to the last version
git reset --hard (id of version partly)

git reflog:to show all the command that you have used
***************************************************************************************************************
git checkout --file:
throw the changed file in workplace
***************************************************************************************************************
how to delete the file:

totlally delete:
                1.rm test.txt
                2.git rm
you want to reset:
                 git checkout --test.txt
  
***************************************************************************************************************
connect with the github:
create a new repository
git remote add origin git@github.com:michaelliao/learngit.git
git push -u origin master
***************************************************************************************************************





