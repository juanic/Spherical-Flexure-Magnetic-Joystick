# Spherical-Flexure-Magnetic-Joystick

Magnetic joystick based of an spherical flexure joint

![Test Image 4](https://github.com/juanic/Spherical-Flexure-Magnetic-Joystick/blob/main/Sources/render.jpg)

I found Jelle's flexure on YouTube and thought It could be something cool to replicate. A lot of the comments on the video (both in [Jelle's](https://www.youtube.com/watch?v=DAngcygU7tc) and [mine](https://youtu.be/wASpQMGZQ70) ) were about possible applications. I tried to come up with something and this is the end result.

The Arduino source code is basically Krakenus analog mouse: https://github.com/Krakenus/arduino-joystick-mouse

I modified it in orther to use an HMC5883 magnetometer instead of an analog joystick. Added also a calibration routine at start up and a third button.

It uses a 5mm magnet, but I guess you can modify it to something else.

Video of the device being used:
https://youtu.be/n7yjRrHE-SI
