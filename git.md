
# Configuration
```
git config --global user.name ''
git config --global user.email ''
```

## List configrations
```
git config --list
```
# Clone & Status
For cloning a repo run this command
## 1. Clone
```
git clone [url]
```
## 2. Status
It shows the branch name with status of the code
```
git status
```

# Add & Commit

## 1. Add
    ```
    git add [fileName]
    ```
## 2. Commit
    ```
    git commit -m "meaningful message"
    ```

## 3. Push

push changes to main branch
```
git push origin main
```
# Upload already create project to github
1. Run following command in project folder to initialize it as git repo
```
git init
```
2. Create a repo at github
3. Copy the link of repo and run
    ```
    git remote add origin [link]
    ```
4. Check the branch
    ```
    git branch
    ```
5. Rename the current branch
    ```
    git branch -M main
    ```

6. Push the code to main branch
```
git push origin main
```
Note - If we we don't want to write origin main with every push we can use '-u' flag
```
git push -u origin main
```

Next Time we can use
```
git push
```
## Init Command
used to initialize git repo
