# Infinity Mirror Clock
I am working on an arduino Infinity Mirror Clock that uses LED's and mirrors in order to generate a cool looking clock. Other parts, like a time-keeping component and a numpad component used to set alarms will also be added.

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Aaron Yan | Lynbrook High School | Engineering | Incoming Junior

![Headstone Image](https://bluestampengineering.com/wp-content/uploads/2016/05/improve.jpg)
  
# Final Milestone
My final milestone is the construction of the frame of my clock and making sure that all the components fit properly and work together. In order to do this I constructed a cradboard box tto store the components and used two mirrors, a normal one at the back and two-way one at the front, in order to create the infinity effect. This stage has actually ended up being one of the most challenging. The first ring I ordered ended up being too small, so I had to order another one that came at the last day. The construction of the container also caused many problems. Also, in order for all my wiring to fit, I had to move all my wiring onto a smaller breadboard, which led to many issues of wires going in the wrong place.

<html><iframe width="560" height="315" src="https://www.youtube.com/embed/u-EK20_LeH0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></html>

# Second Milestone
My second milestone is adding various features, like an alarm, a numpad for inputting the alarm time, and an LCD screen for displaying the time and alarm. I first added an alarm, making so that when it goes off, the LEDs  turn rainbow for a few seconds and a buzzer plays a sound. Next, in order to make it easy for the user to input an alarm, I added a numpad. I made it so that in order to enter "alarm setting mode", one has to first press the star key before entering their desired time. Finally, in order for the user to easily see what they are entering, I added an LCD screen to display the alarm being set. Since I had already added the LCD screen anyways, I decided to display the time on it too, so that the user can easily see whether it is AM or PM.

<html><iframe width="560" height="315" src="https://www.youtube.com/embed/0xissyxx65Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></html>
# First Milestone
  
My first milestone is setting up and hooking up all the wires between my Arduino Uno, Neopixel strip, and clock component in order to make the Neopixel strip light up according to the time. Since my Neopixel strip is 60 LEDs long, I decided to make 1 light up for each second, 1 light up for each minute, and 5 light up for each hour(12-hour format like a standard clock). I also decided to make the seconds green, minutes red, and hours blue in order to easily differentiate the three. I also made it os that when the hours and minutes overlap, it turns purple, which adds more variety to the clock and also makes it clearer. In order to achieve all of this, I downloaded the Arduino softare off the internet and got to coding. To get a better understanding of the code, I made use of the example code to familiarize myself with the various methods of the many Libraries I used, including Adafruit Neopixel, DS3231, RTClib and more.

<html><iframe width="560" height="315" src="https://www.youtube.com/embed/-K1nevuzlrw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></html>
