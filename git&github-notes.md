# **git notes**

```js
//after installing git check git version for confirming weather git is install or not.
  git --version

// set your user name
  git config --global user.name "your name"

//set your email
  git config --global user.email "your email"

  // check your name
  git config --global user.name

  // check your email
  git config --global user.email

  //edit user-name and password
  git config --global --edit

  //......NOTE-THAT....
  //these commands are only for first time, after installing  git in you computer.

```

<br>
<br>
<br>

# make new folder

```js
// make new folder for your project
  mkdir <yourfoldername>

  // cd to your folder
  cd <yourfoldername>


  //git init
  git init

```

**example:-**
![this is image](./images/eg-1.png)

<br>
<br>
<br>

# create file

```js
// make new file in  your project
touch <yourfoldername>

```

**example:-**![this is image](./images/eg-2.png)

<br>
<br>
<br>

# stageing area

```js
// to check the status of project
git status

// add file to stage
 git add <filename>

// add changes from all tracked and untracked files
// stage all new, modifed and deleted files
git add -A

//Stage all (new, modified, deleted) files in current folder
git add .

//update stage of  tracked files
//Stage modified and deleted files only
git add -u

```

![image](./images/eg-3.png)

<br>
<br>
<br>

# git commit

```js
// commit change file
git commit -m "your message"

//  stage and commit all change  of tracked file
git commit -a -m "your message"

// it work like
(git add -u )  +  (git commit -m "your message")= git commit -a -m "your message"


// list all the commit until now
git log
```

<br>
<br>
<br>

# git branch

```js
// list all branch
git branch

// create new branch
git branch <branch-name>

// switch to selected branch
git checkout <branch-name>
git switch <branch-name>

// create and switch to new branch or find out existing branch
git checkout -b <branch-name>

// create and switch to new branch
git switch -c <branch-name>

// merge branch
git merge <branch-name>

// delete local branch
git branch -d <branch-name>

// if branch contain unmarged changes,though git will refuse to delete it. so try this....
git branch -D <branch-name>

// delete remote branch
git push --delete <remote-name> <branch-name>

  example-
  git push --delete origin first-branch

```

<br>
<br>
<br>

# git push

```js
//push to remote repo like your github repo.
```

## Only perform these 4 command once at time of project setup:--

```js

1  //check connected github remote repo
git remote -v
```

```js

2  // add path of your git repo.
git remote add origin <your github repo path>
```

```js

3  //move/rename a branch, even if target exists
git branch -M master
```

```js

4  //setup up-stream
  // * means it allow you to set the default remote branch for your current local branch
git push -u origin master

```

- ## now we don't have to mantion remote branch again an again we can directly push our code to defualt remote branch by just typing following command:--

```js

  //it will directly push your code to defualt remote branch
  git push


```

<br>
<br>
<br>

---

## GIT Documentation link:-

> [for more Git related commands checkout the official GIT Documentation](https://git-scm.com/docs)

 <br>
 <br>
 <br>
  
  ---

# **For more notes check my github repositories:-**

## 1. react notes:-

> [ https://github.com/siduni/notes](https://github.com/siduni/notes)

<br><br>

## 2. node and express notes:-

> [ https://github.com/siduni/notes](https://github.com/siduni/notes)
