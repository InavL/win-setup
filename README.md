# New windows install

## General

### [Firefox](https://www.mozilla.org/sv-SE/firefox/new/)
My browser of choice. I just like that I can really go full Frankenstein on it.

### [IrfanView](https://www.irfanview.com/)
A gazillion times faster image viewer than the built in Photos app.

### [Everything](https://www.voidtools.com/)
The best tool to find any file on your computer. Stupid fast.

### [7-zip](https://www.7-zip.org/)
My preferred zip-file tool. WinRar works well but I like open source.

### [Discord](https://discord.com/)
This is how I talk with friends.

### [Geforce Experience](https://www.nvidia.com/sv-se/geforce/geforce-experience/)
I like it when my graphics drivers are up to date.

### [NordVPN](https://nordvpn.com/)
I fell for the ads you know.

### [OBS Studio](https://obsproject.com/)
For recording and streaming. Or faking a webcam.

### [ShareX](https://getsharex.com/)
Loads of functionality. I mostly use it for screenshoting snippets and holding the contents in the clipboard for easy pasting. It also has a color picker, hash check, qr code scanner etc.

### [SumatraPDF](https://www.sumatrapdfreader.org/free-pdf-reader)
Sumatra is another blazing fast, can do most things, pdf-reader. I really dislike Acrobat Reader.

### [Ueli](https://ueli.app/)
Smart quick access to any application. Alt+space and there you are. Really handy.

## Code

### [Visual Studio Code](https://code.visualstudio.com/)
My preferred IDE. Great customization abilities and user support. If you prefer there is also VSCodium.

### [Windows Terminal](https://www.microsoft.com/en-us/p/windows-terminal/9n0dx20hk701)
Microsoft's new and improved terminal. It's much better than the built in one.

### [WSL](https://docs.microsoft.com/en-us/windows/wsl/install)
I do most work on my Mac but when I do work on windows I use WSL through VS Code and the terminal.

### [Ubuntu](https://www.microsoft.com/en-us/p/ubuntu/9nblggh4msv6)
Just download the latest flavour of Ubuntu from the Microsoft Store. Weird sentence right?

### [Scoop](https://scoop.sh/)
A command-line installer. I use it for Spotify, git and GOG integrations.

### [Voicemeeter Banana](https://vb-audio.com/Voicemeeter/banana.htm)
A very powerful audio manager software. I use a base compressor and an audio gate. I also use it to split my communication sounds from the rest of the computers audio to get a better game-sharing experience with Parsec.

## Maintenance

### [Bleachbit](https://www.bleachbit.org/)
It's like CCleaner but you know not filled with adware.

### [Malwarebytes](https://www.malwarebytes.com/)
A good malware scanner. Free version is well enough for a scan every third month or such.

### [Wiztree](https://www.diskanalyzer.com/)
Shows you the biggest files on your computer. Neat to visualize things.

### [WinDirStat](https://windirstat.net/)
Talking about visualizing things; Windirstat does just that very well.

## Automation

### [AutoHotKey](https://www.autohotkey.com/)
Extremely powerful language for doing all manner of things. I just use it to map media keys to my keyboards without them.
This is the script:

```autohotkey
#NoEnv
SendMode Input
SetWorkingDir %A_ScriptDir%

; Ctrl + Win + e = Next song
^#e::
Send {Media_Next}
return

; previous song
^#q::
Send {Media_Prev}
return

; play/pause
^#w::
Send {Media_Play_Pause}
return

; vol up
^#f::
Send {Volume_Up 2}
return

; vol down
^#d::
Send {Volume_Down 2}
return
```

## Media

### [VLC media player](https://www.videolan.org/vlc/)
The best media player for windows. I've never had a single problem with it.

### [Jellyfin Media Player](https://jellyfin.org/posts/client-jmp/)
The best media player for use with Jellyfin servers.

### [Parsec](https://parsec.app/)
Game-sharing by streaming. Very convenient and smart.

### [Netflix](https://www.microsoft.com/en-us/p/netflix/9wzdncrfj3tj)
The Netflix app is my preferred way of watching Netflix while on my desktop. It supports higher bitrate and surround sound.

### [GOG Galaxy](https://www.gogalaxy.com/en/)
Good looking, well intentioned game library and store with the ability to connect your other game clients. 

### [Steam](https://store.steampowered.com/)
The other big library of games.

### [Shotcut](https://www.shotcut.org/)
Open source, free video editor.
