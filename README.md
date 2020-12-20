# yt-audio
---
## DESCRIPTION
> **yt-audio** is a simple script to download audio from YouTube.com and a few more sites. It uses **_youtube-dl_** program (**_so first install it_**).
## MAKE IT EXECUTABLE
first clone this repo:
```bash
git clone https://github.com/ilvghst/yt-audio.git
cd yt-audio && chmod +x yt-audio
```

## USAGE:
```
yt-audio [--add-link <OPTIONAL>] [--directory <OPTIONAL>] [--help]
```
## OPTIONS
```
 -h, --help:         Prints help
 -a, --add-link:     Add link to songs.txt file (default: 'no default')
 -d, --directory:    Directory to save downloaded audio (default: './')	
```
## EXAMPLE
First add url: (add as many url you like)
```bash
yt-audio -a YOUTUBE_URL1
yt-audio -a YOUTUBE_URL2
...
```
Then:
_if you want to specify directory_
```bash
yt-audio -d /path/to/dir
```
_if you don't want to specify directory_
```bash
yt-audio
```
**Above command will download audio in current directory**
# TODO
1. **_Stop writing shitty code(s)_**
2. **_Try my best to stop writing shitty script(s)_**
3. **_Learn more and more.._**
# THANK YOU
`thank you for your precious time ` :blush: .
