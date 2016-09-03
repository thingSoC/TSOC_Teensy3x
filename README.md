# TSOC_Teensy3x

The **TSOC_Teensy3x** is an adapter board for the excellent [Teensy Development Board](https://www.pjrc.com/teensy/) from [PJRC](https://www.pjrc.com/).

The **TSOC_Teensy3x** allows you to connect [thingSoC](http://thingsoc.github.io/), [Mikrobus](http://www.mikroe.com/mikrobus/), 
and/or [Grove System](http://www.seeedstudio.com/blog/2016/03/09/tutorial-intro-to-grove-connectors-for-arduinoraspberry-pi-projects/) 
Modules all at the same time, either standalone, or with any other thingSoC Processor or Radio module.
This gives you maximum flexiblity for parts selection and reuse. 

The thingSoC "Grovey Series" was designed as "Everyday Electronics", a no-frills, low cost, approach to modular embedded product design.
thingSoC boards are similar in size to most break-out-boards (BOBs), but feature a standardized stacking pinout, as well as an I2C metadata store (EEPROM)
to indicate what peripherals are installed.


[![thingSoC TSOC_TEENSY3X](https://github.com/thingSoC/TSOC_Teensy3x/blob/master/TSOC_Teensy3x/images/product/TSOC_Teensy3x.png?raw=true)TSOC_TEENSY3X](https://github.com/thingSoC/TSOC_TEENSY3X)

**thingSoC Reference Designs** are example thingSoC implementations that implement
various reference and testing circuits for demonstrating the use of the thingSoC libraries.
These reference designs can serve as starting templates for user designs.

---------------------------------------

## TSOC_TEENSY3X Application Pictures

The **TSOC_Teensy3x** allows you to connect [thingSoC](http://thingsoc.github.io/), [Mikrobus](http://www.mikroe.com/mikrobus/), 
and/or [Grove System](http://www.seeedstudio.com/blog/2016/03/09/tutorial-intro-to-grove-connectors-for-arduinoraspberry-pi-projects/) 
Modules all at the same time, either standalone, or with any other thingSoC Processor or Radio module.

In this example, we use the [Grovey_I2CHUB](https://github.com/thingSoC/TSOC_GROVEY_I2CHUB) with the Teensy3.x to support a Grove 16x2 LCD panel.
Since the Grove 16x2 LCD panel is a 5V peripheral, the [Grovey_I2CHUB](https://github.com/thingSoC/TSOC_GROVEY_I2CHUB) perform voltage level translation
from the 3.3V Teensy3.x processor to the 5V LCD controller.

[![thingSoC TSOC_TEENSY3X](https://github.com/thingSoC/TSOC_Teensy3x/blob/master/TSOC_Teensy3x/images/product/teensy3.1with Grove_5V_I2C_LCD_panel.png?raw=true)*TSOC_TEENSY3X*](https://github.com/thingSoC/TSOC_TEENSY3X)

---------------------------------------

## TSOC_Teensy3x with Mikrobus "Click" peripherals


[![thingSoC TSOC_TEENSY3X](https://github.com/thingSoC/TSOC_Teensy3x/blob/master/TSOC_Teensy3x/images/product/TSOC_Teensy3x_with_Click.png?raw=true)*TSOC_TEENSY3X*](https://github.com/thingSoC/TSOC_TEENSY3X)


---------------------------------------

## TSOC_TEENSY3X Arduino Sketch Examples

Under the "examples" directory are several Arduino IDE examples for using the TSOC_TEENSY3X board with Arduino IDE.
Using the Arduino "Wire" library for I2C communications, it is simple to control the TSOC_TEENSY3X

```c
 
 
```

---------------------------------------
## Other Applications

The TSOC_TEENSY3X can also drive other devices, such as Servos, Motors, Relays and more.


---------------------------------------

## TSOC_TEENSY3X Status <a name="TSOC_TEENSY3X_status"/>

**09/02/2016:** 
Revision 1.0 - Initial Layout 


---------------------------------------
## TSOC_TEENSY3X Model Images


[![thingSoC TSOC_TEENSY3X](https://raw.githubusercontent.com/thingSoC/TSOC_TEENSY3X/master/TSOC_TEENSY3X/images/TSOC_TEENSY3X_top.png?raw=true)TSOC_TEENSY3X](https://github.com/thingSoC/TSOC_TEENSY3X)


[![thingSoC TSOC_TEENSY3X](https://raw.githubusercontent.com/thingSoC/TSOC_TEENSY3X/master/TSOC_TEENSY3X/images/TSOC_TEENSY3X_bot.png?raw=true)TSOC_TEENSY3X](https://github.com/thingSoC/TSOC_TEENSY3X)


---------------------------------------

## TSOC_TEENSY3X Documentation Index <a name="TSOC_TEENSY3X_documentation_index"/>

[TSOC_TEENSY3X Project](http://thingsoc.github.io/projects/TSOC_TEENSY3X.html)

[TSOC_TEENSY3X Hardware](https://github.com/thingSoC/TSOC_TEENSY3X/tree/master/TSOC_TEENSY3X/hardware)


---------------------------------------

## thingSoC Documentation Index <a name="thingSoC_documentation_index"/>

[thingSoC Organization Website](http://thingSoC.github.io)

[thingSoC FAQ - Frequently Asked Questions](http://thingsoc.github.io/support/faq.html)

---------------------------------------

[![thingSoC](http://thingsoc.github.io/img/projects/thingSoC/thingSoC_thumb.png?raw=true) 
*thingSoC*](http://thingsoc.github.io)
