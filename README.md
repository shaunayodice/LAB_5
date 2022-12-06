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

![image](https://user-images.githubusercontent.com/98931471/205791741-6b4f2052-6d89-41cf-92db-70c5058177c3.png)

_Part D_

The internal temperature sensor was used for this portion of the lab

_Part E_
https://github.com/shaunayodice/LAB_5/blob/main/Code%20for%20Q1

# Question 2

_Part A_

The image shown below depicts the temperature readings that were obtained using the DHT 11 temperature sensor. Using ADC, we were able to DHT 11 to read the temperature of the room. In this image shown below, you can see the temperature begins at zero and then rises to about room temperature. This indicates that the sensor was working as expected and begin reading the temperature and stored it in the ADCMEM0.

![image](https://user-images.githubusercontent.com/98931471/202036233-b93adb40-43b8-4371-be64-c97a3258d5fc.png)

_Part B_

The Level 0 block diagram for the DHT 11 can be found at the following link below. 

Level 0: https://github.com/shaunayodice/LAB_5/blob/main/Level%200_Q2.png



_Part C_

_Part D_

![image](https://user-images.githubusercontent.com/98931471/202039046-f0668170-4c7a-420e-be61-f954095e0b1e.png)


_Part E_

The code for this portion of the lab can be found at the following link:
https://github.com/shaunayodice/LAB_5/blob/main/DHT_11


