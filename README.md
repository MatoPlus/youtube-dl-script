# Overview
A simple shell script for youtube-dl for use in termux.

# Requirements
- termux access to shared storage via command: `termux-setup-storage`
- `python`
- `youtube-dl`
- an existing file at `~/.config/youtube-dl/config`
- a download folder set up as `~/storage/shared/Youtube`
- a download folder in `~/storage/music`

# Usage
1. Place script in the folder at `~/bin`
2. Go to any youtube video, press share with Termux 
3. The command line should pop up, choose convert options and wait for the download.
4. Done! The video should be in `~/storage/share/Youtube` (if converted to audio, the file will be in `~/storage/music`)
