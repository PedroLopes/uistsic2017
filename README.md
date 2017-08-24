# UIST Student Innovation Contest 2017 
Welcome to the UIST Student Innovation Contest 2017, which features the desktop-sized robotic arm Arduino Braccio. 

## getting started

1. Once you receive your braccio, the first task is to get it assembled. Here's your [easiest starting point](assemble-instructions/Braccio_Quick_Start_Guide.pdf) (.pdf, step by step instructions.) Also, why not taking your time and **following** [the step-by-step video](https://www.youtube.com/watch?v=Lwb2ppat_bs) from the arduino.org folks? 
2. The next step is connecting your braccio's servo shield to your arduino UNO (it is possible to use other arduinos or even other micro controllers but for simplicity the shields retrofit nicely in the UNO without any mods). 
3. Get ready to start your code examples! Get acquainted with the [Arduino Braccio library](https://github.com/arduino-libraries/Braccio.git) (which we also copied to our Github just so you can have access to one in the same place). 
4. Remember that your braccio might need calibration at start and make sure your code doesn't overshoot (try to protect those servos from damage). 
5. Enjoy!


## programming languages, environments & dialects

Arduino's can interface with virtually anything as long as a serial port is there (it can be wireless, blue tooth, smoke signs, whatever! oh.. and USB too). This being said reinventing the wheel typically takes more time than you'll have for the UIST SIC, so try to leverage some existing programming environment that already has some features to control/communicate with arduinos. Here's some of them:

1. [Snap4Arduino](http://www.snap4arduino.org/) (if you like visual programming this is your best tool) and luckily there is a [Snap Braccio Library](https://github.com/bromagosa/Snap4Arduino/tree/master/src/libraries) contributed by our dear friend @bromagosa and here is a [video of that library in action](https://www.youtube.com/watch?v=KKZco88P9X0). 
2. Interfacing with [Python has many options](http://playground.arduino.cc/Interfacing/Python) (from the simplest ``import serial`` to the more elaborate pyFirmata, etc)
3. Does your project use VR? Than you are likely needing to interface some game engine (e.g., Unity3D) with your arduino. The simplest solution is serial messages. Here's a [tutorial for unity3d](http://www.alanzucconi.com/2015/10/07/how-to-integrate-arduino-with-unity/). 
4. Processing has a great [integration with Arduino](http://playground.arduino.cc/Interfacing/Processing) (via simple serial or firmata too)
5. [PlatformIO](http://platformio.org/lib/show/1252/Braccio) has a simple install for the braccio ``pio lib install "Braccio"`` 

## More tips
Another alternative video to assemble the braccio is provided by the folks at [elektor](https://www.youtube.com/watch?v=5VkjJXm6bx8), watch it too. 
References to [older versions](http://platformio.org/lib/show/1252/Braccio) of the braccio lib if needed.


## Contacts / Chairs
This contest is chaired by [Gierad Laput](http://www.gierad.com/) & [Pedro Lopes](http://plopes.org/). If you have any questions just reach out to us!
