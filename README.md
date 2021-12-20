<div align="center">

## YTDLG

[![Release version](https://img.shields.io/github/v/release/unattended-ch/ytdlg?label=&style=for-the-badge)](https://github.com/unattended-ch/ytdlg/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/unattended-ch/ytdlg/total?style=for-the-badge&color=blue)](https://github.com/unattended-ch/ytdlg/releases/latest)

    gui for youtube-dl and yt-dlp

    Ubuntu, Raspian, MacOS and Windows

   -  [Remote Chaos Expirience](https://tickets.events.ccc.de/RC3-21/) from Dec. 27th – 30th, 2021

</div>

<a name="toc"></a>
<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary><h2 style="display: inline-block">TABLE OF CONTENTS</h2></summary>
  <ol>
    <li><a href="#description">Description</a></li>
    <li><a href="#download">Download</a></li>
    <li><a href="#tools">Needed tools</a></li>
  </ol>
</details>

![Main Page](/res/main-window.png)

## DESCRIPTION

       ytdlg <Enter>

       - Download a single file or all files from a playlist

       - Linux data folder ~/.ytdlg is created for temporary files
       - Downloaded files are saved in ~/Music or ~/Videos

       - Windows data folder %APPDATA%\ytdlg is created for temporary files
       - Downloaded files are saved in %USERPROFILE%\Music or %USERPROFILE%\Videos

       - MacOS data folder ~/.ytdlg is created for temporary files
       - Downloaded files are saved in ~/Music or ~/Videos

       - Playlist is saved in a subfolder

       - Video, Audio and Output format selection

       - All list entrys are reloaded on restart

       - After download double click on image to start vlc

       A = Download only audio files
       V = Download video files
       I = Display youtube-dl output
       X = Remove entry from list

       Compiled with Lazarus for Ubuntu, Raspian, MacOS and Windows

   [goto TOC](#toc)


## DOWNLOAD

       - Ubuntu minimal installer package          (ytdlg_VERSION_x86-64.deb)
       - Raspberry minimal installer package       (ytdlg_VERSION_armhf.deb)
       - Windows minimal installer package         (ytdlg_VERSION_setup.exe)
       - MacOS minimal installer package           (ytdlg_VERSION_macos-x64.pkg)

       - Windows full installer package with tools (ytdlg-full_VERSION_setup.exe)

-   [  Releases][releases]

## TOOLS

    For all minimal packages you must install the following tools :
-   [  youtube-dl][youtube-dl] Download manager
-   [  yt-dlp][yt-dlp] Download manager
-   [  ffmpeg][ffmpeg] Convert/Merge Video and Audio
-   [  atomicparsley][atomicparsley] Insert meta data
-   [  curl][curl] Download thumbnails (Windows 7 only)

   [goto TOC](#toc)

[releases]: https://github.com/unattended-ch/ytdlg/releases

[youtube-dl]: https://github.com/ytdl-org/youtube-dl

[yt-dlp]: https://github.com/yt-dlp/yt-dlp

[ffmpeg]: https://www.ffmpeg.org/download.html

[atomicparsley]: https://howtoinstall.co/en/atomicparsley

[curl]: https://curl.se/windows/

[lazarus]: https://www.lazarus-ide.org/
