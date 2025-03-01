[[Integration Suite]]

### Commands
---
- [x] /whitelist {username}
	- [x] Check if Java or Bedrock
- **Java**
	- [x] Forward command to Plugin
	- [x] Plugin executes whitelist command on user
- **Bedrock**
	- [x] Use API to get user floodgate UUID
	- [x] Forward command to Plugin
	- [x] Plugin edits whitelist file
	- [x] Adds username and UUID
	- [x] Executes reload whitelist command


### Chat Transfer
---
**Plugin** - Minecraft
- [x] Retrieve Minecraft chat
- [x] Forward to Bot

**Bot** - Discord
- [x] Receive chat data
- [x] Parse data
- [x] Send message into discord channel

### Help commands
---
**/help**
- [x] In an embed message

**/helpmod**
- [x] List of moderation commands
- [x] /whitelist

**/profile**
- [ ] Shows player stats
- [ ] Shows player streak map


### Player streaks
---
- [ ] Record player streak activity and congrats them when they join for the first time each day
- [ ] Streak freezes they get as rewards for something


### Moderation
---
- [ ] **User Profiles**
	Variables
		Record user strikes
		Ranks
		Num Past Warnings
		Num Past bans
		List of all offenses
			-String explaining offense
			-Expire after a certain amount of time
			-Record num strikes

- [ ] **3 strike system**
	- Per issue
	1st Strike
		*User gets a warning sent in **Discord DMs** and in **Minecraft***
	2nd Strike
		*Temporary ban of moderators choice 1-30 days from Minecraft*
	3rd Strike
		*Perm ban from Minecraft and Discord*


### Adventure Guild
---
- [ ] Building in spawn 


### Mod Reply
---
- [ ] /mod-reply (message)
	- Reply to a users message and do the command
	- Message put in command will be said by bot
- [ ] /opendm (username)
	- Turns current channel into that players dms
	- Anything a mods says will go into their dms
	- Anything user says in their dms will go into channel
	- Dm closes after certain time of inactivity on mods side
- [ ] /closedm
	- Closes current dm in that channel


### Notif
---
- [ ] Twitch and Twitter posts messages on discord
- for neo and her twitch discords




### **Master Archivist: AI-Powered Lore and Diary Entries**
--- 
- [ ] Use ai to generate a daily lore diary
	- [ ] Uses past lore summarizing it all so its digestible
	- [ ] Uses all that days messages to include into the AI
	- [ ] Sends daily lore into a designated channel


### Request Whitelist
---
- [ ] /create-whitelist-requester
	- [ ] Makes an embed message that has a short explanation, etc
	- [ ] Has an interactive button where only none whitelisted players can push
	- [ ] When pushed, bot will dm user and ask survey questions
- [ ] Survey
	- [ ] Use models to ask questions
	- [ ] Will ask questions one by one
	- [ ] Can insta deny user if answers badly
	- [ ] Once user is done the answers are sent into a mod channel as an embed message
	- [ ] This embed message will have a two buttons, Deny and Confirm
	- [ ] Confirm - whitelists player and notifies them
	- [ ] Deny - Prevents user from requesting again, has to go directly to a mod
- [ ] Whitelist
	- [ ] Uses whitelist classes from both bot and plugin


