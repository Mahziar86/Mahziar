# hackcam
# hackcam v1.0
Take webcam shots from target just sending a malicious link



# How it works?
<p>The tool generates a malicious HTTPS page using Serveo or Ngrok Port Forwarding methods, and a javascript code to cam requests using MediaDevices.getUserMedia. </p>

<p>The MediaDevices.getUserMedia() method prompts the user for permission to use a media input which produces a MediaStream with tracks containing the requested types of media. That stream can include, for example, a video track (produced by either a hardware or virtual video source such as a camera, video recording device, screen sharing service, and so forth), an audio track (similarly, produced by a physical or virtual audio source like a microphone, A/D converter, or the like), and possibly other track types. </p>

![hackcam](https://user-images.githubusercontent.com/62829664/79315322-5f228400-7f20-11ea-95eb-9129aa475b40.jpg)

## Installing Termux:

```
apt-get upgrade
pkg install git
pkg install php
pkg install wget
pkg install ssh
pkg install curl
git clone https://github.com/sparkz-technology/hackcam
cd hackcam
chmod +x *
bash hackcam.sh
```
## Installing kali linux
```
git clone https://github.com/sparkz-technology/hackcam
cd hackcam
bash hackcam.sh
```
