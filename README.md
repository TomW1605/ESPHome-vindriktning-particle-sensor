# ESPHome-vindriktning-particle-sensor

ESPHome config for adding home assistnat support, tVOC, eCO2 and controllable leds to the Ikea Vindriktning particle sensor

this config has a 3 led addressable strip on pin 3, to mount the strip the 3 existing leds need to be removed from the board. all the logic for controlling the led colours is done on device so they will still work without home assistant

the device does present a monochrome light entity to HA that lets it control the on/off state and brightness of the leds (so it can be in a bedroom with the lights off at night)

![image](https://github.com/TomW1605/ESPHome-vindriktning-particle-sensor/assets/17092573/ded26d83-2ffe-4e43-90cd-14ca84c8c8c3)

![image](https://github.com/TomW1605/ESPHome-vindriktning-particle-sensor/assets/17092573/ff62b46a-ee8a-4fbc-a42a-76700df76cc6)
