#Tutorial for git

##Creating a new folder to push to github
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


3. This adds all the file that you want to commit. Replace . with the respective file name like "hello.c" if you only want to add that file
```
git add .
```
