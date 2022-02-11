# git-test-yo

![jambalaya](https://raw.githubusercontent.com/ivandorte/git-test-yo/master/avatar.png) 


### Test 1

**I'm learning git**

- How to configure

```
git config --global user.name mygitname
git config --global user.email mymail@com

git config --global core.editor nano
```

- [Markdown reference](https://guides.github.com/features/mastering-markdown/)

- Base commands

```
git clone repolink
```
to clone a repository


```
git clone repolink newfoldername
```
to clone a repository in a custom named folder


```
git add .
```
to track new repository files


```
git commit -a -s
```
stage a change to git repository


```
git push
```
to write changes to repository


- How to amend the latest commit

Do your changes then modify the most recent commit using amend option...
```
git commit -a -s --amend
```

...then push force:

```
git push --force
```

PS: Don't amend public commits, i.e. commit that other developers have based their work on. This is a confusing situation for developers to be in and it’s complicated to recover from.


### contribute to other repositories

Add SSH key to Github account: https://docs.github.com/en/articles/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent

```
git clone git@github.com:ivandorte/git-test-yo.git
```

```
cd TO_DIRECTORY
```

```
git checkout -b NEW_BRANCH_NAME
```

do your changes and push to origin:

```
git add .
```

```
git commit -a -s
```

```
git push origin NEW_BRANCH_NAME
```
