# Cybersecurity : CSN150
Project: ESP32 Camera Firmware Setup

## Purpose
Set up ESP32 and Arduino enviornment. Execute sketch " Wifiscanner". 

## Equipment
* [ESP32Cam](https://www.amazon.com/Aideepen-ESP32-CAM-Bluetooth-ESP32-CAM-MB-Arduino/dp/B08P2578LV/ref=sr_1_3?crid=4FY0ECFW0ZX7&keywords=ESP32+Cam&qid=1678902050&sprefix=esp32+cam%2Caps%2C240&sr=8-3)

* [USB Micro Data Cable](https://www.amazon.com/AmazonBasics-Male-Micro-Cable-Black/dp/B0711PVX6Z/ref=sr_1_1_sspa?keywords=micro+usb+data+cable&qid=1678902214&sprefix=Micro+USB+data+%2Caps%2C89&sr=8-1-spons&psc=1&spLa=ZW5jcnlwdGVkUXVhbGlmaWVyPUFaU0NaUVZHU1RFUlAmZW5jcnlwdGVkSWQ9QTA3NTA4MDVFVERCS01HVlgxM1YmZW5jcnlwdGVkQWRJZD1BMDE4NTE1NTIwWUdONkdWSzU1M1Amd2lkZ2V0TmFtZT1zcF9hdGYmYWN0aW9uPWNsaWNrUmVkaXJlY3QmZG9Ob3RMb2dDbGljaz10cnVl)

## Links to documentation and tools

##### Video 1: 

##### Other Links: 

##### AI GPTs used

## Steps I followed
. Write the steps you followed here.  This way you can keep track of where you might have messed up if the project does not work.
1. Connected ESP32-CAM to computer using USB cable
2.Opened Arduino IDE
3.Installed ESP32 board support in Boards Manager
4.Selected AI Thinker ESP32-CAM board
5.Set upload speed to 115200
6.Selected correct COM port
7.Opened CameraWebServer example code
8.Enabled AI Thinker camera model in code
9.Entered WiFi SSID and password
10.Uploaded code to ESP32-CAM
11.Held BOOT button during “Connecting…”
12.Opened Serial Monitor at 115200 baud
13.Found IP address displayed
14.Opened IP address in browser
15.Started live video stream
16. saw that the feed was black
17. rebooted my cam, checked wifi and password was the same, redid the upload
18. reopened ip address in browser
19. still saw black screen
20. tried fixing the camera ribbon
21. still did not work
22. live stream was working but was black

## Problems and Solutions
Note your problems or errors here.  Google any error you may come across, and not what you tried (even if it does not work), and what was the final answer. Document your errors and solutions that worked for you.  

 Problem: ESP32-CAM connected to laptop and web page loaded, but live video stream showed only a black image.
What I tried: Reset the board, verified CAMERA_MODEL_AI_THINKER, checked power source, and inspected/reseated the camera ribbon cable.
Likely solution: Most likely caused by a loose camera ribbon cable, wrong camera model selection, or unstable 5V power during streaming. Supported fixes are to reseat the camera cable, confirm the AI Thinker camera definition, and use stable 5V power.

 



**Solution:** the live stream was on but it was black, camera ribbon might not be connected properly.

## Final Report
