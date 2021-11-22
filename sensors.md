# Introduction to Sensors
Sensors allow you to determine the various aspects of the external world. Just like we use our eye, ears, hands etc. to make sense of the world, we can use electronic sensors with Arduino to make decision. These sensors are *inputs* to Ardunio and they provide data on a specific thing that they are sensing. This data can be processed programmatically to cause some action in the form of an *output*.

*For example*: You can have a light sensor that detects when the sun rises (input). We can write a program that switches on the coffee maker(output), when the light sensors *seees* that there is enought sunlight.


One way to categorize sensors is to group them by what *kind of information* they can sense i.e. **digital** or **analog** 
<br><br>
<br><br>

![pushing-ceelogreen](https://user-images.githubusercontent.com/70717743/142784781-cd267c22-e60e-401e-8151-270b74c9a88b.gif)

- A **button** is a type of sensor that detects when some pressed it. In other words it either **ON** or **OFF (LOW or 0)**. This sensor can only detect 2 states. This is an example of a **digital** sensor. When reading the data from this type of sensor in Arduino, it will give you a **HIGH (1)** or **LOW (0)**.

<br><br>
<br><br>


<img src="https://user-images.githubusercontent.com/70717743/142784827-f76feaed-e1f1-4c6d-9c59-9a64013f6ef1.gif" width="30%">

- On the other hand a sensors that measures temperature can sense a **wide range**. It can vary from very cold to very hot. Or from **very low** to **very high**. This sensor can detect multiple levels. This is an example of an **analog** sensor. When reading the data from this type of sensor in Arduino, it will give you a range from **0** to **1023**. 


# Push Button (Digital Sensor)
<img src="https://cdn.sparkfun.com//assets/parts/9/0/00097-03-L.jpg" width="30%">

<img src="https://www.arduino.cc/wiki/static/73702ee121860fa04c7f6db5bc77183b/29007/circuit.png" width="70%">

- Tutorial from Arduino.cc: https://www.arduino.cc/en/Tutorial/BuiltInExamples/Button


# LDR (Light Dependent Resistor) aka **Light Sensor** (Analog Sensor)

<img src="https://www.jsumo.com/ldr-photocell-light-dependent-resistor-189-11-B.jpg">
          
- Tutorial from Cactus.io http://cactus.io/hookups/sensors/light/ldr/hookup-arduino-to-ldr-sensor

# Ultrasonic Range Sensor (Analog Sensor)
<img src="https://www.elecrow.com/pub/media/catalog/product/cache/f8158826193ba5faa8b862a9bd1eb9e9/h/c/hc-sr04_ultrasonic_ranging_sensor.jpg" width="30%">

- Tutorial from ArduinoGetStarted.com: https://arduinogetstarted.com/tutorials/arduino-ultrasonic-sensor


# IR (Infrared) Proximity Sensor (Digital Sensor)

<img src="https://aws1.discourse-cdn.com/arduino/original/4X/3/4/5/345044d096f609f73e23c7d1c8b1592110833633.jpeg" width ="30%">

- Tutorial from Arduino.cc: https://create.arduino.cc/projecthub/Raushancpr/arduino-with-ir-sensor-1579b6

# Sensor Resources
- List of Sensors available from Adafruit: https://www.adafruit.com/category/35
- Map Function: https://www.arduino.cc/reference/en/language/functions/math/map/

# Class Activity
- Create a circuit and write a corresponding program that connectes a sensor to a servo. In other words, have your servo react to your sensor data.
