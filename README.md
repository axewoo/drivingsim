# This project is very much wip, i'm doing this as an end of year project in school.

## General Info about the project

[Complete documentation of the serial connection and pinout](https://github.com/axewoo/drivingsim/blob/main/YMPC-SerialDocumentation)


### Programs and components : 
* Board : [STM32F407VGT6-Discovery](https://www.st.com/en/microcontrollers-microprocessors/stm32f407vg.html)
* Motor : Mige 130ST-M10015 6A 220V 10N.m
* Motor driver : YMPC AASD-30A-V6.3
* Connection to the board : Serial by the CN2 Port
* Program tried : MMOSFFB_Tool, FFBoard
* Firmware tried : MMOSFFB_Firmware, FFBoard_Firmware



### Pins used on the board :
Board pins - Motor driver serial pins and identification ; Pin function
![wiring](https://github.com/axewoo/drivingsim/assets/63790257/df14e593-b195-4299-8988-7d3c994cf6ba)

* GND - 10 COM ; Output control signal input ground
* GND - 13 AGND ; Input control signal input ground
* GND - 6 SignIn1 ; SRV-ON
* 5V - 9 DC12-24V ; Input control signal input power 
* PE9 - 25 Vref ; Analog voltage input port. Voltage input range -10V~+10V
* PE11 - 7 SignIn2 ; Alarm reset
* PA0 - 18 PB+ ; Encoder signal output port B
* PA1 - 20 PA+ ; Encoder signal output port A
* PA2 - 15 PZ+ ; Encoder signal output port Z 

##  Asking AI to do the work because existing solutions are not working
 * [AI_Requests folder](https://github.com/axewoo/drivingsim/tree/main/requests)
 
 * [AI_Output folder](https://github.com/axewoo/drivingsim/tree/main/ai_output)
  
 * [SbS_engines](https://github.com/axewoo/drivingsim/tree/main/sbs_engines)

 * [Drive with extra files from the DIY project](https://drive.google.com/drive/folders/1pFFYzRYU7zyws9DOWmLnn82ZYaxkmd0d?usp=sharing)

### Vesc Info (maybe not used)

 * [Vesc_Firmware / bldc ](https://github.com/vedderb/bldc)

 * [Vesc_Tool](https://github.com/vedderb/vesc_tool)

 * [Vesc_bms_Firmware](https://github.com/vedderb/vesc_bms_fw)


## References :
* [MMOSForceFeedBack](https://forum.virtualracing.org/threads/diy-usb-force-feedback-controller.92420/) 
* [Open FFBoard](https://hackaday.io/project/163904-open-ffboard)
* [DIY MMOS Project for original wiring and ideas](https://hackaday.io/project/168801-diy-mmos-ffb-stm32-and-servo-drive-servo-motor)
