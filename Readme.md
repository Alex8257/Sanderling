# Sanderling

**Sanderling helps you automate tasks in [eve online](https://www.eveonline.com) and read information from the game client.**

## Features

+ **safe**: does not inject into or write to the eve online client. That is why using it with eve online is not detectable.
+ **accurate & robust**: Sanderling uses memory reading to retrieve information about the game state. In contrast to screen scraping, this approach won't be thrown off by a noisy background or non-default UI settings.
+ **easy to use**: You will achieve quick results with the [integrated script engine](https://github.com/Arcitectus/Sanderling/wiki/Script-Engine) and API explorer.
+ **comprehensive**: Sanderling is used to build mining, trading, mission running and [anomaly ratting](https://github.com/botengine-de/A-Bot) bots.

## Requirements

+ the application requires Microsoft .NET Framework 4.6.1 which can be downloaded from [https://www.microsoft.com/download/details.aspx?id=49982](https://www.microsoft.com/download/details.aspx?id=49982).

## Getting Started

To start with automation in EVE online, see the [List Of EVE Online Bots For Beginners](http://forum.botengine.org/t/list-of-eve-online-bots-for-beginners/629)

## Feedback

Spotted a bug or have a feature request? Post on the [forum](http://forum.botengine.org/c/botting/eve-online) of file an issue [on github](https://github.com/Arcitectus/Sanderling/issues).

## Need Help?

Do you have a question or need help with the development of your bot? Get in contact with other developers on the [BotEngine Forum](https://forum.botengine.org).

## Information For Developers

### Bot Creators
[Bot Creator Guide](https://github.com/Arcitectus/Sanderling/wiki/Bot-Creator-Guide)

### Building from source
The source code uses C# 7 features. It is recommended to use [Visual Studio](https://www.visualstudio.com/) version 2017 or newer for building.

### Contributing
See the [Contributing Guide](Contributing.md)

<br><br><br><br>

![visualization of data read from eve online client memory.](image/uitree.extract.png)
