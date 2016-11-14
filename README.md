# Rabot
A rabbit-monitoring system

## Steps
1. Prepare a usb webcam and raspberry pi, mine is model 3 B. rtggfZX

2. Install ffmpeg on your pi. If you are using Raspbian, check this tutorial
https://www.assetbank.co.uk/support/documentation/install/ffmpeg-debian-squeeze/ffmpeg-debian-jessie/

3. plug your webcame into your pi and use ffmpeg to record

```ffmpeg -f v4l2 -r 25 -s 640x480 -i /dev/video0 out.avi```

(WIP)
