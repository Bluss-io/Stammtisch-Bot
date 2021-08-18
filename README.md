# Stammtisch Bot 
Der Bot für den Discord Stammtisch (english version at bottom)

Prefix: **?** 

## Commands:

### Info

?about - Infos über den Bot

?help - zeigt verfügbare Befehle an

?stats - uptime, etc

?ping - Ping zu heroku


### Fun & commands (mosly NSFW)

?bondage - pullt von [r/bondage](https://old.reddit.com/r/bondage/ "r/bondage") einen random Post [NSFW]

?bigass - pullt von [r/bigasses](https://old.reddit.com/r/bigasses/ "r/bigasses") einen random Post [NSFW]

?bp - pullt von [r/BustyPetite](https://old.reddit.com/r/BustyPetite/ "r/BustyPetite") einen random Post [NSFW]

?btg - pullt von [r/bigtiddygothgf](https://old.reddit.com/r/bigtiddygothgf/ "r/bigtiddygothgf") einen random Post [NSFW]

?cock - pullt von [r/ratemycock](https://old.reddit.com/r/ratemycock/ "r/ratemycock") einen random Post [NSFW]

?hb - pullt von [r/hugeboobs](https://old.reddit.com/r/hugeboobs/ "r/hugeboobs") einen random Post [NSFW]

?hg - pullt von [r/HotGuys](https://old.reddit.com/r/HotGuys/ "r/HotGuys") einen random Post [NSFW]

?mtits - pullt von [r/MassiveTitsnAss](https://old.reddit.com/r/MassiveTitsnAss/ "r/MassiveTitsnAss") einen random Post [NSFW]

?pa - pullt von [r/ProgrammerAnimemes](https://old.reddit.com/r/ProgrammerAnimemes/ "r/ProgrammerAnimemes") einen random Post [NSFW]

?sg - pullt von [r/suicidegirls](https://old.reddit.com/r/suicidegirls/ "r/suicidegirls") einen random Post [NSFW]

?thicc - pullt von [r/thiccerthanyouthought](https://old.reddit.com/r/thiccerthanyouthought/ "r/thiccerthanyouthought") einen random Post [NSFW]


?trap - pullt von [r/traps](https://old.reddit.com/r/traps "r/traps") einen random Post [NSFW]

?pussy - pullt von [r/godpussy](https://old.reddit.com/r/godpussy "r/pussy") einen random Post [NSFW]

?ww - pullt von [r/wortwitzkasse](https://old.reddit.com/r/wortwitzkasse/ "r/wortwitzkasse") einen random Post 

?pod - Postet das NASA Picture of the day

?echo - echo



------------



# Self-hosting (Heroku)

1. Lade das repo als ein .zip file herunter und entpacke den Inhalt, wohin du möchtest.

2. Öffne einen Termin im Projekt, z.B.: `cd C:\github\stammtisch-bot-master`
und tippe: `npm install` um den Bot zu installieren

3. `client.login(process.env.BOT_TOKEN);` bei heroku unter `Settings => Config Vars` definieren: `BOT_TOKEN` = Value

4. Unter `Overview` den Bot als `worker` definieren

5. `Prefix` unter `config.json` definieren

Wenn alles funktioniert hat, kannst du den Bot mit `node app.js` ausführen.
