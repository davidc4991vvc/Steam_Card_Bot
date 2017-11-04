# Steam-Card-Bot v0.2

1. Unpack the files to your Desktop or where ever you want it

2. go to Command Prompt

3. type the following into command propt
    a. cd Directory of files 
    b. npm install mathjs
    c. npm install steam-user
    e. npm install steam-totp
    f. npm install steam-tradeoffer-manager
    g. npm install raven
    h. npm install steamid
    i. npm install colors
    j. npm install jsonfile
    k. npm install steamcommunity
    


4. go to the settings folder

5. go to config.json and put your username, password, sharedsecret, identitysecret, ownerID

Username = Bot Username
Password = Bot Password
Sharedsecret = Shared Secret from desktop authenticator
Identity Secret = Identity Secret from Desktop Authenticator

OwnerID = Bot owner ID64

SteamName = Desired Steam Name for the Bot

GroupLink = Your Group Link Here

Comments = Enables and Disables Comments on user Profiles

IssueTracking =  Enable/Disables Issue Tracking 
NOTE if Disabled might be hard to help if you encounter a problem with the code

GroupID = GroupId here

Hatbanking =  Enables/disable Hat Banking 
KeyBanking = Enables/disables Key banking
RobopartBanking = Enables/disables robo part banking

Group = Group Name Here
chats = Enables manual chats for the bot to communitcate to other users with chat messages

6. go to GamesPlayed.json and make sure the games are set correctly

Games1 = Listed Game
Games2 = Game ID

7. go to messages.json and make sure everything is done correctly 

8. go to prices check to make sure the items you want to buy and  sell is in it and expample is below and on the prices.json

{
"Steam Market Name of item"
{
"buy": Price,
"sell: Price
}
}

9. Got to Stock.json under Stock folder in settings
Here you will edit stock amounts 
{
"item name has to be the steam market name"
{
"instock": 0,
"stocklimit": 0
}
}

10. Go to Messages/messages.json
make sure the messages are right for the items

11. Go to tradingcard.json and edit them if needed

12. Go to Emoticons.json and edit them if needed

13. Go to backgrounds.json and edit them if needed

14. Go to Settings/Comments/comments.json Edit them if needed
NOTE: Comments are currently set to only comment after a trade success not if it was cancelled or declined

15. Go to the where the app.js is the go to the folder Admin Options

16. Got to AdminConfig.json and Change The Following to Your Personal Preeference

 AdminID = you Main SteamID
 
 AdminChat = Enables / Disables Admin Chats //Note Not Currently Used To Be Added
 
 AdminPrices = Enables / Disables Admin Prices //Note Not Currently Used To Be Added
 
 disableAdminComments = Enables / Disables bot Comments for Admin Commnets

17. Admin Messages Currently Not USed

18. Make a new text file

19. Name it Run Bot.bat

20. Edit it and put the following code: node app.js press ENTER  type pause
it will look like this 

node app.js
pause

21. Run the Run Bot.bat to run the bot

If you want to Try the Developer Options Out
open the Developer options Readme in Developer Options Folder

HAVE ANY PROBLEMS POST YOUR PROBLEM HERE ON THE GITHUB REPO OR USE OUR STEAM GROUP steamcommunity.com/groups/MarketWH
