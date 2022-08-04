<p align="center">
<img src="https://github.com/DannGTH/RyuuBotZ V14/blob/v7.1/image/lol_1.jpg" alt="RyuuBotZ" width="100"/>


</p>
<p align="center">
<a href="#"><img title="RYUUBOT MULTI DEVICE" src="https://img.shields.io/badge/RyuuBotZ V14-green?colorA=%23ff0000&colorB=%23017e40&style=for-the-badge"></a>
</p>
<p align="center">
<a href="https://github.com/DannGTH"><img title="Author" src="https://img.shields.io/badge/Author-DannGTH-red.svg?style=for-the-badge&logo=github"></a>
</p>
<p align="center">
<a href="https://github.com/DannGTH/followers"><img title="Followers" src="https://img.shields.io/github/followers/DannGTH?color=red&style=flat-square"></a>
<a href="https://github.com/DannGTH/RyuuBotZ V14/stargazers/"><img title="Stars" src="https://img.shields.io/github/stars/DannGTH/RyuuBotZ V14?color=blue&style=flat-square"></a>
<a href="https://github.com/DannGTH/RyuuBotZ V14/network/members"><img title="Forks" src="https://img.shields.io/github/forks/DannGTH/RyuuBotZ V14?color=red&style=flat-square"></a>
<a href="https://github.com/DannGTH/RyuuBotZ V14/watchers"><img title="Watching" src="https://img.shields.io/github/watchers/DannGTH/RyuuBotZ V14?label=Watchers&color=blue&style=flat-square"></a>
<a href="https://github.com/DannGTH/RyuuBotZ V14"><img title="Open Source" src="https://badges.frapsoft.com/os/v2/open-source.svg?v=103"></a>
<a href="https://github.com/DannGTH/RyuuBotZ V14/"><img title="Size" src="https://img.shields.io/github/repo-size/DannGTH/RyuuBotZ V14?style=flat-square&color=green"></a>
<a href="https://hits.seeyoufarm.com"><img src="https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2FDannGTH%2FRyuuBotZ V14&count_bg=%2379C83D&title_bg=%23555555&icon=probot.svg&icon_color=%2300FF6D&title=hits&edge_flat=false"/></a>
<a href="https://github.com/DannGTH/RyuuBotZ V14/graphs/commit-activity"><img height="20" src="https://img.shields.io/badge/Maintained%3F-yes-green.svg"></a>&nbsp;&nbsp;
</p>

<p align="center">
  <a href="https://github.com/DannGTH/RyuuBotZ V14#requirements">Requirements</a> •
  <a href="https://github.com/DannGTH/RyuuBotZ V14#instalasi">Installation</a> •
  <a href="https://github.com/DannGTH/RyuuBotZ V14#thanks-to">Thanks to</a> •
  <a href="https://github.com/DannGTH/RyuuBotZ V14#Official-Group"> Official Group Bot</a> •
  <a href="https://github.com/DannGTH/RyuuBotZ V14#donate">Donate</a>
</p>
</div>


---

## Information
> Alpahbot-Md adalah bot yang awalnya memakai base dari [Chikabot](https://github.com/rashidsiregar28/chikabot/blob/main/README.md), sekarang pindah base [Hisoka-Morou](https://github.com/DikaArdnt/Hisoka-Morou). RyuuBotZ V14 is a bot whatsapp using a Baileys library.
> Jika kamu menemukan semacam bug, harap untuk dimaklumi sementara

# Requirements
* [Node.js](https://nodejs.org/en/)
* [Git](https://git-scm.com/downloads)
* [FFmpeg](https://github.com/BtbN/FFmpeg-Builds/releases/download/autobuild-2020-12-08-13-03/ffmpeg-n4.3.1-26-gca55240b8c-win64-gpl-4.3.zip) (for sticker command)

# Instalasi
## Heroku Buildpack
```bash
heroku/nodejs
https://github.com/jonathanong/heroku-buildpack-ffmpeg-latest
https://github.com/clhuang/heroku-buildpack-webp-binaries.git
```

## How to Get Mongodb URI
- Tonton [Di YouTube](https://youtu.be/M8H9S3djxTg)
<img src="https://telegra.ph/file/682c1315ff9a43bb1a724.jpg" width="300">
- Jika sudah memiliki database mongoDB ikuti tutorial di bawah

## HOW TO CONNECT TO MONGODB

- Salin Url database mongoDB
- Constoh `worker: node . --db 'Link Database MongoDb'`
- Contoh `worker: node . --db 'mongodb+srv://mongodb-bot:abcdefghij@zeeoneofc.aWpl9.mongodb.net/?retryWrites=true&w=majority'`

## For Termux
- Download script MediaFire [Here](https://telegra.ph/RyuuBotZ V14-V14-08-02)
- Cara install tonton Di [YouTube](https://youtu.be/ep_PM1PpEVg)

## Edit file
`./settings.js`
```ts
global.autoread = false // auto read pesan / message
global.autorecording = true //status auto merekam ( auto record )
global.autoketik = false //status auto mengetik (auto typing)
global.available = false //status online (online)

// Other
global.botname = "RyuuBotZ V14ོ"
global.ownername= "DannBotZ"
global.myweb ="https://api-alphabot.herokuapp.com/"
global.youtube = "https://youtube.com/c/DannYT"
global.github = "https://DannGTH.github.io/"
global.email = "rowraagency099@gmail.com"
global.region = "Indonesia"
global.ownernomer = "62887435047326"
global.ownernomerr = "+62887435047326"
global.thumbnail = "./image/lol.jpg"
global.donasi = "./image/donasi.jpg"
global.background_welcome="https://telegra.ph/file/90a931648de597820bc08.jpg" // maks size 30kb, agar welcome image nya tdk delay
global.owner = ["62887435047326","62887435047326","6285342106390"] //ganti agar fitur owner bisa di gunakan
global.packname = '© RyuuBotZ V14ོ' //sticker wm
global.author = 'Di Buat Oleh DannBotZ' //sticker wm
global.sessionName = 'session'
```

## ```HOW TO DEPLOY```

[`Click Here For Tutorial`](https://youtu.be/SdKHkld2NcI)<br>

----------

<p align="center">
  <a href="https://youtu.be/SdKHkld2NcI"><img src="https://a.top4top.io/p_2081imvxm1.jpg" />
</p>

## Donate
- [Pulsa](085810172953)
- [Dana](085880124597)
- [Gopay](085810172953)

# Official Group
- [Group 1](https://chat.whatsapp.com/EU890BcXjyBDkNaUT5WmYV)
- [Group 2](https://chat.whatsapp.com/E8NExJwIbhBJYzssfqJNsE)
- [Group 3](https://chat.whatsapp.com/KCSqHTky1apG7ApePsfiPy)
- [Group 4](https://chat.whatsapp.com/KwmvHr7VMFj7r5ry9xmMsU)
- [Group 5](https://chat.whatsapp.com/ELa7GhU0sP4EvXcVimQYtz)

# Thanks to
<a href="https://github.com/DikaArdnt"><img src="https://github.com/DikaArdnt.png?size=100" width="100" height="100"></a> | [![NURUTOMO](https://github.com/Nurutomo.png?size=100)](https://github.com/Nurutomo) 
---|---
[Dika](https://github.com/DikaArdnt)  | [Nurutomo](https://github.com/Nurutomo)
Owner Hisoka-Morou | Constributor |
<a href="https://github.com/MhankBarBar"><img src="https://github.com/MhankBarBar.png?size=100" width="100" height="100"></a> | [![FATIH](https://github.com/fatiharridho.png?size=100)](https://github.com/fatiharridho) 
[Mhankbarbar](https://github.com/MhankBarBar)  | [Fatih A.](https://github.com/fatiharridho)
Constributor | For Help |
<a href="https://github.com/FERDIZ-afk"><img src="https://github.com/FERDIZ-afk.png?size=100" width="100" height="100"></a> | [![RASHID](http://github.com/rashidsiregar28.png?size=100)](http://github.com/rashidsiregar28) 
[Ferdiz](https://github.com/FERDIZ-afk)  | [Rashid](https://github.com/rashidsiregar28)
For Help | Owner RyuuBotZ |
<a href="https://github.com/adiwajshing"><img src="https://github.com/adiwajshing.png?size=100" width="100" height="100"></a> | [![ZEEONE](http://github.com/DannGTH.png?size=100)](http://github.com/DannGTH) 
[Adiwajshing](https://github.com/adiwajshing) | [DannGTH](https://DannGTH.github.io)
Owner of Baileys | Owner of Api Alphabot |

