# Hello, that's a guide for dummies made by dummy
## 1. Today we are going to learn some basic stuff with Markdown using Git

![Git image](https://upload.wikimedia.org/wikipedia/commons/thumb/e/e0/Git-logo.svg/1280px-Git-logo.svg.png)


There are some basic commands to learn, but first things first - some motivational stuff:

># Great citation here
> Someone once said that it's important to learn day by day to improve yourself each day since we are limited in time during this life
>
> *- Someone important*

You can create a file manually using regular **Explorer** of your operational system, or you can do it via **Visual Studio Code**, for example.
Now you can work with **Terminal**


Alright, there is a couple of commands to start:
* **git init** - инизиализация git в репозитории
* **git add *"file name"*** - слежение за файлом со стороны Git
* **git commit *"file name"*** - коммит (сохранение шага) в каком-то его виде
* **git status** - отслеживание текущего статуса программы git 

Important to note, that to create a commitment you have to save file beforehand.

>It may be done using ***Ctrl + S*** Keyboard shortcut

When you have created a lot of versions of your program, you can switch between them using "key", that's provided by the program itself.

If you want to switch to a previous version of the file, you can use the following command:

- **git checkout *"key"*** - возвращение к версии программы с соответствующим "ключом"

Today i learned to use **Markdown** to create something-something. This small manual was prepared using the following guide:

[Язык разметки Markdown](https://doka.guide/tools/markdown/)

## Remote repository operations

Previous material was dedicated to operations with local repository. Now we are going to talk about operations with remote repositories.

To create a remote repository one could use service [Github](https://github.com/) which allows users from all over the world to work with different remote repositories.

To establish connection with remote repository you can use the following command in the terminal:
* git remote add origin [link]

where [link] is a URL to your github profile remote repository

To actually do some changes or to update your file to the latest version, which is located in the remote repository, operator can use the following commands:
* git push - uploads your "file" to the remote repository
* git pull - "updates" your file to the version of that one in the remote repository

Before you actually start doing anything, it's better to create a README file, where you can put some instructions for any user, that would like to contribute to your file

Just in case skill level in programming in your team differs from one person to another, or there are many different programmers that you don't know (opensource projects), it's better to create your own branch in the file via the following command:
* git checkout -b [name]

It also switches branch to the one with the [name]

It's possible to quickly download remote repositories of other users via the following command:
* git clone [link]

this will create a copy of an existing remote repository in your local repository. When you are done with work in your own branch, you can push this file to the remote repository (after saving, comitting, e.t.c)

You can also request an upload of your file to the remote repository via the following command:
* git push --set-upstream origin [branch name]

and then request a pull into remete repository

I guess that's it
