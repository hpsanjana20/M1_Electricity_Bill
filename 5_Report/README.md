# **Project**    

This project is helpful for generating electricity bill with the help of units consumed.
It is available 24*7 and is feasible to bussiness owners.
 
 ## **Features of the project**
 ```     
 This project's key features are :
 * You can get the electricity bill by giving the details which will be asked.
 * Bill is generated accordingly on the basis of where you live in-either Urban or Rural.
 
 ```
## **Requirements**
     Technologies and Tools Used:
     
         * Development Tool: Github Website.
         * IDE Used : Virtual Studio Code.
         * Web browser: Mozilla Firefox.
         * Languages Used: C Language, Makefile.
         * Compiler : GCC Compiler.
         * Operating System : Linux OS, Windows OS.     
## Highlevel Requirements
|HLR_ID|Description|Status|
|:--:|:--:|:--:|
|HLR_1|This project helps to get electric bill|Implemented|
|HLR_2|This project  collects all the details of the customer|Implemented|
|HLR_3|This project allows to select wherther they are from Rural or Urban|Implemented|
|HLR_4|This project generates the bill according to the number of units of power consumed|Implemented|
|HLR_5|This project allows to change the value of power per unit|Future|

    
## Lowlevel Requirements
|HLR_ID|LLR_ID|Description|Status|
|:--:|:--:|:--:|:--:|
|HLR_1|LLR_01|Selects the rate applicable according to the range of units consumed|Implemented|
|HLR_3|LLR_01|Amount according to Rural selection|Implemented|
||LLR_02|Amount according to Urban selection|Implemented|
|HLR_4|LLR_01|Rate for unit consumed within 0 and 30|Implemented|
||LLR_02|Rate for unit consumed within 31 and 100|Implemented|
||LLR_03|Rate for unit consumed within 101 and 200|Implemented|
||LLR_04|Rate for unit consumed above 200|Implemented|

# Test plan
## High_Level
Test Plan | Description | Exp I/P | Exp O/P | Actual O/P | Type of Test 
|:--:|:--:|:--:|:--:|:--:|:--:|
| H_01| User Input | details | details| details | Input test|
| H_02| User Input | 3 | Sorry Invalid Choice! |Please choose from 1 or 2 | Invalid input |


## Low_Level
Test Plan | Description | Exp I/P | Exp O/P | Actual O/P | Type of Test 
|:--:|:--:|:--:|:--:|:--:|:--:|
|L_01| Urban Amount calculation | 105 | 656 | 656.00 | Calculation|
|L_02| Urban Amount calculation  | 203| 1481 | 1481.00 | Calculation |
|L_03| Urban Amount calculation  | 372 | 2715.6 | 2715.00 | Calcualtion |
|L_04| Rural Amount calculation  | 105 | 624 | 624.00 |Calculation | 
|L_05|Rural Amount calculation  | 203 | 1380 |1380.00 | Calculation | 
|L_06|Rural Amount calculation  | 372| 2529.6 |2529.00| Calculation |


## Folder Description
Folder        | description
--------------| ----------------------------------------------
`inc`         | All header files
`src`         | Main source code for calculator
`test`        | All source code and data for testing purposes
`unity`       | All files in accordance with Unity framework

## Behavioral Diagrams


* Usecase diagram

![usecase_diagram](https://github.com/hpsanjana20/M1_Electricity_Bill/blob/main/2_Architecture/usecase_diagram.drawio.png)



* Flowchart

![flowchart](https://github.com/hpsanjana20/M1_Electricity_Bill/blob/main/2_Architecture/flowchart.drawio.png)


## Structural Diagrams

* Object Diagram

![object_Diagram](https://github.com/hpsanjana20/M1_Electricity_Bill/blob/main/2_Architecture/object_diagram.drawio.png)

* Packet Diagram

![packet_Diagram](https://github.com/hpsanjana20/M1_Electricity_Bill/blob/main/2_Architecture/packet_diagram.drawio.png)

## SWOT Analysis
![Swot_analysis](https://github.com/hpsanjana20/M1_Electricity_Bill/blob/main/6_ImagesAndVideos/SWOT%20Analysis.png)


## Implementation
    Instructions to RUN program :
    
        1. Clone my repository into your system.
        2. You should go to 3_Implementation/ folder.
        3. Run "make Run" command in your terminal for execution of program.
        
## Author
- [hpsanjana20](https://github.com/hpsanjana20)
        
 
        
