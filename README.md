# spark_light_sensor

Adafruit for arduino and ESP8266
https://github.com/adafruit/Adafruit_TSL2591_Library

Uses Adafruit Sensor Library:
https://github.com/adafruit/Adafruit_Sensor


Buy it here:

https://learn.adafruit.com/adafruit-tsl2591/overview


I am using it for Particle Core projects.

You can compile the project using spark-cli:
http://docs.particle.io/cli/


Wiring:

    Particle pin D0 --> SDA
    SpParticleark pin D1 --> SCL
    Spark GND --> GND
    Spark 3v3 --> VIn

Go to previous level of the project folder and execute:

    particle cloud flash <your-device-id> spark_light_sensor

All code must be compiled and you can flash your bin to your core.


Use

particle serial monitor

to get data from serial
