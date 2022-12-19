<div align="center">

## YTDLG

[![Downloads](https://img.shields.io/github/last-commit/unattended-ch/ytdlg?style=for-the-badge&color=green)](https://github.com/unattended-ch/ytdlg/releases/latest)
[![Downloads](https://img.shields.io/github/license/unattended-ch/ytdlg?style=for-the-badge&color=green)](https://github.com/unattended-ch/ytdlg/releases/latest)
[![Stars](https://img.shields.io/github/stars/unattended-ch/ytdlg?style=for-the-badge&color=blue)](https://github.com/unattended-ch/ytdlg/stargazers)
[![Release version](https://img.shields.io/github/v/release/unattended-ch/ytdlg?label=&style=for-the-badge)](https://github.com/unattended-ch/ytdlg/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/unattended-ch/ytdlg/total?style=for-the-badge&color=blue)](https://github.com/unattended-ch/ytdlg/releases/latest)

[![Windows](https://img.shields.io/badge/-Windows_x64-blue.svg?style=for-the-badge&logo=windows)](https://github.com/unattended-ch/ytdlg/releases/latest/download/ytdlg-full_0.0.0.30-win64.exe)
[![Ubuntu](https://img.shields.io/badge/-Ubuntu_x64-brightgreen.svg?style=for-the-badge&logo=linux)](https://github.com/unattended-ch/ytdlg/releases/latest/download/ytdlg-full_0.0.0.30-amd64.deb)
[![Raspi](https://img.shields.io/badge/-Raspi_ARMHF-maroon.svg?style=for-the-badge&logo=linux)](https://github.com/unattended-ch/ytdlg/releases/latest/download/ytdlg-full_0.0.0.30-armhf.deb)
[![MacOS](https://img.shields.io/badge/-MacOS_x64-lightblue.svg?style=for-the-badge&logo=apple)](https://github.com/unattended-ch/ytdlg/releases/latest/download/ytdlg-full_0.0.0.30-mac64.dmg)


    Simple GUI for youtube-dl and yt-dlp

    Compiled with Lazarus for Ubuntu, Raspi, MacOS and Windows

    Crosscompiled with Ubuntu for Ubuntu, Raspi and Windows
    Setup created with Ubuntu for Ubuntu, Raspi and Windows

[![my way](https://img.shields.io/badge/-vide_alios_et_bene_quod_opus_est_cogitare-navy.svg?style=for-the-badge)](https://www.google.ch/search?q=%22vide+alios+et+bene+quod+opus+est+cogitare%22+translate)
   [vide alios et bene quod opus est cogitare](https://www.google.ch/search?q=%22vide+alios+et+bene+quod+opus+est+cogitare%22+translate)

</div>

<a name="toc"></a>
<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary><h2 style="display: inline-block">TABLE OF CONTENTS</h2></summary>
  <ol>
    <li><a href="#windows">Windows</a>
      <ul>
      <li><a href="#mainwindow">Main</a></li>
      <li><a href="#optionswindows">Options</a></li>
      <li><a href="#updatewindows">Update</a></li>
      <li><a href="#informationwindows">Information</a></li>
      <li><a href="#audiowindows">Audio</a></li>
      <li><a href="#videowindows">Video</a></li>
      <li><a href="#configwindows">Config</a></li>
      </ul>
    </li>
    <li><a href="#descriptions">Description</a></li>
    <li><a href="#downloads">Download</a></li>
    <li><a href="#neededtools">Needed tools</a></li>
  </ol>
</details>

<a name="windows"></a>
## WINDOWS
<a name="mainwindow"></a>
### Main-Window
![Main Page](/res/main-window.png)

   [goto TOC](#toc)

<a name="descriptions"></a>
## DESCRIPTION

       ytdlg <Enter>

         A = Download only audio files or stop download
         V = Download video files or stop download
         I = Display process output
         X = Remove entry from list

       - <LEFT-CLICK> an A or V starts the download
       - After clinking you can click again to stop it

       - <RIGHT-CLICK> on A, V, I or X open options window (only on not running task)

       - Function keys
           <F1> Open ytdlg github page
           <F10> Close ytdlg
           <F12> Restart ytdlg to load changes

       - Download a single file or all files from a playlist
       - Playlist is saved in a subfolder
       - For playlist there will be created a .m3u file
       - Remember downloading a playlist could take a long time depending on the size
       - For playlist you can select the first file to download in playlist combo
         and the last file in the last file combo

       - Linux data folder ~/.ytdlg is created for temporary files and config
       - Downloaded files are saved in ~/Music or ~/Videos

       - Windows data folder %APPDATA%\ytdlg is created for temporary files, tools and config
       - Downloaded files are saved in %USERPROFILE%\Music or %USERPROFILE%\Videos

       - MacOS data folder ~/.ytdlg is created for temporary files and config
       - Downloaded files are saved in ~/Music or ~/Videos

       - Video, Audio and Output format selection

       - All list entrys are reloaded on restart
       - Reloaded playlist starts with last downloaded file

       - Manage work files from Information window (Save, View, Delete)
       - Find ERROR in .dbg and .err files
       - Search for text in files
       - If you open the Information window it displays the current task
       - Click on file load the file for viewing
       - Right click on file opens the option menu
       - Opening and closing the Information window with playlist could take time

       - After download <DBL-CLICK> on image to start the player (A=Audioplayer, V=Videoplayer)
       - Be sure your Audioplayer and Videoplayer can be found in the PATH else set fullpath in config

       - On Audio- or Video-page
           <DBL-CLICK> to start
           <DEL> to delete file
           <F5> refresh
           <F8> recreate playlist

   [goto TOC](#toc)

<a name="optionswindows"></a>
### Options Window
![Main Page](/res/options-window.png)


<a name="updatewindows"></a>
### Update Window
![Main Page](/res/update-window.png)

   [goto TOC](#toc)

<a name="informationwindows"></a>
### Information window
![Info Page](/res/info-window.png)

   [goto TOC](#toc)

<a name="audiowindows"></a>
### Audio Window
![Main Page](/res/audio-window.png)

   [goto TOC](#toc)

<a name="videowindows"></a>
### Video Window
![Main Page](/res/video-window.png)

   [goto TOC](#toc)

<a name="configwindows"></a>
### Config Window
![Main Page](/res/config-window.png)

   [goto TOC](#toc)

<a name="change"></a>
## CHANGELOG
[Changelog](/CHANGELOG)


<a name="downloads"></a>
## DOWNLOAD

       - Windows full installer package with tools  (ytdlg-full_VERSION-win64.exe)
       - Ubuntu full installer package with tools   (ytdlg-full_VERSION-amd64.deb)
       - Raspi partial installer package with tools (ytdlg-full_VERSION-armhf.deb)
       - MacOS full installer package with tools    (ytdlg-full_VERSION-mac64.dmg)

<div align="center">

[![Download ](https://img.shields.io/github/v/release/unattended-ch/ytdlg?label=&style=for-the-badge)](https://github.com/unattended-ch/ytdlg/releases/latest)

[![Windows](https://img.shields.io/badge/-Windows_x64-blue.svg?style=for-the-badge&logo=windows)](https://github.com/unattended-ch/ytdlg/releases/latest/download/ytdlg-full_0.0.0.30-win64.exe)
[![Ubuntu](https://img.shields.io/badge/-Ubuntu_x64-brightgreen.svg?style=for-the-badge&logo=linux)](https://github.com/unattended-ch/ytdlg/releases/latest/download/ytdlg-full_0.0.0.30-amd64.deb)
[![Raspi](https://img.shields.io/badge/-Raspi_ARMHF-maroon.svg?style=for-the-badge&logo=linux)](https://github.com/unattended-ch/ytdlg/releases/latest/download/ytdlg-full_0.0.0.30-armhf.deb)
[![MacOS](https://img.shields.io/badge/-MacOS_x64-lightblue.svg?style=for-the-badge&logo=apple)](https://github.com/unattended-ch/ytdlg/releases/latest/download/ytdlg-full_0.0.0.30-mac64.dmg)

</div>

<a name="neededtools"></a>
## TOOLS

-   [  youtube-dl][youtube-dl] Download manager (You must install or update)
-   [  yt-dlp][yt-dlp] Download manager (/usr/local/bin/ OR %APPDATA%\ytdlg)
   Raspi (python3 -m pip install -U yt-dlp)
-   [  ffmpeg][ffmpeg] Convert/Merge Video and Audio (/usr/local/bin/ OR %APPDATA%\ytdlg)
-   [  atomicparsley][atomicparsley] Insert meta data (/usr/local/bin/ OR %APPDATA%\ytdlg)

    
   [goto TOC](#toc)

[releases]: https://github.com/unattended-ch/ytdlg/releases

[youtube-dl]: https://github.com/ytdl-org/youtube-dl#installation

[yt-dlp]: https://github.com/yt-dlp/yt-dlp#installation

[ffmpeg]: https://www.ffmpeg.org/download.html

[atomicparsley]: https://howtoinstall.co/en/atomicparsley

[curl]: https://curl.se/windows/

[lazarus]: https://www.lazarus-ide.org/
