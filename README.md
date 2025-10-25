# puush-spectacle
Integration of puush with spectacle. Mainly personal use, but do whatever you want with it.

## Info
This repo is mainly for personal use, but free for others to use, modify, do whatever.

## Requirements
- wl-clipboard
- spectacle

## Usage
I have both `puush` and `puush-screenshot` inside `~/.local/bin` and add it to path.

Also, change `PUUSH_API_KEY` in the file `puush` to your own key, and `chmod +x` to everything I guess.

Usage method I use below.

### From terminal
```
puush /path/to/file
```

### From spectacle
Add keyboard shortcut in shortcut settings to run `puush-screenshot` command, and either "Save" or "Accept" to upload to puush. If you only want to copy to clipboard, just click "copy" instead.

### Right click menu (Dolphin)
Create the directory if it doesn't exist and paste the `.desktop` menu file.
```
~/.local/share/kio/servicemenus/puush.desktop
```

Restart dolphin
```
killall dolphin
```

