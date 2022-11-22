<div align="center">

## YTDLG

[![Release version](https://img.shields.io/github/v/release/unattended-ch/ytdlg?label=&style=for-the-badge)](https://github.com/unattended-ch/ytdlg/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/unattended-ch/ytdlg/total?style=for-the-badge&color=blue)](https://github.com/unattended-ch/ytdlg/releases/latest)

    GUI for youtube-dl and yt-dlp

    Compiled with Lazarus for Ubuntu, MacOS and Windows


   [vide alios et bene quod opus est cogitare](https://www.google.ch/search?q=%22vide+alios+et+bene+quod+opus+est+cogitare%22+deutsch)

</div>

<a name="toc"></a>
<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary><h2 style="display: inline-block">TABLE OF CONTENTS</h2></summary>
  <ol>
    <li><a href="#windows">Windows</a></li>
    <li><a href="#description">Description</a></li>
    <li><a href="#download">Download</a></li>
    <li><a href="#tools">Needed tools</a></li>
  </ol>
</details>

## WINDOWS
### Main Window
![Main Page](/main-window.png)

   [goto TOC](#toc)

### Information window
![Info Page](/info-window.png)

   [goto TOC](#toc)

## DESCRIPTION

       ytdlg <Enter>

         A = Download only audio files or stop download
         V = Download video files or stop download
         I = Display process output
         X = Remove entry from list

       - Download a single file or all files from a playlist
       - Playlist is saved in a subfolder
       - For playlist there will be created a .m3u file
       - Remember downloading a playlist could take a long time depending on the size

       - Linux data folder ~/.ytdlg is created for temporary files and config
       - Downloaded files are saved in ~/Music or ~/Videos

       - Windows data folder %APPDATA%\ytdlg is created for temporary files, tools and config
       - Downloaded files are saved in %USERPROFILE%\Music or %USERPROFILE%\Videos

       - MacOS data folder ~/.ytdlg is created for temporary files and config
       - Downloaded files are saved in ~/Music or ~/Videos

       - Video, Audio and Output format selection

       - All list entrys are reloaded on restart

       - Manage work files from Information window (Save, View, Delete)
       - If you open the Information window it displays the current task
       - Click on file stop current task and load the file for viewing
       - Right click on file opens the option menu
       - Opening and closing the Information window with playlist could take time

       - After download double click on image to start the player (A=Audioplayer, V=Videoplayer)


   [goto TOC](#toc)

## CHANGELOG
[Changelog](/CHANGELOG)


## DOWNLOAD

       - Windows full installer package with tools (ytdlg-full_VERSION_setup.exe)
       - Ubuntu full installer package with tools  (ytdlg-full_VERSION_amd64.deb)
       - MacOS full installer package with tools   (ytdlg-full_VERSION_mac64.dmg)

       - Raspberry no longer supported (no downloads).


[![Download ](https://img.shields.io/github/v/release/unattended-ch/ytdlg?label=&style=for-the-badge)](https://github.com/unattended-ch/ytdlg/releases/latest)

## TOOLS

-   [  youtube-dl][youtube-dl] Download manager (You must install or update)
-   [  yt-dlp][yt-dlp] Download manager
-   [  ffmpeg][ffmpeg] Convert/Merge Video and Audio
-   [  atomicparsley][atomicparsley] Insert meta data

    
   [goto TOC](#toc)

[releases]: https://github.com/unattended-ch/ytdlg/releases

[youtube-dl]: https://github.com/ytdl-org/youtube-dl#installation

[yt-dlp]: https://github.com/yt-dlp/yt-dlp#installation

[ffmpeg]: https://www.ffmpeg.org/download.html

[atomicparsley]: https://howtoinstall.co/en/atomicparsley

[curl]: https://curl.se/windows/

[lazarus]: https://www.lazarus-ide.org/
