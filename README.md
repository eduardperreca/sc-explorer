# sc-explorer
Plays the most commented 10 seconds of a random song on SoundCloud® and adds it to a playlist if you like it

## This script uses undocumented SoundCloud® APIs (since you cannot currently ask for an api key). Use it at your own risk! (theoretically your account might get banned)
## TODO
- TODO: better UI lol

## Credits
Idea taken from https://twitter.com/yush_g (https://github.com/Divide-By-0/ideas-for-projects-people-would-use)

## Installation
```console
$ pip install -r requirements.txt
$ echo YOUR_CLIENT_ID > client_id
$ echo YOUR_OAUTH_TOKEN > oauth
$ echo YOUR_RECAPTCHA_WEBSITE_KEY > website_key
$ echo YOUR_RECAPTCHA_SECRET > secret
$ flask --app sc-explorer run --debug
```

## Screenshots
https://imgur.com/a/ZDAE87z
