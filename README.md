# FEEDBACK CHATBOT
A simple feed-back bot written in [Boting](https://github.com/Quiec/Boting). It is similar to the Livegram bot.

## Install
### Easy
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

### Hard
```sh
git clone https://github.com/bot-developer03/feedback
cd feedback
composer install
nano .env
# Create and edit env file #
php bot.php
```

## Example Env File
```env
DB_TUR="json"
BOT_TOKEN="BOT TOKEN"
ADMIN_ID="ID'IN"
```

## Features
* Suitable for privacy settings
* Heroku support
* JSON Language File (We can edit the articles inside.)

## Commands
### /link
It gives the user's username (if any), and also gives the user a link that can be reached.
