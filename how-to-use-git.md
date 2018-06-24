# How to use git in a team project

# Table of Contents
- [Introduction](#introduction)
- [How to start](#how-to-start)
- [PUSH](#push)
- [PULL](#pull)
- [BRANCH](#branch)
- [PULL REQUEST](#pull-request)
- [Making our lifes easier](#making-our-lifes-easier)
- [Conflicts](#conflicts)

## Introduction
Oke, so this was something that was like magic to me. How do people use git?
Once you practised with it, its easy.
Let's go through it step-by-step

## How to start
First thing you need to do is navigate to github.com to create a new repository. This will be your workspace. Everything you upload will appear there. Next thing you will do is "clone" the project. Cloning means that you will make a "copy" on you local computer. There are two ways to clone. 

1. Use github desktop application - DON'T DO THIS
2. Use command inline - use this

I recommend using command inline, because that's way cooler and proves you have some self respect.
After opening the terminal enter ``` cd *maplocation ``` the maplocation is the place YOU want to clone the project into.
continue with ``` git clone *url ``` the url is the url you got when you clicked on "clone" in github.
Now open this folder into you code programme and make your basic code set up....done? Now it's time to "push" your work into github. 

##  PUSH
Time to get back into your terminal and do the following: 

``` git add . ``` to add everything you have done.
``` git commit -am "message here" ``` enter a message for what you have done.
``` git push ``` to send it to github.

Congratulations! 
your first project is online.


## PULL
The rest of your teammates can clone the repository. But now, everytime you or your teammates is going to work, you need to make a new "branch". You can see a branch as its own development environment. Trust me, you need this. first things first, open up your terminal, navigate to your project folder and type ``` git pull ```. You will now receive the latest version from Github. Now its time to make a new branch.

## BRANCH
After you have pulled the latesta work go to your terminal and type ``` git checkout -b *namebranch ``` make a fitting name for your branch. By using "checkout" you will automatically switch to your newly made branch. You can always see in which branch you are by typing ``` git branch ``` in the terminal. Every eddit you make will be in that branch only.

## PULL REQUEST
After you pushed your work from the newly made branch, your work must be "merged" together so that everyone can have it. Go to github and into your project on github. You will see that you can make a "pull request". DO IT!
Make a pull request and when there are no conflicts you can succesfully merge and everyone can pull!

## CONFLICTS
But what happens when there are conflicts? this mostly happens when you are programming on the same file as one of your teammates. No worries! You can resolve it. Choose to resolve and now the only thing you have to do is fix whats wrong.
