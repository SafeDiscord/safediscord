# SafeDiscord

SafeDiscord exists to keep track of troublemakers that may join your server, so you don't have to. This isn't a moderation suite. No fancy bells or whistles, just a snitch to possibly malicious accounts.

Shills, PM spammers, possibly underage accounts, and many more options.

---

Invite the bot to your server, and go through setup with `//TODO SETUP BOT COMMANDS`. Use `//TODO SET UP PREFIX + HELP` to modify or check the status of current settings, as well as how many reports have been submitted. 

---

We encourage you to not report someone just because the bot warns you about them, but wait to see if there are any problems. This helps us keep down the false positives.

---

## To developers:
[Here](https://github.com/SafeDiscord/safediscord-bot) is the bot code. Please fork and PR, we need all the help we can get. Thank you for your efforts!





---

### Todo
- [X] check usernames or IDs within server
- [X] re-think bot
- [ ] sync self-hosted bot with main repo
- [ ] disable reporting if self-hosting (conflicting files problem)
- [ ] re-think data storage
- [ ] instructions on how to get a user's UUID for manually checking
- [ ] possible frontend search by UUID for offenders (haveibeenpwned.com-esque)
- [ ] possible online report via discordAuth login
- [X] in-server reporting through the bot, based on roles/perms
- [ ] multiple ways to warn a server of possible troublemaker joining: PMs to certain ranks, specific channel, custom message
- [ ] learn how bots store configs per server
- [ ] learn how to do weighted search shenanigans for "this is the most common offense"
- [ ] add roles to incoming troublemakers?
- [ ] warn if account age is below threshold & IP is known VPN outlet
- [ ] create gitignored file of guilds and their settings, probably in YAML
