Just a bunch of arbitary notes of stuff I keep forgetting and then have to lookup again. 

youtube-downloads, yt-dlp 

download video in specific resolution; in this case the video with the best quality that has a height of 480 pixels.\
..\yt-dlp.exe -f "bestvideo[height=480]+bestaudio/best" https://www.youtube.com/watch?v=CNPVxRvzW4c

download the audio only of certain video... I'm assuming this defaults to the best audio format but I've not confirmed\
..\yt-dlp.exe -x https://www.youtube.com/watch?v=FQUYF7HtxEE

