# *Git*

How to push local repo to remote ?

## *Steps*

1. `git init` - Intializing Your local repo
2. `git add .`- To change your current local repo changes to staged
3. `git config user.name <"Your name">`
    `git config user.email <"Your email">`
> Conforming to your terminal who is the user current working 
4. `git commit -m <"Your message">`- Commiting your Repo with massage
5. `git remote add <YOUR REMOTE NAME> <Your repo URL>` 
6. `git remote -v`- To check your local repo's connection with remote had successful (or) not.
7. `git push -u <YOUR NAME> <YOUR BRANCH NAME>`- To push your local repo to remote for the **first time** while pushing a new branch , we include `-u`.

9. `git push` - To push your local repo to remote of **same working branch**

8. `git pull <YOUR REMOTE NAME> <YOUR BRANCH NAME>`- To pull your remote repo to local repo

How to add additional files to your remote repo from local which have already commit ?

## *Steps*

1. `git add .`
2. `git commit -m <"Message">`
3. `git push -u <YOUR REMOTE NAME> <YOUR BRANCH NAME>`

**4. Now you have to `pull request` in git hub and `Merge` the  new file which you had added to your repo**

**5. The files will added to repo**

6. `git log` - To check how many cmds have done on a repo.

7. `git status` - To check the repo had added to git (or) not

8. `git branch` - To check list of branches you had

9. `git branch <YOUR NEW BRANCH NAME>` - To add new branch. 

10. `git checkout`(change) - To change one branch to another

11. `git checkout -b <YOUR NEW BRANCH NAME>`- To create new branch at the same time to swith to that new branch.

12. `git fetch` - To find a particular word which u want to check.

## *How to Pull Request and Merge the repo in the git bash terminal with cmds ?*

1. `git pull <YOUR REMOTE NAME > <YOUR BRANCH NAME>` - To pull from a remote.

2. `git merge <YOUR BRANCH NAME>` - To merge a branch into current branch.

## *How to delete branches with cmd ?*

1. `git branch -d <YOUR BRANCH NAME>` - To  delete a local branch.
2. `git push <YOUR REMOTE NAME> --delete <YOUR BRANCH NAME>` - To delete a remote branch.

***
![](https://www.earthdatascience.org/images/earth-analytics/git-version-control/github-create-new-pull-request.png)
***
### *Pull Request*
***
![](https://embed-ssl.wistia.com/deliveries/02698a12184c77a2137fd9265001c2daa86d943f.jpg?image_crop_resized=640x360)

### *Merge Option*


  