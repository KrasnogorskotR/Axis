# Top - Top module #

## Top channeltop - Channel Top Module ##

## `$channeltop words | $channeltop messages | $channeltop msgs [channel] ` ##
### Functionality ###
Get this servers's favorite words.
### Parameters ###
* channel - IChannel (Optional)

---

## `$channeltop commands | $channeltop cmds [channel] ` ##
### Functionality ###
Get this servers's favorite commands.
### Parameters ###
* channel - IChannel (Optional)

---

# Public - Public module #

## `$help ` ##
### Functionality ###
What...

---

## `$info ` ##
### Functionality ###
Info about Axis

---

## `$inviteme ` ##
### Functionality ###
Returns the OAuth2 Invite URL of the bot

---

## `$stats ` ##
### Functionality ###
Returns Axis stats.

---

## `$ping ` ##
### Functionality ###
Pong!

---

## `$guildinfo ` ##
### Functionality ###
Return the guild info

---

## `$lookup <ip> ` ##
### Functionality ###
Lookup an IP
### Parameters ###
* ip - String

---

# Fun - Fun module #

## `$cat ` ##
### Functionality ###
Sends a random cat image

---

## `$dog ` ##
### Functionality ###
Sends a random dog image

---

## `$lmgtfy [ffs] ` ##
### Functionality ###
http://lmgtfy.com/?q=what+is+lmgtfy
### Parameters ###
* ffs - String (Optional)

---

## `$magic [name] ` ##
### Functionality ###
Show cards of Magic The Gathering
### Parameters ###
* name - String (Optional)

---

## `$steps ` ##
### Functionality ###
Returns random WikiHow steps

---

## `$love <nameone> <nametwo> ` ##
### Parameters ###
* nameone - String
* nametwo - String

---

## `$love <userone> <usertwo> ` ##
### Parameters ###
* userone - IUser
* usertwo - IUser

---

## `$trump ` ##
### Functionality ###
Sends a random Donald Trump quote

---

## `$yodify [query] ` ##
### Functionality ###
Yodify a sentence
### Parameters ###
* query - String (Optional)

---

## `$urban [query] ` ##
### Functionality ###
Return a Urban Dictionary definition about a word
### Parameters ###
* query - String (Optional)

---

## `$define <word> ` ##
### Functionality ###
Returns the definition of a word
### Parameters ###
* word - String

---

## `$catfact ` ##
### Functionality ###
Sends a random Cat fact

---

## `$revav [usr] ` ##
### Functionality ###
Searches for the user avatar on google
### Parameters ###
* usr - IUser (Optional)

---

## `$wiki [query] ` ##
### Functionality ###
Returns a Wikipedia page based on your query
### Parameters ###
* query - String (Optional)

---

## `$mcping [query] ` ##
### Functionality ###
Pings a Minecraft server
### Parameters ###
* query - String (Optional)

---

## `$doge <phrase> ` ##
### Functionality ###
Generate a doge!
### Parameters ###
* phrase - String

---

## `$pat [user] ` ##
### Functionality ###
Pat someone.
### Parameters ###
* user - IUser (Optional)

---

## `$pats [user] ` ##
### Functionality ###
Find out how many times someone has been pat.
### Parameters ###
* user - IUser (Optional)

---

## `$8 <randomText> ` ##
### Functionality ###
Ask your questions to the magic 8 ball
### Parameters ###
* randomText - String

---

## `$reg <input> ` ##
### Functionality ###
Transforms your input into emoji
### Parameters ###
* input - String

---

## `$linux <guhnoo> <loonix> ` ##
### Functionality ###
https://www.youtube.com/watch?v=QlD9UBTcSW4
### Parameters ###
* guhnoo - String
* loonix - String

---

# Gambling - Gambling module #

## `$flip [count] ` ##
### Functionality ###
Flip a coin
### Parameters ###
* count - Int32 (Optional)

---

## `$betflip <amount> <guess> ` ##
### Functionality ###
Bet if the coin flip will return heads or tails
### Parameters ###
* amount - Int32
* guess - String

---

## `$roll ` ##
### Functionality ###
Roll a dice

---

## `$coins [user] ` ##
### Functionality ###
Return your coins
### Parameters ###
* user - IUser (Optional)

---

## `$betroll <amount> ` ##
### Functionality ###
Bet what number the dice will roll
### Parameters ###
* amount - Int64

---

## `$leaderboard ` ##
### Functionality ###
Shows the richest people

---

## `$profile ` ##
### Functionality ###
Shows your profile (Not implemented yet)

---

# Games - Games module #

## `$hangmanlist ` ##
### Functionality ###
Shows all the hangman term types

---

## `$hangman [type] ` ##
### Functionality ###
Start a hangman game
### Parameters ###
* type - HangmanTermType (Optional)

---

## `$leet <level> [text] ` ##
### Functionality ###
L337 5P34|< L1|<3 7|-|47
### Parameters ###
* level - Int32
* text - String (Optional)

---

## `$rps <input> ` ##
### Functionality ###
Rocket, Paperclip and Scissors
### Parameters ###
* input - String

---

# Jokes - Jokes module #

## `$yomama ` ##
### Functionality ###
Retuns a yo mama joke

---

## `$randjoke ` ##
### Functionality ###
Returns a rand joke

---

# Search - Search module #

## `$gif <keywords> ` ##
### Functionality ###
Search for a gif with the provided keywords.
### Parameters ###
* keywords - String

---

## `$weather <query> ` ##
### Functionality ###
Weather command
### Parameters ###
* query - String

---

## `$stackexchange | $se <keywords> ` ##
### Functionality ###
Search for tags on a stackexchange site.
### Parameters ###
* keywords - String

---

# Translate - Translate module #

## `$translate <langs> [text] ` ##
### Functionality ###
Translate a sentence
### Parameters ###
* langs - String
* text - String (Optional)

---

## `$autotranslang [langs] ` ##
### Functionality ###
Auto translate every message in the channel
### Parameters ###
* langs - String (Optional)

---

## `$translangs ` ##
### Functionality ###
Returns the possible translation langs

---

# Utility - Utility module #

## `$user [userM] ` ##
### Functionality ###
Returns information about an user
### Parameters ###
* userM - IGuildUser (Optional)

---

## `$google <search> ` ##
### Functionality ###
"Googles" a sentence
### Parameters ###
* search - String

---

## `$hastebin <str> ` ##
### Functionality ###
Send a text to hastebin
### Parameters ###
* str - String

---

## `$ign <gameName> ` ##
### Functionality ###
Returns a IGN review about a game
### Parameters ###
* gameName - String

---

## `$togethertube ` ##
### Functionality ###
A service to watch youtube together with your friends

---

## `$myperms ` ##
### Functionality ###
Returns all your perms

---

## `$roles [target] [page] ` ##
### Functionality ###
Returns all your roles
### Parameters ###
* target - IGuildUser (Optional)
* page - Int32 (Optional)

---

## `$emojis <emojis> ` ##
### Functionality ###
Returns emojis information
### Parameters ###
* emojis - String

---

## `$listguilds [page] ` ##
### Functionality ###
List all the guilds that Axis is in
### Parameters ###
* page - Int32 (Optional)

---

# Music - Music module (Buggy) (Owner only) #

## `$join ` ##
### Functionality ###
Joins to the channel

---

## `$leave ` ##
### Functionality ###
Disconnect a bot from the channel

---

## `$play <song> ` ##
### Functionality ###
Plays a song
### Parameters ###
* song - String

---

# Owner - Owner module #

## `$shutdown ` ##
### Functionality ###
Shutdown Axis

---

## `$restart ` ##
### Functionality ###
Restart Axis

---

## Owner set - Set Axis things... 🤔 ##

## `$set nickname [newNickname] ` ##
### Functionality ###
Set Axis nickname
### Parameters ###
* newNickname - String (Optional)

---

## Owner blacklist - Blacklist Module ##

## `$blacklist add <userMen> ` ##
### Functionality ###
Add an user to the blacklist
### Parameters ###
* userMen - IUser

---

## `$blacklist remove <userMen> ` ##
### Functionality ###
Remove an user from the blacklist
### Parameters ###
* userMen - IUser

---

## `$blacklist list ` ##
### Functionality ###
List all the users that are in the blacklist

---

# OwnerWIP - Commands in WIP that can only be used by my owner #

## `$test <keywords> ` ##
### Functionality ###
Some testing inidncndidsfmdsf
### Parameters ###
* keywords - String

---

## `$updatedocs ` ##
### Functionality ###
Update these docs

---

## `$gendocs ` ##
### Functionality ###
Generates these docs

---

## `$setcoin <amount> [user] ` ##
### Functionality ###
Set the user's coins.
### Parameters ###
* amount - Int64
* user - IUser (Optional)

---

## `$send <where> [msg] ` ##
### Functionality ###
Send a message to a channel or user
### Parameters ###
* where - String
* msg - String (Optional)

---

## `$announce <message> ` ##
### Functionality ###
Send a message to all guilds
### Parameters ###
* message - String

---

## `$delwarn <User> <Id> ` ##
### Functionality ###
Delete a warn
### Parameters ###
* User - IUser
* Id - Int32

---

## `$warn <User> <Reason> ` ##
### Functionality ###
Warn an user
### Parameters ###
* User - IUser
* Reason - String

---

## `$listwarn <User> ` ##
### Functionality ###
List all the warns of an user
### Parameters ###
* User - IUser

---

## `$resetperms ` ##
### Functionality ###
Reset all the perms, from all the users

---

# Custom - Custom commands #

## `$create <name> [description] ` ##
### Functionality ###
Create a new custom command.
### Parameters ###
* name - String
* description - String (Optional)

---

## `$commands | $cmds [page] ` ##
### Functionality ###
Get a list of all custom commands on this server.
### Parameters ###
* page - Int32 (Optional)

---

# Guild - Guild Commands #

## `$ban <user> [msg] ` ##
### Functionality ###
Bans the user from the guild.
### Parameters ###
* user - IGuildUser
* msg - String (Optional)

---

## `$kick <userM> ` ##
### Functionality ###
Kicks the user from the guild.
### Parameters ###
* userM - IUser

---

# Guild -  #

## `$setprefix <prefix> ` ##
### Functionality ###
Change the prefix for this guild.
### Parameters ###
* prefix - String

---

## `$setmodlog [channel] ` ##
### Functionality ###
Set the channel moderator actions are logged to.
### Parameters ###
* channel - ITextChannel (Optional)

---

## `$setstarboard [channel] ` ##
### Functionality ###
Set the channel starred messages are logged to.
### Parameters ###
* channel - ITextChannel (Optional)

---

