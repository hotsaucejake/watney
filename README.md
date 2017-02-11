# WATNEY
### A raspberry pi powered remote controlled vehicle with camera support
------
![img_20160113_223131](https://cloud.githubusercontent.com/assets/6332533/22855507/609a785a-f04f-11e6-904f-8ab732ef23e0.jpg)

## About WATNEY:
WATNEY is composed of Raspberry Pi, DC-DC Step-down Voltage Module, USB camera, DC motor driver, and PCA9685-based Servo Controller. From the perspective of software, WATNEY is of client/server (C/S) structure. The TCP server program is run on WATNEY for direct control of him. And the video data are acquired and delivered via the open source software MGPJ-streamer in a real-time manner. The TCP client program is run on the remote to send control commands. Both the client and server programs are developed in Python language. WATNEY car is developed based on the open-source hardware Raspberry Pi and integrates the knowledge of mechanics, electronics, and computer, thus having profound educational significance. 

### Notice:
WATNEY must be initialized first before you can deploy the remote.
