# YAAC - Yet Another Audio Encoder

## A GUI Frontend for Commandline ffmpeg with Neroaacenc & ffmpeg with Vorbis

### Features:

* Supports Encoding to AAC LC, HE, HEv2 using Neroaacenc (not included, need to download it separately)

* Supports Encoding to auToV Vorbis using venc (not included, need to download it separately)

* Supports Muxing of encoded audio tracks with source file into a mkv container thanks to MKVToolNix (not included)

* Supports source audio files of upto 8 channels (FLAC encode possible upto 8 channels via eac3to (not included))

* Supports audio normalization (optional) via eac3to or SoX decoders (not included, need to download it separately)

* Ability to fetch mkv container info with the help of Mediainfo (not included, need to download it separately)

* Multiple processing of files with Drag n Drop support

* Multiple audio tracks processing within a source file

* Ability to force AAC to HE or HEv2 if required

* Quality-bitrate charts for look-up of values

### System Requirements:

> Windows XP SP2 and above

> .NET 2.0 Framework - www.microsoft.com/en-us/download/details.aspx?id=19

### Please Note:

> This was specifically created for processing Matroska Video (mkv) files but it might work with other file formats as well.

### What You Need?

##### Since I am just providing GUI for the command line applications which are created by other devs, so you need:

> FFmpeg (Static 32-bit Build) (default - for encoding to uncompressed wav) - ffmpeg.zeranoe.com/builds/

> SoX (Win32 Build) (optional - for encoding to uncompressed wav) - sourceforge.net/projects/sox/

> Neroaacenc (for encoding to AAC) - www.nero.com/eng/downloads-nerodigital-nero-aac-codec.php

> auToV Vorbis (Win32 Reference Library) (for encoding to OGG Vorbis) - www.geocities.jp/aoyoume/aotuv/

> eac3to (for FLAC encode ability for source having channels greater than 2 channel) - madshi.net/eac3to.zip

> Mediainfo (32 bit CLI) (for reading source file information) - mediainfo.sourceforge.net/en/Download/Windows

> MKVToolNix (for extrating and muxing tracks) - www.bunkus.org/videotools/mkvtoolnix/downloads.html#windows

> (If you already have MKVToolNix installed on your PC by their installer program then you don't need to download this)

##### OR

> You can download whole compiled package from here, but I still recommend that you download all applications separately.

> An updated archive of required files can be downloaded from here: d-h.st/z8r

##### AND

> Download "YAAE - Yet Another Audio Encoder - GUI Frontend Audio Encoder For AAC And Vorbis" from here.

> Extract and put all the files in one place and simply run YAAC.exe to start the GUI FrontEnd for AAC and Vorbis encoder. 
