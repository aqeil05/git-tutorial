# Tutorial for git

## Creating a new folder to push to github
1. Create a new folder
2. Inside the CLI, inside the directory of the folder
```
git init
```

3. Create new repository in github. Copy the link
4. Inside the CLI,
```
git remote add origin (link here)
```
5. Check with
```
git remote -v
```
6. Push to github
```
git push -u origin main

git push (Once you put -u initially)
```

## Changes to files
1. Make any changes

2. Check status of which files have changes
```
git status
```
3. This adds all the file that you want to commit. Replace . with the respective file name like "hello.c" if you only want to add that file
```
git add .

git add "hello.c" "helloworld.c"
```

4. Commit the changes locally on your computer
```
git commit -m "(your description of changes here)"
```

5. Push the changes to GitHub
```
git push
```

## Branching
1. Check whether there are branches
```
git branch
```

2. Create a new branch. -b to create new branch
```
git checkout -b feature-readme-instruction
```

### Example of branching
- Hello. This is a demo of branching

3. Commit your changes
```
git status

git add .

git commit -m "(description)"
```

4. Push to github as its own branch. 
```
git push -u origin (name of branch) 

git push
```
Initially use option 1, subsequently can use option 2

5. Send pull request through github.

This does not change the code locally on your computer. Only on github

6. Change code locally on computer
```
git pull

git pull -u origin main
```
Use option 1 unless you did not set upstream option in step 4

testing for conflict
