# YoutubeDL

![Youtube](https://i.postimg.cc/LXWmBnHM/images.png)

## Instalación

```bash
npm install github:HanSamu-27/ytdl-core

```

## Uso

```javascript
const { youtubedl } = require('ytdl-core')

const url = 'https://music.youtube.com/watch?v=Ci-DnZf1bhI&si=De4lrDZzUDqsXCwB'

youtubedl(url).then(result => {
console.log(result)
}).catch(error => {
console.error('://')
})

//Result:
/*{
  title: 'Who Can It Be Now?',
  artist: 'Men at Work - Topic',
  image: 'https://i.ytimg.com/vi_webp/Ci-DnZf1bhI/maxresdefault.webp',
  link: 'https://a.uguu.se/VDfFxRTf.mp3'
}*/
```

# Creador

[![Owner](https://i.postimg.cc/gjwt800Q/da32bf02-c5dc-40c4-9807-ffc85a956a13.jpg)](https://wa.me/+51910108980?text=Hola+Samu)
