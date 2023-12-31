# YTFetch
A simple express app which allows you to view all source urls of a YouTube video to directly download it from Google's servers (API).

## 🖥️ Behavior
It fetches the video files from the YouTube API, then creates download buttons in each format (mp4 or mp3) so that you can download the fetched files directly.

## 📦 Dependencies
- [Express](https://expressjs.com/)
- [Typescript](https://www.typescriptlang.org/)
- [Pug](https://pugjs.org/)
- [ytdl-core](https://www.npmjs.com/package/ytdl-core)

## ⚙️ Source tree
[https://angelotrabuco2013.github.io/YTFetch/tree.html](https://angelotrabuco2013.github.io/YTFetch/tree.html)

## 💽 Installation
### Docker
```
$ sudo git clone https://github.com/angelotrabuco2013/YTFetch/YTFetch.git
$ cd YTFetch
$ sudo docker build -t angelotrabuco2013/YTFetch
$ sudo docker run angelotrabuco2013/YTFetch -e PORT=8601
```

### Manually
*Requires NodeJS 14 or higher*

```
$ sudo git clone https://github.com/angelotrabuco2013/YTFetch/YTFetch.git
$ cd YTFetch
$ sudo npm install
$ sudo npm run build
$ sudo npm run start
```
