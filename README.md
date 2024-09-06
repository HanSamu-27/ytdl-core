# YoutubeDL

![Youtube](https://i.postimg.cc/LXWmBnHM/images.png)

## Instalación

```bash
npm install github:HanSamu-27/ytdl-core

```

## Uso

```javascript
let { youtubedl } = require("ytdl-core")

let fileName = '@Samush_$.mp3' //nombre que se le pondra a los audios
let carp = './DWN/' //carpeta donde se guardaran los audios
(async () => {
let url = 'https://music.youtube.com/watch?v=s5MEYIp57Qw&si=Q8IAIN6cFbY8klVn'
let sophi = await youtubedl(url, carp, fileName)
if (sophi) {
console.log('• Titulo:', sophi.title)
console.log('• Imagen:', sophi.thumbnail)
console.log('• Guardado en:', sophi.save)
console.log('• Peso:', sophi.size)
} else {
console.log('://')
}})()
```

# Creador

[![Owner](https://i.postimg.cc/gjwt800Q/da32bf02-c5dc-40c4-9807-ffc85a956a13.jpg)](https://wa.me/+51910108980?text=Hola+Samu)
