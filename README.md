<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">
<h3><img  style="align-item" :"center" src="https://telegra.ph/file/c8feb585b6b277f9242c6.jpg" width="80px" height="70%"><img src="https://readme-typing-svg.herokuapp.com?color=00BFFF&width=620&lines=✨+🦋+𝐇𝐄𝐘+𝐓𝐇𝐄𝐑𝐄+𝐓𝐇𝐈𝐒+𝐈𝐒+𝗖𝗛𝗔𝗟𝗖𝗢𝗚𝗘𝗡+𝐗𝐃+🖤+🥀"></b></h3>
<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">
<!-- 👁 Visitor Counter -->
<p align="center">
  <img src="https://komarev.com/ghpvc/?username=CertifiedCoders&style=flat-square" />
</p>
<h1 align ="center"><img src="https://readme-typing-svg.herokuapp.com?color=F778A1&width=350&lines=✨+🦋+𝐌𝐔𝐒𝐈𝐂+𝐁𝐎𝐓🖤+🥀"></b></h1>
<p align="center"><a href="https://t.me/CHALCOGENXD"><img src="https://telegra.ph/file/9b216a63b96955753dca6.jpg" width="600"></a></p>
  <a href="https://t.me/zaara_support"><img src="https://img.shields.io/badge/Support%20Channel-blue?style=for-the-badge&logo=telegram&logoColor=white&link=https://t.me/zaara_support" alt="Support Channel"></a>
  <a href="https://t.me/international_besties_chatting"><img src="https://img.shields.io/badge/Support%20Group-blue?style=for-the-badge&logo=telegram&logoColor=white" alt="Support Group"></a>
  <a href="https://t.me/fuck_of_bitches"><img src="https://img.shields.io/badge/Owner-purple?style=for-the-badge&logo=telegram&logoColor=white" alt="Owner"></a>
</p>

<p align="center">
  <a href="https://github.com/Silenthrax/SHRUTI/fork"><img src="https://img.shields.io/github/forks/NoxxOP/ShrutiMusic?style=social" alt="GitHub Forks"></a>
  <a href="https://github.com/NoxxOP/ShrutiMusic/stargazers"><img src="https://img.shields.io/github/stars/NoxxOP/ShrutiMusic?style=social" alt="GitHub Stars"></a>
  <a href="https://github.com/NoxxOP/ShrutiMusic/graphs/contributors"><img src="https://img.shields.io/github/contributors/NoxxOP/ShrutiMusic?style=social" alt="GitHub Contributors"></a>
</p>

<p align="center">
<a href="https://dashboard.heroku.com/new?template=https://github.com/Silenthrax/SHRUTI"><img src="https://img.shields.io/badge/Deploy%20To%20Heroku-purple?style=for-the-badge&logo=heroku&logoColor=white" width="250px" alt="Deploy to Heroku"></a>
</p>

## ✨ Features

- **Play Music**: Stream high-quality music in Telegram voice chats
- **Multiple Sources**: YouTube, Spotify, SoundCloud, and local files
- **Playlists**: Create and manage playlists for your group
- **Multi-Language**: Available in multiple languages
- **Elegant UI**: Clean and modern user interface
- **Group Management**: Powerful admin commands
- **High Quality**: Crystal clear audio streaming

## 📊 Repository Stats

<p align="center">
  <a href="https://github.com/NoxxOP/ShrutiMusic"><img src="https://img.shields.io/github/repo-size/NoxxOP/ShrutiMusic?style=flat-square" alt="Repo Size"></a>
  <a href="https://github.com/NoxxOP/ShrutiMusic/issues"><img src="https://img.shields.io/github/issues/NoxxOP/ShrutiMusic?style=flat-square" alt="Issues"></a>
  <a href="https://github.com/NoxxOP/ShrutiMusic/network/members"><img src="https://img.shields.io/github/forks/NoxxOP/ShrutiMusic?style=flat-square" alt="Forks"></a>
  <a href="https://github.com/NoxxOP/ShrutiMusic/stargazers"><img src="https://img.shields.io/github/stars/NoxxOP/ShrutiMusic?style=flat-square" alt="Stars"></a>
  <a href="https://github.com/NoxxOP/ShrutiMusic/blob/main/LICENSE"><img src="https://img.shields.io/github/license/NoxxOP/ShrutiMusic?style=flat-square" alt="LICENSE"></a>
  <a href="https://github.com/NoxxOP/ShrutiMusic/commits/main"><img src="https://img.shields.io/github/last-commit/NoxxOP/ShrutiMusic?style=flat-square" alt="Last Commit"></a>
</p>

## 🔥 Essential Commands

| Command | Description |
| --- | --- |
| `/play` | Play song from YouTube |
| `/pause` | Pause the current stream |
| `/resume` | Resume the paused stream |
| `/skip` | Skip to the next song |
| `/stop` | Stop the streaming |
| `/playlist` | Show the playlist |
| `/song` | Download a song as audio |
| `/settings` | Open bot settings |

## 🚀 Deployment Guide

### 🔧 VPS Deployment (Step by Step)

#### Prerequisites

First, update your system and install required packages:

```bash
sudo apt-get update && sudo apt-get upgrade -y
sudo apt-get install python3-pip ffmpeg git -y
```

#### Clone the Repository

```bash
git clone https://github.com/NoxxOP/ShrutiMusicBot
cd ShrutiMusicBot
```

#### Setup Virtual Environment

```bash
python3 -m venv venv
source venv/bin/activate
```

#### Install Dependencies

```bash
pip3 install -U pip
pip3 install -U -r requirements.txt
```

#### Configuration

Copy example config file and edit it with your values:

```bash
cp sample.env .env
nano .env
```

Fill in your:
- `API_ID` & `API_HASH` from my.telegram.org
- `BOT_TOKEN` from @BotFather
- `SESSION_STRING` (Generate using session generator bot)
- `MUSIC_BOT_NAME` (your bot name)
- `SUDO_USERS` (your user ID)

#### Starting the Bot

There are two ways to start the bot:

1. Using Python directly:
```bash
python3 -m ShrutiMusic
```

2. Using Bash script:
```bash
bash start
```

#### Running in Background with Screen

To keep the bot running in background:

```bash
screen -S shrutibot
bash start
```

To detach the screen, press `Ctrl+A` then `D`

To reattach the screen later:
```bash
screen -r shrutibot
```

### ☁️ Heroku Deployment

<p align="center">
<a href="https://dashboard.heroku.com/new?template=https://github.com/NoxxOP/ShrutiMusic"><img src="https://img.shields.io/badge/Deploy%20To%20Heroku-purple?style=for-the-badge&logo=heroku&logoColor=white" width="250px" alt="Deploy to Heroku"></a>
</p>

1. Click the button above
2. Fill in the required details:
   - App name
   - API_ID & API_HASH
   - BOT_TOKEN
   - MUSIC_BOT_NAME
   - SESSION_STRING
   - SUDO_USERS (your User ID)
3. Click "Deploy App"
4. Once deployed, go to Resources tab and turn on the worker

## 🔄 How to Generate Session String

Use our Session Generator Bot: [@ShrutiSessionBot](https://t.me/ShrutiSessionBot)

1. Start the bot
2. Send phone number with country code
3. Enter the OTP
4. Your session string will be generated

## 🤔 Common Issues & Fixes

- **Bot not responding**: Check if the bot is running and has proper permissions
- **No sound in VC**: Ensure ffmpeg is properly installed
- **Can't join voice chat**: Make sure the bot is an admin with voice chat permissions
- **API Issues**: Double check your API_ID and API_HASH

## 🌟 Credits and Acknowledgements

- [NoxxOP](https://github.com/NoxxOP): Main Developer
- All contributors who helped make this project better

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📞 Support

For any questions or help, join our [Support Group](https://t.me/ShrutiBotSupport)

<p align="center">
<img src="https://img.shields.io/badge/Made%20with%20%E2%9D%A4%EF%B8%8F%20by-NoxxOP-red?style=for-the-badge" alt="Made with love">
</p>

---

<p align="center">
<b>🎵 Enjoy Streaming Music with Shruti Bot! 🎵</b>
</p>
