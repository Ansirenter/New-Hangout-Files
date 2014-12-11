Hangout-Pokemon Showdown Files Boilerplate
========================================================================
![Hangout](http://i58.tinypic.com/22izyu.png "Hangout")

Hangout Boiler-plate Of Showdown is a template for private servers of [Pokémon Showdown][1]. Pokémon Showdown is created by [Zarel][2].

What is a boilerplate? Boilerplate is any text that is or can be reused in new contexts or applications without being greatly changed from the original.

This repository contains the files needed to set up your own Pokémon Showdown server with all the amazing stuff that Pokémon Showdown private servers like Frost and Pandora has. This also includes [Pokemon-Showdown-Addons][3] created by [kota][4] and parser from [Pokemon-Showdown-Bot][5] by [TalkTakesTime][6].

For more information on Pokémon Showdown, setting up your own server, or viewing the credits, go visit the main [Pokémon Showdown repository][1].

About Hangout Server -
Hangout Server have been made by Ansirent And is helped by coder BlakJack, Anrin and some other guys. Hangout was banned because of a guy named Adipravar advertising so much.. 
Now we are trying our best to make a comeback for hangout server soon as we can, We are also trying to make some new codes with the help of BlakJack
I hope Our server Can be a help to all of the people that want to hangout,And we would appericiate any help. :)

  [1]: https://github.com/Zarel/Pokemon-Showdown
  [2]: https://github.com/Zarel
  [3]: https://github.com/kotarou3/Pokemon-Showdown-Addons
  [4]: https://github.com/kotarou3
  [5]: https://github.com/TalkTakesTime/Pokemon-Showdown-Bot
  [6]: https://github.com/TalkTakesTime


Features
------------------------------------------------------------------------

* Single Process Hack for improve performance.
* Up-to-date with [Pokemon Showdown][1]'s latest features.
* Money (bucks) system for winning tournaments.
* Polls for voting
* Profile command to check to see when the user's last online, their money, etc.
* A bunch of useful commands like /away, /hide, /poof, etc.
* Built-in bot for moderation and fun
* Emoticons in chat
* New Shop Features
* Authlist
* System operator system 
* Bot can Battle with team
* Poof Messages 
* Shadow Ban, Travia and other games for fun
* /clearall command
* New Css
* New Style In Battle Area

Getting Started
------------------------------------------------------------------------
To get started with this boilerplate, just download this as a zip or clone it and install a [Pokemon Showdown server][1] as you usually do.
If you forgot how to do this, here is a quick reference:

	git clone https://github.com/CreaturePhil/Showdown-Boilerplate.git showdown-boilerplate
	cd showdown-boilerplate
	npm install

Once you done that, create __usergroups.csv__, __about.csv__, __elo.csv__, __money.csv__, __lastSeen.csv__, and __tourWins.csv__ files in the _config_ folder.

To do this quickly in your terminal or command line:

On Windows:

	cd config
	Type NUL > usergroups.csv
	Type NUL > about.csv
	Type NUL > elo.csv
	Type NUL > money.csv
	Type NUL > lastSeen.csv
	Type NUL > tourWins.csv
	cd ..

On Linux or Mac:

	cd config
	touch usergroups.csv about.csv elo.csv money.csv lastSeen.csv tourWins.csv
	cd ..

`cd ..` is to go back to the showdown-boilerplate directory.
Once you get your server up and running, you can manage certain settings with the `/controlpanel` or `/cp` command.

![Control Panel](http://i.imgur.com/ImBbK5x.png "Control Panel")

In order to set up an admin account simply go to Cofing folder and by clicking on the new made usergroups.csv and adding the name of the host it will work.
You have to restart your server using /lockdown and /kill then doing node app.js again in your cmd.. enjoy ^_^

* To end a lockdown do /endlockdown 
* to buy something do /buy (thing you want) 
* /shop will make the shop come out.
* /help all - for every help
* /help (@,~,&) helps for staff
* /whois for the bot to talk
* .guide - for every command you can give to the b
* In order to change the name of bot go to bot.js and do control + f and type "Hangout bot" After you've find it simply change the name "Hangout" With your choice for the bot (ONLY WORKS FOR THIS SERVER FILES ! OTHER SERVER BOT COULD HAVE OTHER NAMES )

Contact 
------------------------------------------------------------------------
Ansirent - Usually used PS name
rhythamdasman.gmail.com - My gmail
You can find me on -
* [Pixieworld][1],
* [frost][2],
* [friendship][3],
* [pokecommunity][4]

[1]: https://pixieworld.psim.us
[2]: https://frost.psim.us
[3]: https://friendship.psim.us
[4]: https://pokecommunity.psim.us

Announcement 
------------------------------------------------------------------------
 __We are using different servers as hangout. As soon as we get one permanent server will will change its name as well. You can find us out by seeing our welcome message. Any server with the welcome message of hangout icon will be our Server ! Thanks for supporting us all the time !__


 


License
------------------------------------------------------------------------

Pokémon Showdown's server is distributed under the terms of the [MIT License][7].

  [7]: https://github.com/Zarel/Pokemon-Showdown/blob/master/LICENSE
