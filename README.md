# Rabot
A rabbit-monitoring system

## Steps
1. Prepare a usb webcam and raspberry pi, mine is model 3 b.

2. Install and config motion on your raspberry pi. Check
http://www.emindlab.com/raspberry-pi/raspberry-pi-remote-webcam-streaming.html
and
https://www.youtube.com/watch?v=H1jSudsIJfA

3. Motion commands

  start `$ sudo service motion start`

  stop `$ sudo service motion stop`

  restart `$ sudo service motion restart`
4. Open a webpage on your web browser and input the IP of your raspberry pi on port 8081 (from motion.config)

  For example: `192.168.1.151:8081`
