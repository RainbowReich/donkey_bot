# donkey_bot
My custom Twitch chat bot

Experimenting with making custom commands and interactions for myself, rather than selling out and using Nightbot
or something similar DansGame

### Requirements

1. Python
2. SQLAlchemy

### Utilities

Use the `reset_db.py` script to drop and rebuild your database (as identified by your DB_URL variable) based on the
contents of the `models.py` file. Hopefully this works with other databases besides sqlite3.

### Current priorities

1. Add tests/documentation
2. Organize commands into those only the broadcaster can use vs public commands
3. Codify Twitch IRC message formats to allow the system to be a bit more deterministic
4. !AFK tweaks to work for anyone (deprecate !back, allow customization of welcome back message)
5. Add new features and other fun stuff!

### To see donkey_bot in action

Check out my [Twitch channel](http://www.twitch.tv/thermaldonkey) when I go live (donkey_bot is disabled
when I'm offline). I always [tweet](https://twitter.com/_thermaldonkey) when I start a broadcast.

### Contributing

Feel free to fork and send me pull requests with features you think would be cool!
