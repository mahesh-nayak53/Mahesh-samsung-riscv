

 
<details>  
<summary> Task 3 and task 5 </summary>

<details>  
<summary> Task 3 </summary>


## 15 Unique RISC-v Instructions and their 32- Bit encodings

## RISC-V Instructions and their Ecodings

**addi sp, sp, -16**  
- Type: I-Type  
- Binary Encoding: 11111111100000010000000100010011

**sd ra, 8(sp)**  
- Type: S-Type  
- Binary Encoding: 00000010000100010011010000100011

**li a5, 100**  
- Type:I-Type  
- Binary Encoding: 00000001100100000000010100010011 

**addiw a5, a5, -1**  
- Type: I-Type  
- Binary Encoding: 11111111111101010000010100011011  

**bnez a5, 10190**  
- Type: B-Type  
- Binary Encoding: 11111110101000000001011001100011  

**lui a2, 0x1**  
- Type: U-Type  
- Binary Encoding: 00000000000100011000000110111

**addi a2, a2, 954**  
- Type: I-Type  
- Binary Encoding: 11101110111000011000000110010011 

**li a1, 100**  
- Type: I-Type  
- Binary Encoding: 00000001100100000000000010010011  

**lui a0, 0x21**  
- Type: U-Type  
- Binary Encoding: 00000010000100010000000110111  

**addi a0, a0, 400**  
- Type: I-Type  
- Binary Encoding: 00000011001000010000000100010011 

 **jal ra, 10418**  
- Type: J-Type  
- Binary Encoding: 00100001100100000000001101111 

**li a0, 0**  
- Type: I-Type  
- Binary Encoding: 00000000000000000000000100010011  

**ld ra, 8(sp)**  
- Type: I-Type  
- Binary Encoding: 00000010000000010011000010000011  

**addi sp, sp, 16**  
- Type: I-Type  
- Binary Encoding: 00000000100000010000000100010011  

**ret**   
- Type: I-Type  
- Binary Encoding: 00000000000000001000000001100111  


<details>  
<summary> Task 5 </summary>

## Advanced Easy to use Burgler Alarm

Introduction
In the age of modern IoT devices, CCTV cameras are commonly used for surveillance. However, they are often difficult to install, require internet connectivity, consume significant memory, and can’t be installed in private rooms where privacy is a concern. Therefore, there is a need for a medium-level security device that can detect trespassing, is easy to install, and operates with minimal power.

Overview
The Advanced Easy to Use Burglar Alarm uses an ultrasonic radar sensor to detect any object passing through its field of view. It is equipped with a passive buzzer that alerts the user whenever an intrusion is detected. While similar functionality can be achieved with a laser detection system, where a laser is pointed at a Light Dependent Resistor (LDR) and detects trespassing when its line of sight is blocked, such systems require extensive setup and wiring and are not foolproof.

In contrast, the Advanced Easy to Use Burglar Alarm is designed for easy installation. It only needs to be placed perpendicular to a solid surface. One of the key features of this device is its adaptability through the auto-adjust feature. When placed within 0.1 – 4 meters from a solid surface and turned on, the device’s LED lights up, during which it measures the distance to the solid surface and sets its threshold. After the LED turns off, the device is ready to detect any object passing through its field of view and alerts the user with its buzzer, and just requires 5V DC power which can be provided with a 5V DC adapter or a battery bank.

Key Features
Easy Installation: Requires minimal setup; simply place it perpendicular to a solid surface, with 5v DC connection.
Auto-Adjust Feature: Automatically calibrates the detection threshold within 10 seconds of being turned on.
Adaptable Range: Can be placed between 0.1- 4 meters from the detection surface.
Low Power Consumption: Designed to operate efficiently with just 5V DC power which can be provided from a 5V adapter or a Battery bank.
Privacy-Friendly: Suitable for use in private rooms without violating privacy.

Components Required

- VSD Squadron Mini developement board
- Male USB C Cable
- HC-SR04 Ultrasonic Sensor
- Bread Board
- Male to Male; Male to Female jumper cable
- Red LED
- Passive Buzzer
- 220 Ohm Resistor
- Toggle Switch


Table for Pin Connection

**HC-SR04 Ultrasonic Sensor	 and VSD Squadron Mini**
- VCC	 to 5V
- Trig	to PD3
- Echo to	PD2
- Gnd to	Gnd

**LED,	Resistor**
- LED positive to PD4
- LED negative to	220Ω	to Gnd

**Buzzer**
- Pin 1 to	PC7 	VSD Squadron Mini
- Pin 2	to Gnd	VSD Squadron Mini
  
**Button Switch	 and VSD Squadron Mini**
- Pin 1 to	5V
- Pin 2 to	PC3




