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

## NAME

       ytdlg is a gui for youtube-dl or yt-dlp

![Main Page](/res/ytdlg.png)

## DESCRIPTION

       ytdlg <Enter>

       Download a single file or all files from a playlist

       Linux data folder ~/.ytdlg is created for temporary files
       Downloaded files are saved in ~/Music or ~/Videos

       Windows data folder %APPDATA%\ytdlg is created for temporary files
       Downloaded files are saved in %USERPROFILE%\Music or %USERPROFILE%\Videos

       Playlist is saved in a subfolder

       A = Download only audio files
       V = Download video files
       I = Display youtube-dl output
       X = Remove entry from list

       All list entrys are reloaded on restart

       After download double click on image to start vlc

       On Config page you can change input and output formats

       Compiled with Lazarus for Ubuntu and Windows

       I have successfully compiled the project on my iMac,
       but unfortunately my OS has only python 2.7

   [goto TOC](#toc)


## DOWNLOAD

-   [  Releases][releases]

## TOOLS

    You must install the following tools :
-   [  youtube-dl][youtube-dl] Download manager
-   [  yt-dlp][yt-dlp] Download manager
-   [  ffmpeg][ffmpeg] Convert/Merge Video and Audio
-   [  atomicparsley][atomicparsley] Insert meta data

   [goto TOC](#toc)

[releases]: https://github.com/unattended-ch/ytdlg/releases

[youtube-dl]: https://github.com/ytdl-org/youtube-dl

[yt-dlp]: https://github.com/yt-dlp/yt-dlp

[ffmpeg]: https://www.ffmpeg.org/download.html

[atomicparsley]: https://howtoinstall.co/en/atomicparsley

[lazarus]: https://www.lazarus-ide.org/

