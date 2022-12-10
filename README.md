# File-SHare-Bot




Telegram Bot To Store Posts And Documents And it Can Access By Special Links.
I Guess This Will Be Usefull For Many People.....😇. 

##

**If you need any more modes in repo or If you find out any bugs, mention in [@venkat2535](https://telegram.me/venkat2535)**

### Features
- Fully customisable.
- Customisable welcome & Forcesub messages.
- More than one Posts in One Link.
- Can be deployed on heroku directly.

### Setup

- Add the bot to Database Channel with all permission
- Add bot to ForceSub channel as Admin with Invite Users via Link Permission if you enabled ForceSub 

##
### Installation
#### Deploy on Heroku
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/VenkatMastercoder/File-Share-Bot)</br>
<a href="https://youtu.be/ep3u-n_DI_Q">
  <img src="https://img.shields.io/badge/How%20to-Deploy-red?logo=youtube" width="147">
</a><br>



### Admin Commands

```
/start - start the bot or get posts

/batch - create link for more than one posts

/genlink - create link for one post

/users - view bot statistics

/broadcast - broadcast any messages to bot users
```

### Variables

* `API_HASH` Your API Hash from [@MT_MyTelegramOrg_Bot](https://telegram.me/MT_MyTelegramOrg_Bot)
* `API_ID` Your API ID from [@MT_MyTelegramOrg_Bot](https://telegram.me/MT_MyTelegramOrg_Bot)
* `TG_BOT_TOKEN` Your bot token from [@BotFather](https://telegram.me/BotFather)
* `OWNER_ID` Must enter Your Telegram Id
* `CHANNEL_ID` Your Channel ID eg:- -100xxxxxxxx
* `ADMINS` Optional: A space separated list of user_ids of Admins, they can only create links
* `START_MESSAGE` Optional: start message of bot, use HTML and <a href='https://github.com/COLD-ONEZ/File-SHare-Bot/blob/main/README.md#start_message'>fillings</a>
* `FORCE_SUB_MESSAGE`Optional:Force sub message of bot, use HTML and Fillings
* `FORCE_SUB_CHANNEL` Optional: ForceSub Channel ID, leave 0 if you want disable force sub


### Fillings
#### START_MESSAGE | FORCE_SUB_MESSAGE

* `{first}` - User first name
* `{last}` - User last name
* `{id}` - User ID
* `{mention}` - Mention the user
* `{username}` - Username

#### CUSTOM_CAPTION

* `{filename}` - file name of the Document
* `{previouscaption}` - Original Caption

##

   **Star this Repo if you Liked it ⭐⭐⭐**

