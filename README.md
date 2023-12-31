# YTFetch
A simple express app which allows you to view all source urls of a YouTube video to directly download it from Google's servers (API).
[![Node.js CI](https://github.com/angelotrabuco2013/YTFetch/actions/workflows/node.js.yml/badge.svg)](https://github.com/angelotrabuco2013/YTFetch/actions/workflows/node.js.yml)

## 🖥️ Behavior
It sends an HTTP request to fetch the video files from the YouTube API (Google's servers), then creates download buttons in each format (MP4 for video, or MP3 for audio) so that you can get the fetched files directly. Also, the page has an embedded video to watch after conversion. If the API fails to process the video file, the fetching process will not suceeed.

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
