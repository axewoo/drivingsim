# drivingsim
Driving sim application and project.


Programs and components : 
Board : STM32F407VGT6-Discovery
Motor : Mige 130ST-M10015 6A 220V 10N.m
Motor driver : YMPC AASD-30A-V6.3
Connection to the board : Serial by the CN2 Port
Program tried : MMOSFFB_Tool, FFBoard
Firmware tried : MMOSFFB_Firmware, FFBoard


Pins used on the board :
Board pins - Motor driver serial pins and identification ; Pin function

GND - 10 COM ; Output control signal input ground
GND - 13 AGND ; Input control signal input ground
GND - 6 SignIn1 ; SRV-ON
5V - 9 DC12-24V ; Input control signal input power 
PE9 - 25 Vref ; Analog voltage input port. Voltage input range -10V~+10V
PE11 - 7 SignIn2 ; Alarm reset
PA0 - 18 PB+ ; Encoder signal output port B
PA1 - 20 PA+ ; Encoder signal output port A
PA2 - 15 PZ+ ; Encoder signal output port Z 
