# FFSUKI

Make Hardsub It's Easy!

# What Is FFSUKI

FFSUKI is an FFMPEG interface to make it easier for you to make hardsub.

If you have a difficulty operating FFMPEG, You don't need to learn the FFMPEG command, because FFSUKI makes it easy for you!.

just as easy as choosing 1, 2, 3, ...

# How To Install FFSUKI?

## Installing Dependencies

### if you use Debian Based Linux (Debian, Ubuntu, etc)

>$ sudo apt install ffmpeg libarchive-zip-perl xz-utils

<!--### if you use openSuSE Based Linux (Not Tested, Need Help For Testing)-->

<!--follow step on this website for install FFMPEG-->

<!--https://software.opensuse.org/package/ffmpeg-->

<!--then-->

<!-->$ sudo zypper install libarchive-zip-perl-->

<!--### if you use RedHat Based Linux (RHEL, Fedora, Centos, etc) (Not Tested, Need Help For Testing)-->

<!-->$ sudo dnf install ffmpeg libarchive-zip-perl -->

<!--or-->

<!-->$ sudo yum install ffmpeg libarchive-zip-perl-->

### if you use Windows

1. Go to Control Panel > Programs and Features > Turn Windows features on or off

2. Activate "Windows Subsystem for Linux"

3. Go to Microsoft Store

4. Search "Linux"

5. Install Ubuntu / Debian / openSUSE / other linux what you want (Tested Only On Ubuntu)

6. open bash

7. following a Installing Dependencies in Linux

## Download FFSUKI

go to Releases in FFSUKI GitHub repository



or you can git clone FFSUKI (Unstable, We recommend download FFSUKI from releases)



# How To Use FFSUKI?

1. move .mkv videos to **ffsuki** directory

2. Open FFSUKI

>$ bash ffsuki.sh

3. Input Your Name / Your Fansub Name

4. Choose Video Format

5. Choose Video Resolution

6. Choose Video Quality

7. wait..... until finish

8.  Your hardsub videos in **ffsuki/output** directory

Thank you for using FFSUKI 😊

# Features

> ✔️ = Availabe
> ❌ = Not Available (On Development)

## Video Format

✔️ x264

✔️ x265

✔️ VP9

❌ AV1

## Resolution

✔️ nHD (640x360)

✔️ qHD (960x540)

✔️ HD (1280x720)

✔️ FHD (1920x1080)
  
✔️ 2K DCI (2048x1080)

✔️ WQHD (2560x1440)

✔️ UHD (3840x2160)

✔️ 4k DCI (4096x2160)

# Credits



Thanks to : 

- FFmpeg for make very awesome video converter software (https://ffmpeg.org/)
- All who contributed to this project