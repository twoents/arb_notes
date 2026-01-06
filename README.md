Just a bunch of arbitary notes of stuff I keep forgetting and then have to lookup again. 

youtube-downloads, yt-dlp 

download video in specific resolution; in this case the video with the best quality that has a height of 480 pixels.\
..\yt-dlp.exe -f "bestvideo[height=480]+bestaudio/best" https://www.youtube.com/watch?v=CNPVxRvzW4c

download the audio only of certain video... I'm assuming this defaults to the best audio format but I've not confirmed\
..\yt-dlp.exe -x https://www.youtube.com/watch?v=FQUYF7HtxEE

don't gorget to look into\
* CDS and AOT to reduce memory footprint
* GraalVM compilation seems to reduce the memory consumption even more

Journaling setup for systemd ubuntu24
SystemMaxUse=500M (The total disk space all journals can take).
SystemMaxFileSize=100M (The maximum size of a single journal file before it rotates)


