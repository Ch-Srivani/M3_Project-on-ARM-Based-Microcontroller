# OBJECTIVE OF THIS PROJECT:
* By using STM32F407,buttons,4 LED's the project should be done using the timers and the sequence of glowing of LED's RED,GREEN,BLUE and the 4th acc mode either ON or OFF mode.If we press for a long time car should start or stop and by clicking the buttons the wipers speed mode should change.

# INTRODUCTION:
* we use the STM32F4xx-discovery board to illustrate an automobile wiper control system. Most automobile wipers are controlled by a DC motor, however because the STM32F4xx-discovery lacks a motor, we are exploring using LEDs in this application. As an example, the wiper control system. The STM32F4xx-discovery board has four LEDs and a Push Button. The colours of these LEDs are orange, green, red, and blue. A current limiting resistor connects four user LEDs to the PD12, PD13, PD14, and PD15 pins of PORTD on the Discovery board. To make a push button work with the STM32F407VG microcontroller, the GPIO pins will be set as digital input pins. If you push and hold the user button for two seconds, the Red When the ignition key is positioned at the ACC, the LED illuminates. Furthermore, the LEDs are flickering, indicating that the wipers are turned on.
# COMPONENTS AND SUPPLIES:
* STM32F407 Discovery Board
* Push Button
* LED's
* Resistors
* Power Supply
# ADVANTAGES:
* It is quite easy to use.
* Rain sensor-based systems are extremely simple to install.
* Individual rain sensors are fairly inexpensive.
* As a consequence, less energy is consumed.
* As a consequence, rain sensor-based equipment like vehicle wipers and irrigation systems last longer since they only work when needed.
* To save money during wet seasons, turn off the irrigation system. Electricity bills are lowered as a consequence.
*Rain sensors store water during rain events, allowing it to be available throughout the summer and winter.
# DISADVANTAGES:
* The entire system cost rises when more components, including a rain sensor, are required.
* Rain sensors must make a decision within a few minutes to avoid erroneous detection of rain.
* When water falls squarely on the rain sensor, the mechanism activates.
# COMPONENTS:
# STM32F407VG MICROCONTROLLER BOARD
# DESCRIPTION:
* The STM32F405xx and STM32F407xx family depends on the elite execution Arm?? Cortex??-M4 32-digit RISC center working at a recurrence of up to 168 MHz. The Cortex-M4 center highlights a Floating point unit (FPU) single accuracy which upholds all Arm single-accuracy information handling guidelines and information types. It likewise carries out a full arrangement of DSP guidelines and a memory insurance unit (MPU) which improves application security. The STM32F405xx and STM32F407xx family consolidates rapid implanted
## Xpack Packages:
# Windows Build Tools: 
* The xPack Windows Build Tools is a standalone Windows binary distribution of GNU make and a few of other tools required by the Eclipse Embedded CDT (formerly GNU MCU/ARM Eclipse) project, but the binaries can also be used in generic build environments.
OpenOCD:
* Open On-Chip Debugger (OpenOCD) is a free, open-source project that aims to provide debugging, in-system programming, and boundary scan using a debug adapter. The adapter is a hardware module that provides the right signals for the target to understand.
# QEMU:
* The xPack QEMU Arm is a standalone cross-platform binary distribution of QEMU, with several extensions for Arm Cortex-M devices.
# HISTORY:
* By 1917 John Oeishi shaped the Tri-Continental Corporation later to become Trico, probably the biggest maker of windshield wipers on the planet. the windshield wiper had arrived at large scale manufacturing stage! By the mid 1920s, the hand-wrenched wiper had been supplanted by a framework that utilizes motor vacuum to drive the system. Vacuum Wipers were perfect, then again, actually their speed would shift as per motor burden and speed. By the mid 60s vacuum wipers were supplanted by an electric drive, and during the 60s. teh irregular wiper was imagined (and was at first dismissed by Ford).
# FEATURES OF STM32F407VG MICROCONTROLLER:
* Up to 1 Mbyte of Flash memory.
* Up to 192+4 Kbytes of SRAM including 64-Kbyte of CCM (core coupled memory) data RAM.
* 512 bytes of OTP memory.
* Flexible static memory controller supporting Compact Flash, SRAM, PSRAM, NOR and NAND memories.
# AIM & OBJECTIVE:
* To avoid the accidents during rain conditions.
* To remove the raindrops, dust, oil or water from the windshield.
# RESEARCH:
* Application is investigated from different asset like from Google, Youtube and research papers and afterward created one application model that is Wiper Control System.
# 4W & H (WHO,WHAT,WHEN,WHERE,HOW):
* WHAT:
The operational speed of a vehicle wiper is controlled by a wiper speed control mechanism based on rain conditions. To generate, the control system incorporates a rain sensor (30) that detects rain conditions. The amplitude of an analogue signal depends on the detected rain conditions.
* WHY:
To keep the windscreen clean enough to give adequate view at all times. #WHEN The windshield wipers remove rain and snow from the windshield, while the headlights improve visibility at night.
* WHO:
Mark Anderson invented on 1902
# STRENGTH:
* Low Budget
* Decrease the accidental situation
* High Bargaining Power Supliers
* Increase safety
# WEAKNESS:
* High maintenance.
* High Transaction Cost
* Limited speed
* Week Focus on Process Innovations
* Can be frustrating at low penetration rates.
# OPPORTUNITIES:
* Emerging New Markets
* Technological Development
* Demand for Saver Equipments
* Technological Lock in of Product
* Enables novel MTM application.
# THREATS:
* Low Bargaining Power Buyers
* Highly REgulated Industry
* Ethical Pressure
* Econimical Crisis
* MTM delayed adapation.
# HIGH LEVEL REQUIREMENTS
![high level](https://user-images.githubusercontent.com/102870718/170036109-41784821-ca5c-431a-a468-9ad33627bf70.png)
# LOW LEVEL REQUIREMENTS
![low levell](https://user-images.githubusercontent.com/102870718/170036246-6d9e717d-808e-4f93-8fa7-3308ab8fa3df.png)
# HIGH LEVEL TEST CASES

![LOW LEVEL 2](https://user-images.githubusercontent.com/102870718/170037285-f9bc6727-8ca0-4de8-9af0-af700257e1ee.png)
# LOW LEVEL TEST CASES
![LOW LEVEL](https://user-images.githubusercontent.com/102870718/170037762-3d143ab9-e79f-4af4-831f-407426d26b72.png)

