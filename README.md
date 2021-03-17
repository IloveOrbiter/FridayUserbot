## Repl
[![Run on Repl.it](https://repl.it/badge/github/STARKGANG/friday)](https://friday.midhunkm1294.repl.run)

# Deploying To Heroku

[![Deploy To Heroku](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/IloveOrbiter/FridayUserbot)

# Self-hosting (For Devs)

### If You Want Modules Like Image / Vid Tools To Work You Need To Install These:
```
$ ffmpeg
$ Open CV
$ Chrome Driver
$ Chrome
$ gifsicle
$ mediainfo
```

# Mandatory Configs
```
[+] Make Sure You Add All These Mandatory Vars. 
    [-] APP_ID:   You can get this value from https://my.telegram.org
    [-] API_HASH :   You can get this value from https://my.telegram.org
    [-] STRING_SESSION : Your String Session, You can get this From Repl or BY running StringGen File Locally
    [-] TG_BOT_TOKEN_BF_HER : Your Bot Token Obtained From @BotFather 
    [-] PRIVATE_GROUP_ID : Id of group where you wanna log important logs, Private group is recommended for this
    [-] DATABASE_URL: Data Base Url, You Can Make You Own By Following This Tutorial - https://www.digitalocean.com/community/tutorials/how-to-install-and-use-postgresql-on-ubuntu-18-04, Else Get this from Elephant Sql, Or You can even make a heroku app to get Free DataBase.
[+] The userbot will not work without setting the mandatory vars.
```


## An Example Of "local.env" File.
```
APP_ID=2877510
API_HASH="fb6e6a1d96f3e6ea1b8e293912bd2edf"
STRING_SESSION="1AZWarzkBu6awXELYNW1w9xUMBt4OKtuOyMXX50ut5fUZ0oMo-0Qcp-GPDDc6YomgR7YdIL4woqQPHxpIvq6AXfPVbSeMN4nj_89Y03NSuDcEVOMhuJkfA6tTVUVPlkh4cQDgIwygG9GUYCAyntL4OvDIjLjNpkI68aSIrB9xChqa6T4uqn74AgRoUvN_5SQ0Y5F2Z6fz7UluwC33j0TuPMOWAdrcSooiIcjxe3WKtao6xz6-dWd0085sND8liyAdDrSQymzSC98kXx1Evo2GJG9matA6aGEyxNW_awuKB5Djjm6wkLszuYVuc03oeD9WNlyFtA-d_bd9Ge-TIScItpkiM8r4CCo="
TG_BOT_TOKEN_BF_HER="1651787609:AAFT8tyKb_h1kSS7zFLJ8Uqx3wmesqIUjls"
PRIVATE_GROUP_ID=-100535552668
DATABASE_URL="postgres://jchzxwhkwuhbldjnxqfp:142.compute1.amazonaws.com:5432/d14c1pas7r1clf"
```
