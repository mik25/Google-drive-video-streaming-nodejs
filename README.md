# Google-drive-video-streaming-nodejs
This is a small script in nodejs that allow you to watch a video stored into your Google drive directly into your video player.

### Install
You need only to install all the dependencies typing this command:
```bash
npm install
```


### Usage
Just type this command to startup the script:
```bash
node ./app.js
```
Now that the server is started you can start watching your video or pre-download it.

#### Streaming
Paste this link into your player to start watching the video in streaming
```bash
http://127.0.0.1:8998/<google-drive-video-id>
```
#### Pre-download
To pre-download it first, type this url into a new broser tab
```bash
http://127.0.0.1:8998/<google-drive-video-id>/predownload
```
if you want you can specify the parameter p, that indicate in percentage what portion of video will be skipped.
For example to pre-download the video from half you should use this link

```bash
http://127.0.0.1:8998/<google-drive-video-id>/predownload?p=50
```

To stop the pre-downloading process just close the browser tab.
