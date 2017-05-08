# Groupify
A crowdsourced, crowdcurated DJ!
Created at DandyHacks 2017!

# .env Setup
Ensure to configure this file with Spotify and MariaDB credentials prior to deployment.

```
USERNAME=root
PASSWORD=

SLACK_TOKEN=
SLACK_URI=

SPOTIFY_CLIENT_ID=
SPOTIFY_CLIENT_SECRET=
SPOTIFY_REDIRECT_URI=

SPOTIFY_ACCESS_TOKEN=

SPOTIFY_PLAYLIST_ID=
SPOTIFY_USER_ID=

TIME_STAMP=0
```

# Setup
## Arch Linux
* npm install
* systemctl start mysqld
* npm start
## Amazon Linux
* npm install
* sudo service mysqld start
* npm start

# TODO
- [ ] dynamic refresh
- [ ] drop-down song search
- [ ] masonary UI
- [ ] different parties

Enjoy :)
