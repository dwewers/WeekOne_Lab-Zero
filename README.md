# WeekOne_Lab-Zero Diary

Daniel Ewers 25/02/2020

Code for personal repository [Lab Zero]:

git checkoout -b dev 
 git checkout -b bugFix
  git add .
   git commit -m "[insert text]"
    git push origin bugFix

git checkout dev
 git merge bugFix
  git commit -m "[insert text]"
   git push origin dev

git checkout master
 git merge dev
  git commit -m "[insert text]"
   git push origin master

(------------------------)

Code for group task:

cd .\NewTeamShinn\
 git pull 
  git checkout a
   git add .
    git commit -m "[insert text]'
     git push origin a

The first thing that we covered was how to clone a new repository and place it into our workspaace outside of the other repositories. We have also learned how to open the repository in a new tab on its own using code . This means we can work in that repository without getting mixed up with the other repositories or cloning to the wrong one ect. this was useful as it meant that when we are dealing with larger codes or group projects, the risk of making a big mistake is reduced and we can focus on the individual areas of the area that we are working on. We then learned how to insert text like this using 'git commit -m [insert text here]'


What have I learnt?
I learned the process in which we create a repository in which we can use as a group and develop it as in a group. This is by cloning the master repository from git hub and putting it into Visual studio. We were then able to work on it through there. We also learned that it is important to plan with the group first and discuss how we are going to develop it and talk eachother through the processes so that someoneone didnt get ahead and we were all on the same page.

Why have i learned this?
I believe I we learned this as it is very useful when working as a team on a project. In doing this task, we got an understanding of how important it is that we work together as a team and go with the slowest person and comunicate with eachother in order to avoid mistakes or getting ahead of eachother. By taking it slowly we were able to make sure that things were done in the correc order which avoided hickups.

How have Learned this?
Through prior knowledge of creating repositories and the help of putting our knowledge together to get the final product.
There were a few issues along the way in achieving this such as an error that we were getting when we were trying to push the origin
which in our case was "git push origin a."

The error we were getting was "fatal: unable to access 'https://github.com/shinn-krammerIT/TeamShinn.git/': The requested URL returned error: 403"

We were able to resolve this issue by finding a collaboration feature in the settings, and inviting each member to the group. In doing this we were then able to all contribute to the process and push our section of code to github and update the branch.



