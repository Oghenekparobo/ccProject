# kodecamp-team-athena
# kodecamp-team-athena
## These are the things you need to do to contribute to this repo.
#### The first thing you need to do is navigate to this repo with the link submitted on the slack channel.
#### After that, please follow the steps below.
---
1. **Clone the repository**; navigate to the develop branch by clicking on main and changing branch to develop. Then click on the *green* button that has **code** written in it. copy the https key [here or there](https://github.com/kodecampteam/kodecamp-team-athena.git). 
1. **Open your terminal**; In your terminal you would run the command 
```cmd
  cd *folder you want*
  git clone https://github.com/kodecampteam/kodecamp-team-athena.git
```
### After running that command, the repo would be cloned to your pc and then you then run another command to change directory into the folder and then breakout into the develop branch to show the documents on you pc, like;
```cmd
  cd kode-camp-team-athena
  git checkout develop
```
### Once you,ve done that you can do your work, write your code and plan to push. At anytime before you push you should always run the next command so that your folders are up to date;
```cmd
  git pull origin develop
```
### This is important to update what you have on your local so that it is the same as what is on the repo. After you are done coding your work and you want to push to github, you would then create your own branch using;
```cmd
git checkout -b *ft-your page name*
```
### After you do that, you then run the following command, let us imagine that for the sake of this doc your branch name is **test**, this is what you terminal command should look like;
```cmd
 git add .
 git commit -m 'Created and worked on the test page'
 git push -u origin test
 ```
 ### Once you have done that, your work is pushed to github but isn't merged to the develop branch yet. So you then create a pull request from your brnch(test or contact or whatever you named your branch) to the develop branch.


 ### You are to host your work on gitpages and submit the link alongside with the pull request so that your work can be inspected before it is merged to the develop branch.

---

## Note;
1. Please make your work responsive across all devices.
1. Minimize custom css and use more of bootstrap.
1. Everyone is to use a different custom css file and link it to their html page
1. If you aren't sure of anything please ask.


