# Beginner-Repo
This repository is made for the beginners to get started with git contribution

## Setup Git
- git config --global user.name "John_Doe"
- git config --global user.email "john@example.com"

## Git commands you are going to use

1. git clone url (by cloning all the files in that repo will be available to your local machine + before cloning make sure to fork the repo to your acount)
2. git add filename.txt (after changing a particular file )
3. git add . (too add everything)
4. git commit -m "message"  (it is recommended to commit with a message to tell what are the things you have changed)
5. git push (push it to the main branch now it will be available in github)
> git push origin branch_name (it will push your code from local branch to the master branch) 
e.g __git push origin devsg__ ( it will push branch devsg( local branch) to original repo's master branch , henceforth creating a PR)
6. git config --global https.proxy 172.16.102.28:8080
7. git config --global http.proxy 172.16.102.28:8080
8. git config --global --get-regexp http.*
9. git config --global --unset https.proxy
10. git config --global --unset http.proxy


## First Contribtution

- In order to contribute to this repository first fork the repo.(you can see this in the right most side of the page).This will make a local vesrion of the repository in your GitHub account. 

- ``` git clone https://github.com/user_name/Beginner-Repo ``` where **user_name** is your GitHub handle name e.g - https://github.com/pydevsg/Beginner-Repo 
- ``` cd Beginner-Repo ```
- Change from master branch to your local_branch 
```  git checkout -b local_branch ``` where **local_branch** is your local branch name and is user defined from your Git Bash.
- Add your name in the Contributor.md file as given in the [Contributors format](https://github.com/pydevsg/Beginner-Repo/edit/master/Contributor.md/#4) 
- ``` git add Contributor.md ```  
- ``` git commit -m "comment" ``` where **comment** is user defined and it can be anything meaningful from your side. e.g - git commit -m " Added my name"
- ``` git push origin local_branch ``` where **local_branch** is your local branch name and is user defined from your Git Bash.

- This will  help you in making your first PR. 
### All the best for [JGEC Winter of Code(JWoC)](https://jwoc.tech/). Keep contribtuing.:tada:
