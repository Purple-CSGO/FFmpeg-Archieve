# FFmpeg-Archieve
Repo to archieve ffmpeg executable files into .7z &lt;20MB in order to use jsdelivr to speed up.

**NOTE: This repo is manually maintained and I can't make sure it's the latest at all times.**

# API

If the latest version is `4.3.1` and u want to download windows 64bit static version:

```
https://cdn.jsdelivr.net/gh/Purple-CSGO/FFmpeg-Archieve/ffmpeg-4.3.1-win64-static.7z
```

or

```
https://cdn.jsdelivr.net/gh/Purple-CSGO/FFmpeg-Archieve@4.3.1/ffmpeg-4.3.1-win64-static.7z
```

If u are having trouble visiting GitHub API such as:

```
https://api.github.com/repos/FFmpeg/FFmpeg/tags
```

then this could be a backup solution:

```
https://cdn.jsdelivr.net/gh/Purple-CSGO/FFmpeg-Archieve/tags.json
```

# Win64

## Static Version

Removed `./bin/ffplay.exe` and `./bin/ffprobe.exe`

## Shared Version

All preserved

# MacOS

## Static Version

Removed `./bin/ffplay` and `./bin/ffprobe`

## Shared Version

All preserved

# Linux

## Static Version

Removed `./ffprobe` of `amd64` build.

> NOTE: have not testes yet if ffprobe removal makes ffmpeg unusable!!!

## Shared Version

All preserved