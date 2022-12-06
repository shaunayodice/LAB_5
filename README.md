# LAB_5

# Contribution Chart

![image](https://user-images.githubusercontent.com/98931471/205790717-0204429d-c57f-45a6-91a1-e79317a093aa.png)




# Question 1

_Part A_
![image](https://user-images.githubusercontent.com/98931471/202038502-597a7d9a-f9aa-46b1-9dd2-5db11ee76053.png)
Within part A, we were tasked to be able to read the ambient temperature of the lab room. To do so, the internal temperature sensor embedded onto the MSP430FR2355 board was used with ADC configuration. Within the code, both Celsius and Fahrenheit can be read within the register browser and graph. In specific, the register named ADCMEM0 was used to read the value of the temperature. In the photo shown above, it can be seen that a peak of 78 degrees Fahrenheit was detected. To be able to have this configuration, interupts and the ADC were enabled.

_Part B_


Level 0: 
https://github.com/shaunayodice/LAB_5/blob/main/LEVEL0.PNG

Level 1:
https://github.com/shaunayodice/LAB_5/blob/main/LEVEL1.PNG



_Part C_

The image below shows the UML diagram for the use of the internal temperature sensor within the MSP 430 board. For this internal temperature sensor, ADC channel 12 was used.

![image](https://user-images.githubusercontent.com/98931471/205972936-27cc0b81-1c3c-4eb6-bdde-3dcd1e5d600d.png)

_Part D_

The internal temperature sensor was used for this portion of the lab.

_Part E_
https://github.com/shaunayodice/LAB_5/blob/main/Code%20for%20Q1

# Question 2

_Part A_

The image shown below depicts the temperature readings that were obtained using the DHT 11 temperature sensor. Using ADC, we were able to DHT 11 to read the temperature of the room. In this image shown below, you can see the temperature begins at zero and then rises to about room temperature. This indicates that the sensor was working as expected and begin reading the temperature and stored it in the ADCMEM0.

![image](https://user-images.githubusercontent.com/98931471/202036233-b93adb40-43b8-4371-be64-c97a3258d5fc.png)

_Part B_

The Level 0 block diagram for the DHT 11 can be found at the following link below. 

Level 0: https://github.com/shaunayodice/LAB_5/blob/main/Level%200_Q2.png

The Level 1 block diagram for the DHT 11 is found at the following link.

Level 1: https://github.com/shaunayodice/LAB_5/blob/main/Level%201_Q2.png


_Part C_

The image below shows the UML diagram for utilizing the DHT 11 with the MSP 430 board. The process mirrors that of the internal temperature sensor. The change made was the ADC channel 1 was used for this sensor.

![image](https://user-images.githubusercontent.com/98931471/205972988-e1a63d10-df02-4cce-8375-95a51fad3843.png)


_Part D_

The image below shows the schematic for the DHT 11 temperature sensor configuration. This sensor uses ADC for communiction so it only has a singular data pin. The other pins are connected to power and ground respectively with their indicated resistors as shown. 

![image](https://user-images.githubusercontent.com/98931471/202039046-f0668170-4c7a-420e-be61-f954095e0b1e.png)


_Part E_

The code for this portion of the lab can be found at the following link:
https://github.com/shaunayodice/LAB_5/blob/main/DHT_11


