BrewPi Keggle Slave
==========

This is based on the BrewPi AVR/Arduino code, and will be used to control a E-BIAB keggle.
Below is the original work:

Project Layout
--------------
The project layout is skewed by the requirement of Atmel Stutio to have all the source files in the project folder.

 - brewpi_avr - all files for building the arduino code
 - brewpi_cpp - "overlay" files that are used in preference to the files in brewpi_avr for building the desktop simulator
 - brewpi_lib - Netbeans project - a static lib from brewpi_cpp/brewpi_avr. NetBeans-integrated unit tests (simpleunit) and Google Test. 
     To run the tests, right click the "Test Files" folder and choose "Test". Simple tests are integrated into the IDE test runner, while GTests are not.
 - brewpi_sim - Netbeans project - a executable application that runs the brewpi-avr code on the desktop as a command line program. Right-click and choose "Run"

This layout is transient and will most like change as we work with the project. 

Include dirs:

 - ./brewpi_cpp
 - ./brewpi_avr
 - ./brewpi_avr/fallback



