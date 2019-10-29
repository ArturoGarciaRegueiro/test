# Git Config
```
git config --global user.name "ArturoGarciaRegueiro"
git config --global use.email "arturogarciaregueiro@gmail.com"
```

# Git Upload
1. Create Repository in your account.
2. From terminal > Go to the folder that will be on github
3. Command lines 
```
git init # < starts git in curent folder
git add . # < adds the files in the local repository and stages them for commit
git commit -m "First Commit" # < commits the tracked changes and preparres for pushing
```
4. Get GitHub repository URL and copy in the following line:
```
git remote add origin <URL> # sets the remote
```

5. Push the changes (to master)
```
git push -u origin master
```

# Git Command Lines
```
git status # < status of our repository
```
# Git Concepts
* Status
    1. Working directory: where we read/write our files.
    2. Staging area: we choose what files are ready for next status.
    3. Repository: we commit to repository.
