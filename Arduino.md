
## What is Arduino?
#### From the website [Arduino.cc](http://www.arduino.cc): *"Arduino is an open-source physical computing platform based on a simple I/O board and a development environment"* More here: (https://www.arduino.cc/en/Guide/Introduction)

The Arduino ecosystem consists of 3 parts:
1. 	[The Hardware](https://www.arduino.cc/en/Main/Products): These are usually called 'boards' and they come in many different flavors each with varying features. We wil be using the [Arduino UNO board](https://store-usa.arduino.cc/products/arduino-uno-rev3/?selectedStore=us) board in this class. 
<img src="https://cdn.shopify.com/s/files/1/0438/4735/2471/products/A000066_03.front_934x700.jpg" width="20%">

2. 	[The Software](https://www.arduino.cc/en/software): To write and upload programs to the board requires the use of the Arduino IDE. Once you download this program you can upload code by connecting your board to your computers using a USB cable.
3. 	Open Source Community: The Arduino platform is [open source](https://en.wikipedia.org/wiki/Open_source) i.e. all aspects of the project are free avaible for modification and redistribution. As a result "a worldwide community of makers - students, hobbyists, artists, programmers, and professionals - has gathered around this open-source platform, their contributions have added up to an incredible amount of accessible knowledge that can be of great help to novices and experts alike." Check out the projects people have made: https://create.arduino.cc/projecthub



## 	Anatomy of the Arduino UNO board
At the core of this board is the ATMega328p microcontroller i.e. 'the brains'. This is the chip where your programs are uploaded to. 
Features:
- 14 Digital I/O (Input Output) Pins of which 6 are PWM (pulse width modulation)
- 6 Analog Input Pins

<img src="https://diyi0t.com/wp-content/uploads/2019/08/Arduino-Uno-Pinout-1.png" width ="50%">


## Uploading your first 'Sketch'
1. 	Download the [Arduino IDE](https://www.arduino.cc/en/software). Make sure to select your operating system
2. 	Using the USB, connect the Arduio to your computer
3. 	Open the LED blink example sketch: **File > Examples >01.Basics > Blink**
<img src="https://www.arduino.cc/wiki/static/769176014865d9e2b5255b4f4f6dcff2/7763a/UNO_Load_Blink.jpg" width = "50%">

4. 	Select the board from **Tools>Board>Arduino UNO**. Your board might be named differently, but look for Arduino UNO in the description.
5. 	Select the port from **Tools>Port**. This will look different depending on if you are using Windows or Mac, but you will be able to tell which port is associated to the Arduino UNO board.
<img src="https://user-images.githubusercontent.com/70717743/141707927-35eda308-3f76-427c-9a07-e2cef48d08ec.png" width = "50%">

6. 	Upload the code by clicking on the upload button:
<img src="https://www.arduino.cc/wiki/static/0bd943210336ba4022b1b4e493775d82/008e2/UNO_Upload.png" width = "20%">

7. 	You should see a blinking light on the Arduino UNO board. Congratulations!!
<img src="https://makergram.com/blog/content/images/2020/04/WillingDishonestCirriped-small-1.gif">

## Practice Activity #1
- Try changing the values in **delay(1000)**. What do you notice? 
- **digitalWrite(HIGH)** turns the LED on while **digitalWrite(LOW)** turns it off. Can you create your own blinking pattern?




## Using Servos with Arduino
<img src ="https://i0.wp.com/randomnerdtutorials.com/wp-content/uploads/2018/05/giphy.gif?resize=480%2C270&quality=100&strip=all&ssl=1">

Unlike LEDs (which are controlled by an HIGH or LOW signal) servo motors are controlled using a PWM (Pulse Width Modulated) signal. There are 6 pins that can output a PWM signal.
<img src="https://user-images.githubusercontent.com/70717743/141709094-b782e91f-e2c6-4d15-959e-804b13bec1c3.png"> 
(Source: https://www.meccanismocomplesso.org/en/arduino-servo-motors-how-they-work-and-how-to-control-them/)

#### How to use servos
1. Open your servo and identify the colors of wires. Each servo has 3 wires Power, Signal, Ground. These colors will vary depending up your type of servo. This source will help: https://learn.sparkfun.com/tutorials/hobby-servo-tutorial/all#servo-motor-background.
<img src="https://cdn.sparkfun.com/r/600-600/assets/learn_tutorials/5/2/6/servo-color-code.jpg">

2. Follow this tutorial to start using servos: https://www.arduino.cc/en/Tutorial/LibraryExamples/Sweep. 

## Practice Activity #2
- How can you change the speed of your servo?
 


