<!DOCTYPE html>
<html>
<head>
<link rel="stylesheet" href="css/style.css">
</head>

### TelegramBotCourse
Just some examples from (course/tutorial) from TelegramBot, using version from [python-telegram-bot-13.13  or 14], that version was the only version that i had sucess in my [debian 11] system, with [python version 3.9 or 3.11].

All examples posted here was tested by me in my system, and a telegram-robot created by **@BotFather**, in my telegram account. 

Step by step to get a positive result. Thus avoiding headaches like I had at the beginning of my apprenticeship.

### Installing Python
First download python 3.9 or high. link to [https://www.python.org](https://www.python.org/downloads/)

```bash
 #open a terminal
 mkdir ~/workspace
 cd ~/workspace
 # extract your version of python
 tar -xvf Python-3.xx.x.tar.xz 
 # Enter in the folder
 cd Python-3.xx.x 
 ./configure --enable-optimizations
```
For configure the quantities of processor your machine have you will need run (nproc) command. Call it and get the number of processor you have in your machine and pass to command (**make -j ?**), example: **make -j 2**, The number 2 represent the number of processor my machine have.

``` 
make -j 2 # Number 2 is just an example of the quantity for any computer.
sudo make altinstall
cd .. # Returns you to your previous working directory
```

On this time you will have python installed in your system. Just for test run: 

```
python --version # If you get command not found. Try: python3 --version
```
### Installing python-telegram-bot-13.14
That is the latest version to using without surprise...👍
Lets clone the latest version: 

```bash
git clone -b v13.x  https://github.com/python-telegram-bot/python-telegram-bot --recursive
#Lets install it...
cd python-telegram-bot
```

Now let's perform the installation using the command, 🔓<c>**(sudo)**</c> to install. Because the installer requires privileges to install in the same location where python3 is installed.

```
sudo python3 setup.py install
```
### After Installation...
Now it's a time to start your telegram application, and create our first bot to use in the course.
 
+ First open telegram app, and call botfather, in the search bar, like: @BotFather..
 ![BotFatherStart-Short.png](images%2FBotFatherStart-Short.png)
 
+ Now click in `<start>`, like in the image below...
 ![BotFatherStartShort-1.png](images%2FBotFatherStartShort-1.png)
 
+ Now we can see the menu options in this image below and select the first option from the menu to create our bot.
 ![BotFather-after-start.png](images%2FBotFather-after-start.png)
 
+ Now, it's time to give our bot a name, as in the image below. We can call it: TutorialBot..
 ![TutorialBot.png](images%2FBotName.png)
 
+ Now, it's time to define a user to our bot, that shoul be tutorialuser_bot... As in the image below.
 ![TutorialUserBotName.png](images%2FTutorialUserBotName.png)
 
+ Now, it's time to take note of our Token, to use it in our application... It should look like what we see in the image below... Note about the Token: It should not be shared with anyone else... If you want to have access problems with it..
 ![TakenNotesShort.png](images%2FTakenNotesShort.png)
 
+ Now, we will testing our bot... Following step below... Just click on your bot name where it is displayed in the image text...
 ![TestingYourBot-1.png](images%2FTestingYourBot-1.png)
 
+ Next... just click `/Start`
+ ![TestingYourBot-2.png](images%2FTestingYourBot-2.png)
 
+ Next... Writing something to test, and press `<enter>`
+ ![HelloWorldToBot.png](images%2FHelloWorldToBot.png)

+ Next...
+ ![HelloWorld-2.png](images%2FHelloWorld-2.png)

### Preparation is done..! 
From this moment. We are ready to start the course. In other words!, We will be able to test all the examples that we find for the version that has been installed on our system. That is (v13.x and v14.x).👍

Now from that moment, we will start testing the examples with their explanations. I will put each one in an individual folder to facilitate the tests, and also to have the explanations individually.

 
## With little patience everything will be fine, from now on... 🙏


