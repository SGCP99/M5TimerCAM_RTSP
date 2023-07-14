# M5TimerCAM_RTSP
Livestream on your local network using RTSP. To access the livestream you should use the VLC Media Player

To use the code you should add in the library the following zip files. 

When you add the three zip files on your Arduino IDE, go to the examples and search for TimerCam, and select the rtsp-stream. 
Replace on the code the WIFI SSID and Password and run the code. 
If you added correct the libraries the program should download to the Timer camera.
When the download is completed open the serial monitor and reset the camera. 
The serial port should display that the camera is connected to the wifi and display a URL. 

Copy the URL (example: rtsp://192.168.0.47/jmpeg/1) and open the VLC, go to Media ---> Open Network System and paste the URL. 
The VLC should start loading and after few seconds you should get the livestream image. 

Source: https://github.com/m5stack/TimerCam-arduino/tree/master

      : https://github.com/mathertel/OneButton/tree/master
      
      : https://github.com/geeksville/Micro-RTSP?search=1


***If you want to save the RTSP stream and the people one your network to access it by using a specific URL without having to access it through VLC
follow the steps of this video: https://www.youtube.com/watch?v=rgWVm_j3llo&t=325s&ab_channel=AndyFordham
