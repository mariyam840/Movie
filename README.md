
<details>
<summary><b>Features</b></summary>

- [x] Auto Filter
- [x] Manual Filter
- [x] IMDB
- [x] Admin Commands
- [x] Broadcast
- [x] Index
- [x] IMDB Search
- [x] Inline Search
- [x] Random Pics
- [x] Ids And User Info
- [x] Stats, Users, Chats, Ban, Unban, Leave, Disable, Channel
- [x] Spelling Check Feature
- [x] Custom File Caption
- [x] Group Broadcast 
- [x] AutoFilter Auto Delete
- [x] Junk Group & Users Clearing On Database
- [x] Global Filter
- [x] Url Shortner In Autofilter
- [x] Custom Button Lock
- [x] Image Editor & Background Remover
- [x] Telegraph, Pin, Json, Password Generator
- [x] Ban, Mute, Unmute, Etc... Group Manager
- [x] Custom Welcome Message
- [x] Advanced Admin Panel
- [x] Photo Changing In All Buttons
- [x] Custom Start Message
- [x] Custom Button Alter Message
- [x] Advanced Status (Disk, Cpu, Ram, Uptime..) In Image Type
</details>

<details>
<summary><b>Variables</b></summary>
  
### Required Variables
* `BOT_TOKEN`: Create a bot using [@BotFather](https://telegram.dog/BotFather), and get the Telegram API token.
* `API_ID`: Get this value from [telegram.org](https://my.telegram.org/apps)
* `API_HASH`: Get this value from [telegram.org](https://my.telegram.org/apps)
* `CHANNELS`: Username or ID of channel or group. Separate multiple IDs by space
* `ADMINS`: Username or ID of Admin. Separate multiple Admins by space
* `DATABASE_URL`: [mongoDB](https://www.mongodb.com) URI. Get this value from [mongoDB](https://www.mongodb.com). For more help watch this [video](https://youtu.be/1G1XwEOnxxo)
* `DATABASE_NAME`: Name of the database in [mongoDB](https://www.mongodb.com). For more help watch this [video](https://youtu.be/1G1XwEOnxxo)
* `LOG_CHANNEL` : A channel to log the activities of bot. Make sure bot is an admin in the channel.
* `SUPPORT_CHAT` : Username of a Support Group / ADMIN. ( Should be username without @ and not ID
  
### Optional Variables
* `PICS`: Telegraph links of images to show in start message.( Multiple images can be used seperated by space )
* `USE_CAPTION_FILTER` : Whether bot should use captions to improve search results. (True False)
* `CUSTOM_FILE_CAPTION` : A custom file caption for your files. formatable with , file_name, file_caption, file_size, Read Readme.md for better understanding
* `CACHE_TIME` : The maximum amount of time in seconds that the result of the inline query may be cached on the server
* `IMDB` : Imdb, the view of information when making True/False
* `SINGLE_BUTTON` : choose b/w single or double buttons 
* `P_TTI_SHOW_OFF` : Customize Result Buttons to Callback or Url by (True = url / False = callback)
### Url Shortner Variable
* `SHORT_URL` : Url Of Shortner Site You Use
* `SHORT_API` : Api Key Of Shortner Which You Use
</details>

<details>
<summary><b>Deploy to Heroku</b></summary>

<a href="https://youtu.be/uv0WHxwHwfo"><img src="https://img.shields.io/badge/watch%20Heroku%20Tutorial-red.svg?logo=Youtube"></a>                

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/mariyam840/Movie)
</details>
