# drone-camera
An Arduino code written for the ESP32-CAM used as the drone camera.

## Dependencies
ESP32 library v3.1.3

## How It Works?
1. It'll try to connect to the network using the given SSID and password
2. It'll use port 8888 to perform UDP broadcast and wait for the phone's acknowledge; LED blinks
3. After receiving the response, it'll stream the MJPEG feed, and open a port for command
