# Raspberry-Bushcam
by J. Grant Boling: gboling [at] gmail [dot] com

A python script for the Raspberry Pi to record video of wildlife when triggered by PIR sensor. 
Optionally supports DHT11 temp/humidity sensor.
Handles encoding the raw h264 files to mp4 and copies to a folder organized as such: year/month/date.
Video files are annotated with timestamp and temp/humidity at time of trigger. Filename is also the timestamp.

Dependencies:
------------

Raspberry Pi 2 B with Camera, picamera-dev
PIR sensor,
Raspbian Jessie,
pigpiod http://abyz.co.uk/rpi/pigpio/pigpiod.html
DHTXXD  http://abyz.co.uk/rpi/pigpio/examples.html -- compile, then place in /usr/bin or somewhere in $PATH

PIR sensor should be plugged into GPIO pin 17
DHT sensor should be plugged into GPIO pin 18

