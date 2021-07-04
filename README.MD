# mention-all-bot

mention-all-bot is a telegram bot that helps to mention all users in a group.

## Deploy
<a href="https://heroku.com/deploy?template=https://github.com/justteen/mentionbot"> <img src="https://img.shields.io/badge/Deploy%20To%20Heroku-red?style=for-the-badge&logo=heroku" width="220" height="38.45"/></a></p>

Everyone who wants to receive notifications opts-in using /in

Now you can call everyone with /all

Commands:

```
/start - Display help text
/in - Opt-in to receive mentions
/out - Opt-out of receiving mentions
/all - Mention all opted-in users
/stats - Display bot stats
```

## Installation

```bash
# clone the repo
git clone https://github.com/pischule/mention-all-bot.git
cd mention-all-bot

# set your bot token and db password
echo "TGBOT_TOKEN=????????" > .env
echo "DB_PWD=????????" > .env

# run the app
docker-compose up -d
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
GNU GPLv3
