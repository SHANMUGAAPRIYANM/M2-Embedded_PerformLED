# Requirements
# Introduction
   Perform LED is a simple project in Embedded progamming world. There are several ways of making a blinking LED circuit. You 
can make one using relays. You can make one using transistors. Or you can make one using components like an inverter, a 555 Timer or a microcontroller. Here swtich is used to blink the two LED using  ATmega328(a microcontroller).
# Objective
   The main objective is to blink the led using ATmega328 and a switch to controll two LED's. And Observe the Changes.
# Components used
1.ATmega328   

2.Two LED 

3.Switch

4.Resistor
# software used
1.simulIDe

2.Visual Studie Code
# Research
   Atmega328 is an Atmel microcontroller.Atmega328 has 28 pins in total. It has 3 Ports in total which are named as Port B,Port  C and Port D.Port C is an analogue Port and it has six pins in total. So, ATmega328 has 6 analogue pins.Port B and Port D are digital ports and have 7 pins each.So, in total ATmega328 has 14 digital pins. It also supports Serial Communications, we can perform serial communication via Pin  2 (RX) and Pin 3 (TX).It also supports SPI Protocol, USART Protocol.
![Introduction-to-Atmega328_8](https://user-images.githubusercontent.com/94114144/144362001-ab24a5a7-16f3-49d0-ba6c-1a3bb3a0ea57.png)


# Features
      It has simple features.
       
    1.It can switch off the LED's when switch is in off state.
    2.It can switch on the LED's when switch is in on state.
# 4W's and 1 H's
   ## Why:
    1.To blink two LED's using a switch in ATmega328.
    2.To understand basic concepts in ATmega328.
   ## Where:
    1. It can be used anywhere.
    2. It can be used for understanding purposes in schools and colleges.
   ## Who:
    1.It can be used by students.
    2.It can be used by anyone who are new to embedded programming language.
   ## When:
    1.People are trying to learn an embedded programming language.
    2.In schools and colleges it can be implemented.
   ## How
    1.By using softwares to exceute the program.
    2.By loading the program in ATmega328.
# SWOT Analysis
   ## Strengths
    1.Simple program to understand.
    2.Cost effective.
   ## Weakness
    1.Basic program.
   ## Opportunities
    1.Program can be made more complex by adding more components.
   ## Threats
    1.There are advanced programs which are simple to learn already avialable.
# High Level Requirements
| Id    	| Description     	| Status      	|
|-------	|-----------------	|-------------	|
| HLR_1 	| Microcontroller 	| Implemented 	|
| HlR_2 	| Swtich          	| Implemented 	|
| HLR_3 	| Two LED         	| Implemented 	|
| HLR_4 	| Software        	| Implemented 	|
# Low Level Requirements
| Id    	| Description              	| Status      	|
|-------	|--------------------------	|-------------	|
| LLR_1 	| ATmega328                	| Implemented 	|
| LLR_2 	| Swtich                   	| Implemented 	|
| LLR_3 	| Two LED                  	| Implemented 	|
| LLR_4 	| Visual studio & SimulIDE 	| Implemented 	|

## BEHAVIOURAL DIAGRAM

![Flowchart](https://user-images.githubusercontent.com/94114144/144385526-720b09c8-552b-45f4-8d1f-5058e9f2ab22.jpeg)

## STRUCTURAL DIAGRAM

![Blank diagram](https://user-images.githubusercontent.com/94114144/144385762-881a7d65-33e0-44be-ba9c-f975c8494528.jpeg)



## BLOCK DIAGRAM

![Blank diagram (1)](https://user-images.githubusercontent.com/94114144/144385960-380aee86-44a2-4c4d-acfa-4fd2e5772ab9.jpeg)


## Simulation
![SimuleIDE](https://user-images.githubusercontent.com/94114144/144367663-dbb047b7-8c27-48a1-91b1-1d8483224708.PNG)


## Circuit: PerformLED.simu

## Bill of Materials:

Led-2 : Led   
Led-3 : Led   
Resistor-48 : Resistor 100 Ω
Resistor-6 : Resistor 100 Ω
Resistor-9 : Resistor 100 Ω
Switch-45 : Switch   
atmega328-1 : atmega328   

# Test Plan
# High Level Requirement
| Id    	| Description 	| Expected I/P 	| Expected O/P 	| Actual O/P 	| Type Of Test 	|
|-------	|-------------	|--------------	|--------------	|:----------:	|--------------	|
| HLR_1 	| Switch on   	| High power   	| LED On       	| LED On     	| Rquirement   	|
| HLR_2 	| Switch Off  	| No power     	| LED Off      	| LED Off    	| Requirement  	|
# Low Level Requirement
| Id    	| Description 	| Expected I/P 	| Expected O/P 	| Actual O/P 	| Type Of Test 	|
|-------	|-------------	|--------------	|--------------	|:----------:	|--------------	|
| LLR_1 	| Switch on   	| value 1      	| LED On       	| LED On     	| Rquirement   	|
| LLR_2 	| Switch Off  	| value 0      	| LED Off      	| LED Off    	| Requirement  	|

## PerformLED ON
![Output](https://user-images.githubusercontent.com/94114144/144375666-fb109c0e-cc02-4cf5-9025-805224bde86c.PNG)
# PerformLED OFF
![Output Switch off](https://user-images.githubusercontent.com/94114144/144375673-b03c1212-53b6-4415-bb91-b5d829702209.PNG)








    

