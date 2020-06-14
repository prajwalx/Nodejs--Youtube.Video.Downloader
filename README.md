# NodeJs - Youtube Video Downloader
The best use case of Nodejs is its ability to stream content in chunks using pipes . This app is developed to use this feature to create a Media Downloader in Nodejs for downloading Video / Audio files from Youtube . Since downloading from youtube is not allowed, we use the popular youtube-dl as a child process in our application.

# Preview
![](https://github.com/prajwalx/Nodejs--Youtube.Video.Downloader/blob/master/public/images/ezgif.com-gif-maker.gif)

## Getting Started

### Prerequisites

- [Git](https://git-scm.com/)
- [Node.js and npm](nodejs.org) Node ^13.0.1, npm ^6.12.0
- [Youtube-dl](https://ytdl-org.github.io/youtube-dl/download.html)
- [FFmpeg](https://ffmpeg.zeranoe.com/builds/)
- Run `youtube-dl --version` to check if Youtube-dl is installed correctly.
- Run `ffmpeg -version` to check if FFmpeg is installed correctly.
- Proceed only if above 2 packages are installed correctly and versions are displayed in terminal.
- Create your own [Youtube API KEY](https://developers.google.com/youtube/v3/getting-started) for   getting search results for queries. It's free of cost. Dont worry :)
- Goto `routes/youtube_search.js` and update `const YOUTUBE_API_KEY = ' YOUR - API - KEY - HERE';`

### Developing

1. Run `npm install` to install server dependencies.

2. Run `npm start` to start the development server.

3. Open your favorite browser and goto `localhost:3000`

4. Search for any video and enjoy your download :)