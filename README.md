# 28BYJ48Stepper-Motor-Control-using-Arduino-Nano

This blog is about controlling the Stepper Motors using the ULN2803 Chipset and Arduino Nano.

I have used the Arduino Nano instead of the Uno for simplicity and there is hardly any code changes except for the pins.


## Parts needed :

Arduino Nano
Motor Driver ULN 2803 breakout board
Stepper Motor 28NYJ48

12V Wall Adapter.
5V External DC Power Supply  ( I did not source the power from Nano for fear of risking burning the Microcontroller )


## Connection / Wiring Description

The controls from the Arduino Nano to Motor Driver is from D3-> IN1, D4->IN2, D5-> IN3 and D6 -> IN4.

The outputs from the Motor Driver are OP1, OP2, OP3 and OP4



The code can be found in this repo.

Snapshot is of my Stepper motor:

![img_20180524_175537](https://user-images.githubusercontent.com/14288989/40484877-9bf3147a-5f7a-11e8-833f-f0a71566c6ed.jpg)


The Nano controlling the Motor Driver and the Motor:

![img_20180524_175553](https://user-images.githubusercontent.com/14288989/40484878-9c1ee8f2-5f7a-11e8-9887-213efb509540.jpg)

The ULN 2803 - which is similar to ULN 2003.

![img_20180524_180229](https://user-images.githubusercontent.com/14288989/40485393-03aa5078-5f7c-11e8-80d0-342d9d8c6a51.jpg)


Motor wiring diagram of the Stepper Motor.
Please follow them carefully when connecting.

The connections from the Stepper Motor to Output Pins of the Motor Driver are:

Blue goes to O/P1
Yellow goes to O/P3

Pink goes to O/P2
Orange goes to O/P4

![img_20180524_181903](https://user-images.githubusercontent.com/14288989/40486160-1f743812-5f7e-11e8-87f3-10f6029b604a.jpg)

Wiring Diagram

![screen shot 2018-05-24 at 6 05 43 pm](https://user-images.githubusercontent.com/14288989/40485871-4d4e5584-5f7d-11e8-944d-ab4132a07cd3.png)



Additional Helpful Links:

http://cyaninfinite.com/tutorials/moving-the-28byj-48-stepper-motor/

