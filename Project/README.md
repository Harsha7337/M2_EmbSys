# TEMPERATURE MEASUREMENT SYSTEM

| Cpp check | Code Inspector | Codacy | valgrid | Git Inspector |
| --- | --- | --- | --- | --- |
| [![Cppcheck](https://github.com/Harsha7337/M2_EmbSys/actions/workflows/cpp_check.yml/badge.svg)](https://github.com/Harsha7337/M2_EmbSys/actions/workflows/cpp_check.yml) | ![code inspector](https://api.codiga.io/project/31410/status/svg) ![codiga](https://api.codiga.io/project/31410/score/svg) | [![Codacy Badge](https://app.codacy.com/project/badge/Grade/292b98818b6f4c2ba8dc827224a10e9b)](https://www.codacy.com/gh/Harsha7337/M2_EmbSys/dashboard?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=Harsha7337/M2_EmbSys&amp;utm_campaign=Badge_Grade) | [![Valgrid](https://github.com/Harsha7337/M2_EmbSys/actions/workflows/valgrid.yml/badge.svg)](https://github.com/Harsha7337/M2_EmbSys/actions/workflows/valgrid.yml) | [![Contribution Check - Git Inspector](https://github.com/Harsha7337/M2_EmbSys/actions/workflows/Git_Inspector.yml/badge.svg)](https://github.com/Harsha7337/M2_EmbSys/actions/workflows/Git_Inspector.yml) |

### FOLDER STRUCTURE
| Folder  | Description  |
|--- |--- |
| 1_Requirements | Details about Project |
| 2_Architecture | Structural and Behavioural UML Diagrams for High Level and Low level Implementation |
| 3_Implementation | Contains Main Code |
| 4_Test Plan and Output | Required test plans and outputs |
| 5_Report | Generated Report |
| 6_ImagesandVideos | Images and Videos of the Project Implementation |

# **Introduction:**

The temperature measurement system is used to measure and control the temperature.It has been implemented by using Atmega32 in a simulation software named SimulIDE using Embedded C.

# **Research:**

Mostly used in vehicles to make sure that the equipments used are working efficiently in cold weather.It takes an analog input and generates a temperature accordingly via master slave communication.

# **Features:**

-Low Cost
-Checks if the driver is seated or not.
-Can modify the temperature according to the passenger.
-Robust System

## Details requirements
### High Level Requirements:
| ID | Description | 
|----| ------------| 
|HLR1  | When the two switches are closed, the first LED glows indicating the actuation of the system and the heater. | 
|HLR2  | Analog input from the temperature sensor | 
|HLR3  | Display. |		

#### Low Level Requirements:

| ID | Description |
|-------|------|
| LLR1 | ADC with Pulse Width Modulation.| 
| LLR2 | Compatible on different Operating Systems. |

 
#### TEST PLAN:
### High Level Test plan:
| ID    | Description                             | Expected O/P | Actual O/P |
|-------|-----------------------------------------| ------------ | ---------- |
| H_01  |Read temperature                         |PASSED        |SUCCESS     | 
| H_01  |Sensing                                  |PASSED        |SUCCESS     | 
| H_03  |enable blinking led                      |PASSED        |SUCCESS     | 


### Low Level Test Plan:
| ID    | Description           | Expected O/P | Actual O/P | 
|-------|-----------------------| ------------ | -----------| 
| L_01  |Open the app           | PASSED       |SUCESS      | 
| L_03  |Reserve seat           | PASSED       |SUCCESS     |



| CONTRIBUTION BY |
| --- |
| *A.HARSHAVARDHAN* |
