###  FreeRTOS V10.2.1 for Arduino Samd51 Boards

####  This library will allow you to create FreeRtos Projects in the arduino IDE and run them on your Samd51 boards.

Want FreeRtos for the Samd21? Use this other repository
https://github.com/BriscoeTech/Arduino-FreeRTOS-SAMD21

***************************************************************************************************************
#### Tested Boards:
 Adafruit Metro M4 Express


***************************************************************************************************************

#### Optional Feature: Wrapped Memmory Functions.

This linker setting change will allow all microcontroller malloc/free/realloc/calloc
operations to be managed by FreeRtos. This could eliminate memory corruption issues on
c++ intensive projects, or projects that might be fragmenting the heap.

Implementation Guide can be found in: "wrapping memory functions\platform.local.txt"

***************************************************************************************************************

Special thanks to these people for your help and guidance, reference material, and hard work on contributions.

Richard Barry, for creating FreeRtos and sharing it with the world  
www.FreeRtos.org  
trlafleur  
drewfish  
sergiotomasello  
godario  
TomasRoj  
feilipu  
greiman  