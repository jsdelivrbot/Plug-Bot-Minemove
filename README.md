basicBot
========

A not so basic bot for plug.dj 

Stay updated on **basicBot**'s development by following the project on Twitter [@bscBt](http://twitter.com/bscBt)


!!!TO CUSTOMIZE: USE [THIS REPOSITORY](https://github.com/KaosBass/basicBot-customization)!!!
==============================================================================================

IMPORTANT
---------

__basicBot has been updated to work under plug's update. There may still be bugs and functionality is not guaranteed.__

__Make sure to update your bookmark, as the link has changed recently!!!__

__Important changes in version 2.x.x:__

- Now should be fully compatible with Firefox.
- You can now change the bot's name, no need to make a fork to change it anymore. Available under custom settings as "botName".
- The bot's variable is now exposed outside of the script. You can access it as the variable "bot" in the console. This should allow for secondary scripts extending the bot without the need to fork and lose support on its basis.
Be careful when extending it to make sure commands or features interact properly with the rest of them.
An example script to extend the bot is provided under exampleExtension.js. Please do not fork this repository to just change that file. Details of how to use are provided inside.
This is NOT needed to run the bot as it is provided, only if you want to add functionality.
- Command checking has been reworked to facilitate adding commands through secondary scripts as explained above.
- __There is now support for custom chat messages. This means you can use your own custom wording or translate it into your own language.__

Usage
-----

Bookmark the following code. To run the bot, run the bookmark.

`javascript:(function(){$.getScript('https://rawgit.com/KaosBass/basicBot/master/basicBot.js');})();`

If this does not work, go to https://raw.githubusercontent.com/KaosBass/basicBot/master/basicBot.js and copy paste its content into your console (accessible in chrome by pressing f12) when on plug.dj in your community.

###Commands###

These can be found in [the commands file](https://github.com/KaosBass/basicBot/blob/master/commands.md).

###Blacklists###
Examples of blacklists can be found in [the customization repository](https://github.com/KaosBass/basicBot-customization/tree/master/blacklists).
You can add blacklists in the settings of the bot via the methods given in that same repository. See below for more information.

###Extending functionality and custom default settings###

basicBot can be customized to fit your needs. Please refer to [the customization repository](https://github.com/KaosBass/basicBot-customization) for more info.
Please do not try to if you are not confident in your javascript capabilities.
