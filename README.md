Simple port of [Adafruit TCS34725][1] for Spark Core.
------------------------------------------------
----------
This is a simple port of Adafruit TCS34725 library for Spark Core.

###Connection###
 1. TCS34725 Vin/3V3 of TCS34725 5/3.3
 2. TCS34725 GND to GND 
 3. TCS34725 SCL to D1 (with pullup resistor)
 4. TCS34725 SDA to D0 (with pullup resistor)

###Sample Application###
The sample application is based on the [Adafruit Tutorial of TCS34725][2]. The application reads the RGB Color from the sensor and publish an event with name ***colorinfo***.

###Web Page###
I took [@bko][3]'s HTML page and modified it to include the RGB color.

###How to run the application###
Load the sample application into the Spark Core. Open the Web Page in an editor and replace the tokens *deviceid* and *access token* with actual values. Open the web page in a browser and press ***Connect*** Button.


  [1]: http://www.adafruit.com/products/1334
  [2]: https://learn.adafruit.com/adafruit-color-sensors/overview
  [3]: https://community.spark.io/t/tutorial-getting-started-with-spark-publish/3422