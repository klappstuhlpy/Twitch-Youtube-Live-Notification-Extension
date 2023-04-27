### Twitch-Youtube-Live-Notification-Extension
Those are two "Extensions" written for the discord.py library where the Bot sends automatically a Message wheter a User is currently Live Streaming.


# Setup

### Example Folder Hierarchy
This is Important for the part in the Code where to access your "config.json" File.:

<pre>
YourBotFolder <- Second "parent" folder
    - cogs  <- First "parent" folder
        - twitch.py
        - youtube.py
    - main.py
    - config.json
</pre>


# API Keys?

### Twitch
To get a `Client ID` and a `Client Secret`, you need to got to https://dev.twitch.tv/console/extensions and create a new Extension.

### YouTube
In order use the `Youtube Data v3 API` you have to generate an API Key in the Google Cloud Protal at https://console.cloud.google.com/.
