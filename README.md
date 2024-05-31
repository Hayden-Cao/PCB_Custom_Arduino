# PCB_Custom_Arduino

**Overview:**  
    
  This project is based off information from the Udemy Course - Design a board in 15 hours. Step-by-Step tutorial based on Arduino project (Altium), and the open-source Arduino Uno R3 schematic. 

**Encountered Issues:** 

  There were two issues that I encountered while following this course and both were due to the fact that the course was last updated in 2020.    
    
  The first issue was that some parts that were used in the circuit were now obsolete so I had to find alternative parts based off the specfications of the parts that were used in the course.     
    
  The second issue was that Altium Designer has changed its UI since 2020 which made some options and shortcuts explained in the Udemy course obsolete. Additionally, during the creation of the schematic libraries the units of measurments on the current version of Altium Designer were different than the units of measument in the course. This led to me making a major mistake and I used different units of measurements when making different parts to place in the schematic libraries. I used mils and mm for different parts which caused issues with creating the schematic itself as I had many off grid components. When trying to correct this error by using the option to align all parts to the grid, I ended up disconnecting mutliple wires and parts which required me to go back and reconnect all disconnected parts. Furthermore, the problem was not fixed and my schematic still had multiple off-grid components. Thankfully, the grid issues of the schematic does not affect the PCB placement and layout, but I still learned that I need to keep the measurement units consistent between the creating of each part in the schematic library to the creation of the actual schematic.

Schematic:

![image](https://github.com/Hayden-Cao/PCB_Custom_Arduino/assets/130268332/8acf9905-d22f-4fce-bfde-3b03639fa933)


PCB Placement:

![image](https://github.com/Hayden-Cao/PCB_Custom_Arduino/assets/130268332/13e063b1-6665-4eac-a857-496654f282b5)


3D Model Before PCB Layout:

![image](https://github.com/Hayden-Cao/PCB_Custom_Arduino/assets/130268332/40ce8599-3114-4991-949c-761897c8bd4c)


PCB Layout (In Progress):


