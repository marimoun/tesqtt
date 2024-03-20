+++
title = 'Lilo'
date = 2024-03-20T14:38:55+01:00
draft = false
+++
test
#jvjhcfhtg

## Versionning the right way
After creating and setting up a repo 
```bash
git init 
git commit --allow-empty -m "🎉 init master branch"
git remote add origin <link to gihtub new repo>
git push -u origin master
```
> till this stage the master branch is set up and ready with an empty commit
__Create & init a develop branch__
```bash
git checkout -b develop   # create a new branch called develop = création d'une branche intitulé develop
git commit --allow-empty -m "🎉 init develop branch"
git push origin develop
```
__Branch feature first__
```bash
git checkout -b feature/first
# the branch introducing the first feature is created .
# make the necessary modifications on your project
git add .   # we add all the modification , we must verify in the case of a project the .gitignore file is created .
git commit -m "feat: 🚧 add the project boilerplate" 
git push origin feature/first