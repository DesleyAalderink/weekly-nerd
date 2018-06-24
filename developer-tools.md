# A dive into developer tools and modules

# Table of Contents
- [Introduction](#introduction)
- [Choosing a build tool](#Choosing-a-build-tool)
- [Build tool](#despair)
- [Insert the data into the HTML](#Insert-the-data-into-the-HTML)
- [Compiling JS and CSS](#Compiling-JS-and-CSS)
- [Strict code rules](#Strict-code-rules)
- [Making our lifes easier](#Making-our-lifes-easier)
- [Conclusion](#Conclusion)

## Introduction
For the final project of the minor, its up to me to make a code setup with build tools.
We had a basic set up that involves Gulp but, Danny (our mentor) adviced us to start from scratch.
I always wanted to learn more about this subject, so I dove into the web and made a little research for what the project must have.

![Builtools](sketchnotes/img/buildtools.png)

## Choosing a build tool
There is a huge list of build tools to choose from, but what do I choose?
I started my research by finding out what my project needs. It needed to do the following:

* A build tool
* Insert the data into the HMTL
* Compile the JS and CSS for faster performance
* Make strict code rules for our groep
* Something to make our lifes easier 

## Build tool
Choosing a build tool is difficult. The #1 problem with build tools is that they get outdated really fast. I decided to play it safe and just use NPM Scripts. Everything we want to achieve can be done with NPM Scripts without some rubbish extra modules that gets installed like Gulp does.

![NPMscript](sketchnotes/img/npmscript.png)

## Insert the data into the HTML
I started by going through the list. A quick and easy tool to insert data into HTML is "EJS".
It's something I have experience with because I use it for almost all of my projects. Its fast and easy to use.

![EJS](sketchnotes/img/ejs.png)

## Compiling JS and CSS
This was something new for me. A lot of developers are compiling JS and CSS for a faster performance AND a more functional way to write code. When searching online I found a toold called "Rollup JS" what will do exactly what we want. It will only work with ES6 but, that works out great for us, because we want to work with ES6.

![Rollup](sketchnotes/img/rollup.jpg)

## Strict code rules
Because we are working in a team of 4, we need something to make sure we are using the same code rules. We all need to think on the same line. We need a linter. A good and easy to use linter is "eslint". We can modify the rules to our benefit and it will give good errors for us to see. The rules were: 

* No ;
* A space before the "{"
* ES6 only
* Capital letters with ID's and classes

![Eslint](sketchnotes/img/eslint.png)

## Making our lifes easier
Something to make coding a little more relaxed is "Nodemon". This little module will restart the server after every safe. It also comes with a function called "watch" that will help compile the CSS and JS when the server gets restarted.

![Eslint](sketchnotes/img/nodemon.png)

## Conclusion
Build tools and modules are cool. I get why a lot of developers work with it. I learned a lot of it and it made our project a little easier. I will definitely keep using these tools and modules.


