# AuraXMusic TELEGRAM VC MUSIC BOT 
[![AuraXMusic logo](https://telegra.ph/file/d21963be67c93841589ee.jpg)](https://t.me/AuraXNetwork)


-It is inspired from su music project and hamkercat's telegram voice bot.
Neither su music project , nor pytgcalls are stable


<p align="center">
<a href="https://app.codacy.com/gh/AuraXNetwork/AuraXMusic?utm_source=github.com&utm_medium=referral&utm_content=AuraXNetwork/AuraXMusic&utm_campaign=Badge_Grade_Settings" alt="Codacy Badge">
<img src="https://api.codacy.com/project/badge/Grade/6141417ceaf84545bab6bd671503df51" /> </a>
<a href="https://github.com/AuraXNetwork/AuraXMusic" alt="Libraries.io dependency status for GitHub repo"> <img src="https://img.shields.io/librariesio/github/AuraXNetwork/AuraXMusic" /> </a>
<a href="http://hits.dwyl.com/AuraXNetwork/AuraXMusic" alt="HitCount"> <img src="http://hits.dwyl.com/AuraXNetwork/AuraXMusic.svg" /> </a>
</p>
<p align="center">
<a href="https://github.com/AuraXNetwork/AuraXMusic" alt="GitHub closed issues"> <img src="https://img.shields.io/github/issues-closed-raw/AuraXNetwork/AuraXMusic?style=flat&logo=github&color=success" /> </a>
<a href="https://github.com/AuraXNetwork/AuraXMusic" alt="GitHub commit activity"> <img src="https://img.shields.io/github/commit-activity/m/AuraXNetwork/AuraXMusic" /> </a>
<a href="https://github.com/AuraXNetwork/AuraXMusic/graphs/contributors" alt="GitHub contributors"> <img src="https://img.shields.io/github/contributors/AuraXNetwork/AuraXMusic?style=flat&logo=github" /> </a>
<a href="https://github.com/AuraXNetwork/AuraXMusic/network/members" alt="GitHub forks"> <img src="https://img.shields.io/github/forks/AuraXNetwork/AuraXMusic?label=Forks&logo=github" /> </a>
<a href="https://github.com/AuraXNetwork/AuraXMusic" alt="GitHub closed pull requests"> <img src="https://img.shields.io/github/issues-pr-closed-raw/AuraXNetwork/AuraXMusic?color=success" /> </a>
<a href="https://github.com/AuraXNetwork/AuraXMusic" alt="GitHub issues"> <img src="https://img.shields.io/github/issues-raw/AuraXNetwork/AuraXMusic?style=flat&logo=github&color=yellow" /> </a>
</p>
<p align="center">
<a href="https://github.com/AuraXNetwork/AuraXMusic" alt="GitHub release (latest by date including pre-releases)"> <img src="https://img.shields.io/github/v/release/AuraXNetwork/AuraXMusic?include_prereleases?style=flat&logo=github" /> </a>
<a href="https://www.python.org/" alt="made-with-python"> <img src="https://img.shields.io/badge/Made%20with-Python-1f425f.svg?style=flat&logo=python&color=blue" /> </a>
<a href="https://github.com/AuraXNetwork/AuraXMusic" alt="Docker!"> <img src="https://aleen42.github.io/badges/src/docker.svg" /> </a>
<a href="https://github.com/AuraXNetwork/AuraXMusic" alt="GitHub repo size"> <img src="https://img.shields.io/github/repo-size/AuraXNetwork/AuraXMusic" /> </a>
<a href="https://github.com/AuraXNetwork/AuraXMusic/blob/master/LICENSE" alt="GPLv3 license"> <img src="https://img.shields.io/badge/License-GPLv3-blue.svg" /> </a>
</p>
<p align="center">
<a href="https://t.me/AuraXMusicUpdates" alt="Telegram!"> <img src="https://aleen42.github.io/badges/src/telegram.svg" /> </a>
<a href="https://github.com/AuraXNetwork/AuraXMusic/graphs/commit-activity" alt="Maintenance"> <img src="https://img.shields.io/badge/Maintained%3F-yes-green.svg" /> </a>
<a href="https://makeapullrequest.com" alt="PRs Welcome"> <img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square" /> </a>
</p>


## Requirements

- FFmpeg
- NodeJS [nodesource.com](https://nodesource.com/)
- Python 3.7+
- [PyTgCalls](https://github.com/pytgcalls/pytgcalls)

## Deployment

### Config

Copy `example.env` to `.env` and fill it with your credentials.

### Without Docker

1. Install Python requirements:
   ```bash
   pip install -r requirements.txt
   ```
2. Run:
   ```bash
   python main.py
   ```

### Using Docker

1. Build:
   ```bash
   docker build -t musicplayer .
   ```
2. Run:
   ```bash
   docker run --env-file .env musicplayer
   ```

### Heroku
 [![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/AuraXNetwork/AuraXMusic.git)

### StringSession

[![GenerateString](https://img.shields.io/badge/repl.it-generateString-yellowgreen)](https://replit.com/@itzgauravv/AuraXVCBot#main.py) 


### Commands 🛠
#### For all in group
- `/play <song name>` - play song you requested
- `/dplay <song name>` - play song you requested via deezer
- `/splay <song name>` - play song you requested via jio saavn
- `/playlist` - Show now playing list
- `/current` - Show now playing
- `/song <song name>` - download songs you want quickly
- `/search <query>` - search videos on youtube with details
- `/deezer <song name>` - download songs you want quickly via deezer
- `/saavn <song name>` - download songs you want quickly via saavn
- `/video <song name>` - download videos you want quickly


#### Admins only
- `/player` - open music player settings panel
- `/pause` - pause song play
- `/resume` - resume song play
- `/skip` - play next song
- `/end` - stop music play
- `/userbotjoin` - invite assistant to your chat
- `/userbotleave` - remove assistant from your chat
- `/admincache` - Refresh admin list

- Inline search is also supported.

* Bot Link:  <a href="https://t.me/AuraXMusic" alt="AuraXMusic"> <img src="https://img.shields.io/badge/%F0%9F%A4%96%20-AuraXMusic-blue" /> </a>
* News channel: <a  href="https://t.me/AuraXUpdates" alt="AuraXMusic Updates"> <img  src="https://img.shields.io/badge/%F0%9F%92%A1-AuraXMusic%20Updates-9cf" /> </a>

## Support
- [Channel](https://t.me/AuraXNetwork)
- [Group](https://t.me/AuraXSupport)

## Credits
- [InukaASiTH](https://github.com/InukaAsith)
- [hamker cat](https://github.com/thehamkercat/Telegram_VC_Bot)
- [Roj](https://github.com/rojserbest)
- [Marvin](https://github.com/BlackStoneReborn)
- [Laky](https://github.com/Laky-64) & [Andrew](https://github.com/AndrewLaneX): PyTgCalls
