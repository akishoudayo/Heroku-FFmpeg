# heroku-ffmpeg-stable

Push: [![Test](https://github.com/akishoudayo/ffmpeg-heroku/workflows/Test/badge.svg?branch=master&event=push)](https://github.com/akishoudayo/ffmpeg-heroku/actions?query=workflow%3ATest+event%3Apush+branch%3Amaster)  
Scheduled: [![Test](https://github.com/akishoudayo/ffmpeg-heroku/workflows/Test/badge.svg?branch=master&event=schedule)](https://github.com/akishoudayo/ffmpeg-heroku/actions?query=workflow%3ATest+event%3Aschedule+branch%3Amaster)

## Why I created this repository?
Because the ffmpeg download server was not stable.
So, I created this repository to change the url to stable one.

## Usage

```
heroku buildpacks:add --index 1 https://github.com/akishoudayo/ffmpeg-heroku.git
```
or Add to buildpack
`https://github.com/akishoudayo/ffmpeg-heroku.git`

