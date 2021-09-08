## Video Compressor Bot

[![Deploy on Heroku](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/remxd/CompressQueue)

[![Deploy on Railway](https://railway.app/button.svg)](https://railway.app/new/template?template=https%3A%2F%2Fgithub.com%2FZylern%2FTGVidComp%2Ftree%2Fmain&plugins=redis&envs=API_HASH%2CAPP_ID%2CBOT_TOKEN%2CFFMPEG%2COWNER%2CTHUMBNAIL&optionalEnvs=APP_ID%2CAPI_HASH&FFMPEGDesc=ffmpeg+-i+'''{}'''+-preset+ultrafast+-c:v+libx265+-crf+27+-map+0:v+-c:a+aac+-map+0:a+-c:s+copy+-map+0:s?+''{}'''+-y)


### Variables
`APP_ID` `API_HASH` `BOT_TOKEN`

`OWNER` : Put Id Of Auth Users with a space between it

`THUMBNAIL` : Put telegraph link of a picture for use of Thumbnail.

`FFMPEG` : Put Your FFMPEG Code with "{}" as input and output. (Eg. `ffmpeg -i "{}" -preset veryfast -vcodec libx265 -crf 27 "{}"`)
