# Git tutorial

To check Git version and installation of the git 

```git --version```

Config your Github username and email

```git config --global user.name "your name here"```

```git config --global user.email "your email"```

To check your name and email detail

```git config --global user.name ```

```git config --global user.email```

To edit on your current config

```git config --global --edit```

--> how to make directory

```mkdir <dir name> ```

--> how to change the directory  

```cd filename/```

--> To intialise a git repo

``` git init```

--> To the list of hidden files and created file 

```ls```

```ls -a #show hidden file```   

--> To track the changes in your git repo

```git status```

# Staging Area

--> To add a single file 

```git add <file name>```

--> To add all file

```git add .```

# For commit

 --> To commit added file

```git commit -m "initial command"```

--> To check number of commit

```git log```

--> To check out your commit at any particular number of commit
for this you need your hash code(to get hashcode run git log command)

```git checkout <Hashcode>```

--> To again visit last commit

```git checkout master```

--> To check your branch

```git branch```

--> How to make branch 

```git branch <branch name>```

-->To create and checkout branch at a time 

```git checkout -b adarsh/add```

--> To merge different branch

`git merge adarsh/add`

 # To ignore some file which you don't want to add in your github repo

--> first make a file 

`touch .gitignore`

type the name of that file which you want to ignore gitignore file

--> To ignore the whole folder at a time 

let say we made a folder(secretkey), (help) and want to ignore both the file then we can do ```secretkey/help```










