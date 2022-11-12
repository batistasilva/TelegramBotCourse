# Let's study and tests the first example: echobot.py
Follow the Link on github: [`echobot.py`](https://github.com/python-telegram-bot/python-telegram-bot/blob/v13.x/examples/echobot.py)

This is probably the base for most of the bots made with `python-telegram-bot`. It simply replies to each text message with a message that contains the same text.
### Let's study the code:

Starting at the beginning of the file, when the comments start...
From lines 6 to 16...
```
"""
Simple Bot to reply to Telegram messages.

First, a few handler functions are defined. Then, those functions are passed to
the Dispatcher and registered at their respective places.
Then, the bot is started and runs until we press Ctrl-C on the command line.

Usage:
Basic Echobot example, repeats messages.
Press Ctrl-C on the command line or send a signal to the process to stop the
bot.
"""
```
In the comment above it says that the bot acts like a telegram chat...
Also, it is in an endless loop waiting for a command. Which are defined by functions `[start. help, echo]`.
It also says that we can stop it by pressing the keys on our keyboard, `[Ctrl + C]`, or even we can send the command from our operating system to terminate the running process.

