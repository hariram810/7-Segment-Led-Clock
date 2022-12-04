# 7-Segment-Led-Clock

![Screenshot (596)](https://user-images.githubusercontent.com/118633170/205499074-0d3aafb6-d969-4ba6-b101-947b455d13ea.png)

If you have hard-time 3d printing stuff and other materials which i have provided in this project please refer the professionals for the help, [JLCPCB](https://jlcpcb.com/RNA) is one of the best company from shenzhen china they provide, PCB manufacturing, PCBA and 3D printing services to people in need, they provide good quality products in all sectors

[JLCPCB](https://jlcpcb.com/RNA)


Please use the following link to register an account in [JLCPCB](https://jlcpcb.com/RNA)

https://jlcpcb.com/RNA


Pcb Manufacturing

----------

2 layers

4 layers

6 layers

jlcpcb.com/RNA



PCBA Services

[JLCPCB](https://jlcpcb.com/RNA) have 350k+ Components In-stock. You don’t have to worry about parts sourcing, this helps you to save time and hassle, also keeps your costs down.

Moreover, you can pre-order parts and hold the inventory at [JLCPCB](https://jlcpcb.com/RNA), giving you peace-of-mind that you won't run into any last minute part shortages. jlcpcb.com/RNA



3d printing

-------------------

SLA -- MJF --SLM -- FDM -- & SLS. easy order and fast shipping makes [JLCPCB](https://jlcpcb.com/RNA) better companion among other manufactures try out [JLCPCB](https://jlcpcb.com/RNA) 3D Printing servies

[JLCPCB](https://jlcpcb.com/RNA) 3D Printing starts at $1 &Get $54 Coupons for new users

Ardhuino Controlled 7 Segment Clock Made With Leds


The clock is made using arduino and other components as mentioned the files and all pictures are attached below

the control of the clock is done by arduino or you can use 74HC595 Drivers for easy control

In this case, I used it to simulate an analog clock without its hands, with very interesting results. The hours and minutes are placed around the center of matrix giving a familiar look of analog clocks. The code I have developed applies a little of trigonometry (sine and cosine) to calculate the coordinates of hours and minutes to be shown into LED matrix. With that I saved many lines of coding.


![Screenshot (582)](https://user-images.githubusercontent.com/118633170/205499132-96c52f2b-c75f-43b0-a98b-92b88af383c7.png)

![Screenshot (594)](https://user-images.githubusercontent.com/118633170/205499137-560ff9c2-5bf2-4dee-8595-f35cb38b23e5.png)

Every time you reset or restart the Arduino, the time mode will change.

The first four digits at left of display show the hours and minutes in decimal numbers. The next three digits show the hours, minutes and seconds in binary notation and the last digit at right inform the weekday.

![Screenshot (590)](https://user-images.githubusercontent.com/118633170/205499139-f0dd3aa9-3963-437d-9fa3-33241be0c506.png)

About the code, I had to develop a way to use the "LedControl" library to turn conventional 7-Seg decimal display into a Binary display. The solution is to use "setRow" function that is usually applied for dot matrix display. 

Add TipAsk QuestionCommentDownload
Step 1: Assembly

24-hour clock display need six seven segment displays. But for building digital clock we have to use only a single microcontroller. The problem we face is the lack of input pins on the microcontroller. In Arduino UNO it contain ATMEGA328p microcontroller which has 23 input pins only. Whereas for making clock we require six displays. As one display would take 8 pins and so three SSD would take 24 pins. For making the connections we have to use multiplexing all the seven segment displays.
