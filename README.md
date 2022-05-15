
# M3_Wiper Control System #
# Introduction #
![th](https://user-images.githubusercontent.com/101357248/168490192-bed1f9bb-091c-4c3a-8329-f8dcdac804d1.jpg)


   ![th (1)](https://user-images.githubusercontent.com/101357248/168490220-210d193d-0f8f-4526-bee9-da410ac1a6a8.jpg)




The wiper serves to clean the windshield of the car at the front and rear, although not all cars have wipers on the rear side. WIper works by removing oil, dust, rainwater, and dirt that get stuck to the windshield.If there are no wipers, of course, the rainwater that wets the glass will condense and the condition of the glass will become unclear. Not only that, dirt that sticks to the windshield for a long time, of course, is very difficult to remove. If left untreated, of course, will hinder the driver’s view and create a high risk of driving accident.  The concept of this wiper system is similar to other conventional wipers, yet this system will be upgraded to an automatic control system by using a controller. When water hits a dedicated sensor located on the windscreen, it triggers the wiper motor to move. If water is not detected by sensor, the wiper will automatically stop.

# Folder Structure #

Folder Name        |              Contents
-------------------|-----------------------------------------------
0_Absract	         | absract for Wiper Control System
1_Requirements	    | requirnments for Wiper Control System
2_Design	          | architecture for Wiper Control System
3_Implementation	  | implementation for Wiper Control System
4_TestPlanAndOutput|	test plan and output of Wiper Control System
5_Report	          | report of Wiper Control System
6_Output	          | output files of Wiper Control System
# Working Principle #
Assume that the automobile is the microcontroller(STM32F407VG). If the button is pressed , the first led (red) will turn on, Clicking again the wiper will starts , and the second led (blue) will turn on for a desired rate. If the button is pressed again , the third led (green) will turn on, and the wiper's speed will be increased in comparison to the previous one. The fourth press will turn on the fourth led (orange) , and the wiper speed will be increased in accordance with the previous one. The microcontroller (vehicle) is turned off after the fifth click of the button.
# Swot Analysis #
## Strengths ##
* Hands-Free Calling.
* Automatically detects rain and wipes the windows by moving the wiper.
* Improve safety by decreasing driver distraction.
* Low Budget.
## Weakness ##
* The rain sensor-based system functions when water falls on the sensor directly.
* Week Focus on Process Innovations.
* Structural Inertia.
## Opportunities ##
* Safety.
* Hands-free calling.
* Emerging New Markets.
## Threats ##
* Low Bargaining Power Buyers.
* Ethical Pressure.
* Once the board repaired cannot be replaced quickly.
## High Level Requirements ##
ID	 |  Description	                                                |     Status
-----|--------------------------------------------------------------|-------------------------
HLR-1|	Turn on the Ignition	                                      |   Implemented
HLR-2|	Activating wiper system	                                    |   Implemented
HLR-3|	Controlling the speed of the wiper based on frequency levels|	  Implemented
HLR-4|	Deactivating wiper system	                                  |   Implemented
HLR-5|	Turn off the Ignition	                                      |   Implemented

# Low level Requirements # 

ID	   |  Description	                                                                       |  Status
------|------------------------------------------------------------------------------------|--------------------------------------------------------
LLR-1 |	Turn on the Microcontroller	                                                       | Implemented
LLR-2 |	Press push button for 2secs – RED LED ON	                                         | Implemented
LLR-3 |	Press push button for first time - BLUE, GREEN,ORANGE LED’s glow with 1Hz frequency|	Implemented
LLR-4 |	Press push button for second time - BLUE,GREEN,ORANGE LED’s glow with 4Hz frequency|	Implemented
LLR-5 |	Press push button for third time - BLUE,GREEN,ORANGE LED,s glow with 8Hz frequency |	Implemented
LLR-6 |	Press push button for fourth time – ORANGE,GREEN,BLUE LED,s stops glowing	         | Implemented
LLR-7 |	Press push button for 2secs – RED LED OFF	                                         | Implemented
# Challenges Faced and How Was It Overcome #
* ARM Architecture concept was quite challenging.
# Learning Resources #
* Futureskill reference videos.

