### TelegramBotCourse
Just some examples from (course/tutorial) from TelegramBot, using version from [python-telegram-bot-13.13  or 14], that version was the only version that i had sucess in my [debian 11] system, with [python version 3.9 or 3.11].

All examples posted here was tested by me in my system, and a telegram-rob created by `@BotFather`, in my telegram account.

Step by step to get a positive result. Thus avoiding headaches like I had at the beginning of my apprenticeship.

### Installing Python
First install python 3.9 or high. link to [download:](https://www.python.org/downloads/)

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
For configure the quantities of processor your machine have you will need run (nproc) command. Call it and get the number of processor you have in your machine and passe to command (make -j ?), example: make -j 2, The number 2 represent the number of processor my machine have.

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
Now let's perform the installation using the command, *(sudo)* to install. Because the installer requires privileges to install in the same location where python3 is installed.

```
sudo python3 setup.py install

```
 



