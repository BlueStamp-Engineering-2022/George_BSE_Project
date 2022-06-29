# Object and Eye Detection on Raspberry Pi
For my project, I used a raspberry pi with a picamera2 to detect objects and eyes. The object detection code draws boxes around different objects and identifies them, all in real time. The eye detection draws circles around any eyes the camera sees, also in real time. 

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| George | Los Gatos High School | Computer Science | Incoming Sophomore

![image](https://user-images.githubusercontent.com/107579713/174339039-3c74fc92-e809-4c39-a8a3-21d61a538fcb.png)

  
# Final Milestone
My final milestone was getting the program for eye detection on the raspberry pi. I got it to work with the picamera2 instead of a webcam. This is useful because, unlike the webcam of my laptop, the picamera can move around more easily. Additionally, getting the code on the raspberry pi was my initial intention, so it was important to have the program run there. The code for the picamera required different commands than the webcam of my laptop. For example, instead of starting the webcam with VideoCapture(), I had to start it with picam2.start(). For my next steps, outside of BlueStamp, I will be finishing training a model that recognizes only my face using my laptop and its webcam. 

[![Milestone 3](https://res.cloudinary.com/marcomontalbano/image/upload/v1656087542/video_to_markdown/images/youtube--0jbku2rOTdQ-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://www.youtube.com/watch?v=0jbku2rOTdQ "George Milestone 3")

# Second Milestone
For my second milestone, I got the eye detection program to work on my laptop. I downloaded various packages that are required for the code to work. I then changed the code from face detection to just eye detection. I changed the rectangle to a circle to better fit the shape of eyes when identifying them. Finally, I added to the code so that it would stop running when I pressed "q" on my keyboard. Once again, troubleshooting the various issues that came up in my code were the most difficult and time consuming parts of the project, but also the most satisfying when I figuired out what was wrong. 

[![Milestone 2](https://res.cloudinary.com/marcomontalbano/image/upload/v1655923419/video_to_markdown/images/youtube--WtUPKN5Uh3I-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://www.youtube.com/watch?v=WtUPKN5Uh3I "Milestone 2")

# First Milestone
  

My first milestone was setting up my raspberry pi and running machine learning object detection code from github. I started by setting up the SD card and installing the Raspberry Pi operating system. Once that was completed, I inserted the SD card into my Raspberry Pi and connected a monitor, mouse, keyboard, and the picamera2. Finally, I found a library on github for object detection. I cloned it and, using the terminal, ran the code on my camera. I learned a lot about doing online research for different code and using the libraries that I found. I struggled with the troubleshooting I had to do whenever the code did not work as I wanted it to.  

[![Milestone 1](https://res.cloudinary.com/marcomontalbano/image/upload/v1655923371/video_to_markdown/images/youtube--2VjpJtcZLl0-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://www.youtube.com/watch?v=2VjpJtcZLl0 "Milestone 1")

# Starter Project
  

On the starter project, I worked with an arduino and a NeoPixel Ring. The Neopixel Ring is made up of 12 individual LEDs. It is connected to the arduino with three wires, and the arduino is connected to my computer so that I can control it with my code. The code allows the user to control the ring using the serial monitor. If the user types characters b, y, g, m, r, or c, the NeoPixel Ring lights up with the respective colors (blue, yellow, green, magenta, red, cyan). When working with Arduino, I struggled figuring out the necessary code. C++ was an entirely new language for me, so it was a challenge to research all the necessary commands for accessing the serial monitor.


[![Starter Project](https://res.cloudinary.com/marcomontalbano/image/upload/v1655741724/video_to_markdown/images/youtube--NjxrbR2duPs-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://youtu.be/NjxrbR2duPs "George K Starter Project")
