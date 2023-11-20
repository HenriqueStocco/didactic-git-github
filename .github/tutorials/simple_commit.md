# Basic __*GIT*__ commands to make you __*HAPPY*__

### MAIN COMMANDS :

#### Description :

When creating a new project, you will follow the commands in this list.

*PS : This is for __NEW PROJECTS__.*

*secondPS : These commands are explained at the end of this file.*


```bash
$ git config --global user.name '<your_name>'

$ git config --global user.email '<your_email>'

$ git clone '<https://github.com/repo>'

$ git init

$ git remote add origin '<https://github.com/your_repo>'

$ git branch -M main

$ git add '<folder/file/.>'

$ git commit -m '<message>'

$ git push -u origin '<branch>'

$ git pull
```

---

### EXPLANATION OF COMMANDS

*PS : It may be that explanation in not __"THE RIGHT AND/OR CORRECT EXPLANATION"__, but it is a way of thinking and understanding to make it easier to understand.*

---

#### LET'S GET STARTED

__User settings__ :

```command
git config --global user.name
git config --global user.email
```

This command defines your name and e-mail address in general. So every time you create a new project and type *`git init`* into the terminal, a hidden *`.git`* folder will be created with these settings and it will say that it's you and/or you machine.

---

__CLONING PROJECTS__ :

```command
git clone
```

This command simply copies a project to your machine, like a printer makes a copy of something that already exists.

---

__STARTING GIT__ :

```command
git init
```
Git init, starts in your project, creating a hidden *`.git`* folder, as mentioned above, with your information among other things.

---

__REMOTE__ :

```command
git remote add origin
```
Remote points for connecting to your `GitHub` repository, like a water pipe connected to a tap to create a flow of water. In this case, the flow of water is the files, folders and everything you send there.

---

__BRANCH__ :

```command
git branch -M main
```
Imagine you're writing a book, and you want to try out a new idea without messing up the main story. What do you do? You create a copy of the main story to play around with. This copy is like a branch.
The *`main`* is a convention for the name of the main branch of the project.

---

__GIT ADD__ :

```command
git add
```
The *`add`* is as way of adding your files and sending updates to your repository.

---

__COMMIT__ :
```command
git commit -m 'message'
```

*`commit`* is a kind of short, snappy explanation about uploading or updating a file in your project, similiar to a summary.

---

__PUSHING__ :

```command
git push -u origin main
```
Making a *`push`* is similar to sending a post to your friend on social media. You receive a post, select a friend em send it. In push, you select where you want to send, is this case *`git remote`*, as mentioned above, alredy does this for you, and sends your update or new files, folders etc.
Dont't worry about *`-u`*, as it's not important at the moment, but *`origin main`* means that you're sending to the branch defined above such as *`main`*.

---

__PULLING__ :

```command
git pull
```

Making a *`pull`* basically means synchronizing the project on your machine with it's repository on `GitHub`. Your repository will say to you: "Hey, is this the same project that's on your machine?". If you aswering: "YUP!", it will say: "Great, we're synchronized!". Otherwise: "Not so good, something's missing!".

---

### UPDATING THE SAME PROJECT

All explained, so that you can make an update to your project, if you've followed all the steps mentioned above, you won't neet to do all the steps again, just the ones below:

```bash
$ git add .

$ git commit -m '<message>'

$ git push

$ git pull
```