# CASduino-MEGA

This project is based on the TSXduino MEGA, simplifying its construction by using Through-Hole components and modules that simplify assembly. This project would not have been possible without the contribution of @rcmolina and @melinkv.

# Instructions

1- The PCB board is fully screen printed for easy assembly. It has jumpers to configure the positive (+) and negative (-) pins of the OLED / LCD screen

2- CASduino MEGA is a multi-screen project and accepts 16x2 / 20x4 LCD screens and OLED 0.96 / 1.3

3- CASduino MEGA can be powered by MICRO USB power with a mobile phone charger, or by a DC 7v - 12v Max transformer.

4- In the amplifier circuit, to reduce costs, they sell a PCB, see image (/ images / PAM8406), and all its components can be used

5- Download the Maxduino Firmware (MaxDuino_1.56M) adapted for arduino MEGA from MELINKV at the following link https://github.com/merlinkv

6- CASDuino MEGA has an on / off selector(MUTE) to activate the audio through the speaker to listen to the file.

7- It also has a second on / off selector to activate the output amplifier to the computer.

8- It has 6 buttons (up, down, play, stop, root and del) to navigate through the menus of the maxduino version MEGA

9- CASDuino MEGA has two potentiometers that regulate the output audio and speaker audio separately.

IMPORTANT! In this project it is necessary to take into account that to work well, the SD card recommends that it is not class10, that it is of the old ones. In my case I have a 512 Mb of aliexpress and it works perfectly. Another thing to keep in mind is that the I2C protocol of the Oled screen, which has an address that can match the Maxduino_1.30M signature of @merlinkv or be different. If the screen does not turn on, the address is different. There is a simple assembly and a sketch called I2CSCANNER, to know what address the I2C of the screen has.
Another thing to keep in mind, is that the reason for being able to activate and deactivate the amplifier simply obeys that there are computers that have turned to certain capacitors that have lost their qualities need that extra amplification, in order to correctly load the file. It is for this reason, that if this extra amplification is not necessary, an excess saturation saturation can also generate load errors. Therefore, it is recommended to do a test without amplifying the audio, and look for an optimal setting for loading files using the AUDIO potentiometer. Only in this case, if the result of the file upload fails or works randomly, make use of the amplifier and also adjust an optimum AUDIO level for the file upload.

NOTE: There is an assembly manual that explains in more detail its assembly ( https://msxmakers.design.blog/proyectos/casduino-mega/ )

# Updates

New firm update version 1.56M
https://github.com/merlinkv/MaxDuino_1.56M

 # Images
 
![Alt text](https://raw.githubusercontent.com/capsule5000/CASduino-MEGA/master/Images/foto20x4.jpg?raw=true "Title")

![Alt text](https://raw.githubusercontent.com/capsule5000/CASduino-MEGA/master/Images/IMG_20200609_121924.jpg?raw=true "Title")

![Alt text](https://raw.githubusercontent.com/capsule5000/CASduino-MEGA/master/Images/IMG_20200609_150529.jpg?raw=true "Title")

# Note

This is a work in progress, several testing must be made but it should work as is. I take no responsibiltiy for any damage to any equipment that results from the use of this board. USE AT YOUR OWN RISK!
