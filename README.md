# LANGOSAURUS (Under construction)

Telegram bot for improving english vocabulary (For russian speakers)

![alt text](https://github.com/Py4Rpi/langosaurus/blob/main/screen.jpg)

## Description

Hello!

This is my pet project for SQL and Telegram Bots practice. It is a Telegram bot which helps you to learn new words from English vocabulary.
So far it is designed only for russian speakers but there are plans to make it multilangual. This project still has a lot of work to do so
there could be some bugs or code snipets to improve.

## Getting Started

### Dependencies

I use Python 3.7 in this project.

Use requirements.txt to install:

* APScheduler==3.7.0
* async-timeout==3.0.1
* pyTelegramBotAPI==3.7.5
* schedule==1.0.0
* sqlparse==0.4.1
* virtualenv==20.0.31

### Installing

To install the bot you can just download it as a ZIP file or use "gh repo clone Py4Rpi/langosaurus" command. 
Then just copy the code in your home dir and setup config.py with your own credentials. You will have to 
register your own telegram bot and get the token from Bot Father.

### Executing program

* When dependencies and installing steps are completed you can just open terminal, go to dir with bot and run it :

```
python superlangbot.py
```

If all goes well it will send the greating message and further instructions.

There are two modes so far: 

* Learning mode
* Immediate Test

## Help

Keep in mind that it is just a simple pet project and there are no any warranty that it will work on your setup.

If any troubles you can use Issue Tracker to notify me.

Have a nice coding :)

## Version History

* 0.1
    * Initial Release

## License

There is no any licence, do whatever you want :)
