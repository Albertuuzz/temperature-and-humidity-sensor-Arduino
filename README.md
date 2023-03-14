# Temperature-and-humidity-sensor-Arduino
All the files and info from the author below! Credit: alberto.valle@sketch3d.mx


This is an updated 2023 tutorial on how to make a temperature and humidity sensor using an Elegoo Uno R3 Arduino. To do this, we will need the following parts:

    - LCD display
    - Breadboard
    - Potentiometer
    - DHT11 sensor (also works for DHT22)
    - Cables, with both male ends

The first thing we will do is assemble our circuit. It's simple, just follow the following diagram:

![Sin título](https://user-images.githubusercontent.com/43005371/224946401-c3c1618f-fa01-4cc7-840b-75a052e5e6af.jpg)

Remember that the red and black wires are for power (5v) and ground, respectively. Next, I'm going to make some clarifications piece by piece:

-   Humidity and temperature sensor: For this practice, I am using the DHT11 although you can use the DHT22. However, I am going to clarify some things about       the DHT11. There are two versions of the DHT11, one that comes with an LED and another that comes without an LED. In the version that comes with an LED,        each pin will be detailed as VCC, Ground or Data Pin. In my case, I have the DHT11 without an LED, so it's enough to follow the above diagram.

-   Potentiometer: For the practice, I have been using a 3-pin potentiometer, specifically the B103. I have two pins facing forward and one facing backward.         This last one is dedicated to regulating the sensitivity of the LED screen (This is important because the data may be showing on the LCD, and you may not       have noticed it due to not adjusting the potentiometer), so once you have it assembled, remember to adjust the potentiometer.

-   LCD display: We have a 16-pin LCD, the 3rd pin is the one that regulates the amount of light it should emit (it is adjusted with the potentiometer).

-   Arduino Uno: Remember to connect the Arduino to the computer via USB and then, using the Arduino IDE, run the program to display the data on the LCD.

Now, we will open the .ino file from the repository with the Arduino IDE on our PC (if you don't have it, you can download the latest version at https://www.arduino.cc/en/software). Once it's open, we will select Arduino Uno in the top left corner, as shown below.

![Captura65455](https://user-images.githubusercontent.com/43005371/224952638-907f4d3c-8f30-47e9-b1eb-3c430189a4cd.PNG)

Next, we will need to install the dht11 library and open the Arduino program from the repository.

To install the dht11 library, we will go to C:\Users\User\Documents\Arduino. In this directory, the "libraries" folder should appear, and that is where we will place the dht11 folder. If the "libraries" folder does not appear, we will go to the IDE, select Sketch, include library, and add any library, and the "libraries" folder will appear. We just need to add the dht11 folder inside the "libraries" folder (you can also try opening the folder from Sketch / open .Zip).

After that, we will click on "upload and verify," and it will be ready!

IMPORTANT

This is a tutorial detailing some things to keep in mind and updated for the year 2023. The license for all files in the repository belongs to Alberto Valle. Below, I leave his repository, tutorial, and website in Spanish. I hope this tutorial has been able to help someone :) Regards!

Download data from         --> https://drive.google.com/drive/folders/1Y-LN6PaQ-BHtK7_dDY5x4c6N_sK2HF1s

Author web page            --> https://www.sketch3d.mx/

Youtube tutorial (spanish) --> https://www.youtube.com/watch?v=LYMdgvtxP3g

