# BindEsp32-Task1

steps to bind the esp32 with the computer:

The first step is to connect the esp32 piece to the USB port.

In the second step we will look for the esp32 segment inside the libraries in the Arduino environment and we will extract the esp32 folder.

In the third step you must make sure that there are “boards.txt”, and “platform.txt”, inside the esp32 folder. In order to compile the ESP32 code, we also need the Xtensa GNU compiler (GCC) group.

In the fourth step This file will execute get.exe and download the Xtensa GNU tools and then decompress them.


In the fifth step, we will use the LED to test. The ESP32 development board will connect to the computer via a USB micro USB cable. Once the board is connected, we should set the communication or COM port.

Then the download speed must be reduced to: 115200 and write the code BindEsp32.
