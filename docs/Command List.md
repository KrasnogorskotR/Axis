# Top -  #

## Top channeltop -  ##

## `$channeltop words | $channeltop messages | $channeltop msgs [channel] ` ##
### Functionality ###
Get this servers's favorite words.
### Parameters ###
* channel - IChannel (Optional)

## `$channeltop commands | $channeltop cmds [channel] ` ##
### Functionality ###
Get this servers's favorite commands.
### Parameters ###
* channel - IChannel (Optional)

# Public -  #

## `$info ` ##

## `$inviteme ` ##
### Functionality ###
Returns the OAuth2 Invite URL of the bot

## `$stats ` ##
### Functionality ###
Returns Axis stats.

## `$ping ` ##
### Functionality ###
Pong!

## `$guildinfo ` ##

## `$lookup <ip> ` ##
### Parameters ###
* ip - String

# Fun -  #

## `$cat ` ##

## `$dog ` ##

## `$lmgtfy [ffs] ` ##
### Parameters ###
* ffs - String (Optional)

## `$magic [name] ` ##
### Parameters ###
* name - String (Optional)

## `$steps ` ##

## `$love <userone> <usertwo> ` ##
### Parameters ###
* userone - IUser
* usertwo - IUser

## `$love <nameone> <nametwo> ` ##
### Parameters ###
* nameone - String
* nametwo - String

## `$trump ` ##

## `$yodify [query] ` ##
### Parameters ###
* query - String (Optional)

## `$urban [query] ` ##
### Parameters ###
* query - String (Optional)

## `$define <word> ` ##
### Parameters ###
* word - String

## `$catfact ` ##

## `$revav [usr] ` ##
### Parameters ###
* usr - IUser (Optional)

## `$wiki [query] ` ##
### Parameters ###
* query - String (Optional)

## `$mcping [query] ` ##
### Parameters ###
* query - String (Optional)

## `$doge <phrase> ` ##
### Functionality ###
Generate a doge!
### Parameters ###
* phrase - String

## `$char <str> ` ##
### Functionality ###
Get the char info.
### Parameters ###
* str - String

## `$pat [user] ` ##
### Functionality ###
Pat someone.
### Parameters ###
* user - IUser (Optional)

## `$pats [user] ` ##
### Functionality ###
Find out how many times someone has been pat.
### Parameters ###
* user - IUser (Optional)

## `$8 <randomText> ` ##
### Parameters ###
* randomText - String

## `$reg <input> ` ##
### Parameters ###
* input - String

## Fun pb -  ##

## `$pb call <id> ` ##
### Parameters ###
* id - UInt64

## `$pb disconnect | $pb dc ` ##

# Gambling -  #

## `$flip [count] ` ##
### Parameters ###
* count - Int32 (Optional)

## `$betflip <amount> <guess> ` ##
### Parameters ###
* amount - Int32
* guess - String

## `$roll ` ##

## `$cash [user] ` ##
### Parameters ###
* user - IUser (Optional)

## `$betroll <amount> ` ##
### Parameters ###
* amount - Int64

## `$leaderboard ` ##

## `$profile ` ##

# Games -  #

## `$hangmanlist ` ##

## `$hangman [type] ` ##
### Parameters ###
* type - HangmanTermType (Optional)

## `$leet <level> [text] ` ##
### Parameters ###
* level - Int32
* text - String (Optional)

## `$rps <input> ` ##
### Parameters ###
* input - String

## `$linux <guhnoo> <loonix> ` ##
### Parameters ###
* guhnoo - String
* loonix - String

# Help -  #

## `$help ` ##
### Functionality ###
What...

## `$help <command> ` ##
### Parameters ###
* command - String

# Jokes -  #

## `$yomama ` ##

## `$randjoke ` ##

# Search -  #

## `$gif <keywords> ` ##
### Functionality ###
Search for a gif with the provided keywords.
### Parameters ###
* keywords - String

## `$weather <query> ` ##
### Parameters ###
* query - String

## `$stackexchange | $se <keywords> ` ##
### Functionality ###
Search for tags on a stackexchange site.
### Parameters ###
* keywords - String

# Translate -  #

## `$translate <langs> [text] ` ##
### Parameters ###
* langs - String
* text - String (Optional)

## `$autotranslang [langs] ` ##
### Parameters ###
* langs - String (Optional)

## `$translangs ` ##

# Utility -  #

## `$user [userM] ` ##
### Parameters ###
* userM - IGuildUser (Optional)

## `$google <search> ` ##
### Parameters ###
* search - String

## `$color <color> ` ##
### Parameters ###
* color - String

## `$hastebin <str> ` ##
### Parameters ###
* str - String

## `$ign <gameName> ` ##
### Parameters ###
* gameName - String

## `$togethertube ` ##

## `$myperms ` ##

## `$roles <target> [page] ` ##
### Parameters ###
* target - IGuildUser
* page - Int32 (Optional)

## `$roles [page] ` ##
### Parameters ###
* page - Int32 (Optional)

## `$emojis <emojis> ` ##
### Parameters ###
* emojis - String

## `$listguilds [page] ` ##
### Parameters ###
* page - Int32 (Optional)

# Eval -  #

## `$eval <toExecute> ` ##
### Parameters ###
* toExecute - String

# Music -  #

## `$play <path> ` ##
### Parameters ###
* path - String

## `$mdc ` ##

# Owner -  #

## `$shutdown ` ##

## `$restart ` ##

## Owner set -  ##

## `$set nickname [newNickname] ` ##
### Parameters ###
* newNickname - String (Optional)

## Owner blacklist -  ##

## `$blacklist add <userMen> ` ##
### Parameters ###
* userMen - IUser

## `$blacklist remove <userMen> ` ##
### Parameters ###
* userMen - IUser

## `$blacklist list ` ##

# OwnerWIP -  #

## `$test ` ##

## `$gendocs ` ##
### Functionality ###
Generates these docs

## `$setcoin <amount> [user] ` ##
### Parameters ###
* amount - Int64
* user - IUser (Optional)

## `$send <where> [msg] ` ##
### Parameters ###
* where - String
* msg - String (Optional)

## `$announce <message> ` ##
### Parameters ###
* message - String

## `$delwarn <User> <Id> ` ##
### Parameters ###
* User - IUser
* Id - Int32

## `$warn <User> <Reason> ` ##
### Parameters ###
* User - IUser
* Reason - String

## `$listwarn <User> ` ##
### Parameters ###
* User - IUser

## `$resetperms ` ##

# Custom -  #

## `$create <name> [description] ` ##
### Functionality ###
Create a new custom command.
### Parameters ###
* name - String
* description - String (Optional)

## `$commands | $cmds [page] ` ##
### Functionality ###
Get a list of all custom commands on this server.
### Parameters ###
* page - Int32 (Optional)

# Guild -  #

## `$ban <user> [msg] ` ##
### Functionality ###
Bans the user from the guild.
### Parameters ###
* user - IGuildUser
* msg - String (Optional)

## `$kick <userM> ` ##
### Functionality ###
Kicks the user from the guild.
### Parameters ###
* userM - IUser

# Guild -  #

## `$setprefix <prefix> ` ##
### Functionality ###
Change the prefix for this guild.
### Parameters ###
* prefix - String

## `$setmodlog [channel] ` ##
### Functionality ###
Set the channel moderator actions are logged to.
### Parameters ###
* channel - ITextChannel (Optional)

## `$setstarboard [channel] ` ##
### Functionality ###
Set the channel starred messages are logged to.
### Parameters ###
* channel - ITextChannel (Optional)

