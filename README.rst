Configure and read accelerometer data from a BMI270 sensor on thingy 53. 

The original Zephyr sample assumes that the BMI 270 is connected over I2C. However, on the thingy 53, BMI270 is connected over SPI. The overlay file notes that. 

It was tested on Connect SDK 2.9.0. The thingy 53 outputs on a serial terminal port. 


