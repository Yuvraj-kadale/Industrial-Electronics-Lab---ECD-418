# Experiment -3

**Aim:** To analyse the variations of pulsating DC output voltage waveforms of a Single Phase Half Wave Uncontrolled Rectifier for R, L, C, RLC, RL, and RC loads using MATLAB Simulink.  

**Software Required:** Matlab Simulink 

**Components:** Resistors, Capacitor, Inductors, Voltage supply, Voltage Measurement, Current Measurement, Scope.  

**Theory:** A half wave uncontrolled rectifier is used to convert AC supply to pulsating DC voltage. In half wave rectifier, we are using diode as uncontrolled switch. Diode will conduct only in forward direction. So, output will show only half of positive cycles. Diode will not conduct in reverse biased direction. So, diode will not conduct in negative half cycle of AC supply.  
 
 ![image](https://user-images.githubusercontent.com/43489758/129491718-a70ae3b4-790e-4f12-bd67-047603cc7599.png)

*Circuit Diagram of Half Wave Rectifier*

**Working:**  The working of half wave rectifier is divided into two cases.  

Case 1: For positive half cycles.  
Case 2: For negative half cycles.  

**Case 1:** For positive half cycles:   
In positive half cycle, single phase 230V, 50Hz AC supply is applied to the circuit. The anode terminal of the diode becomes positive with respect to cathode. Positive supply is flowing throughout the diode.

During positive half cycle of AC supply, diode will be in forward biased conditions. Hence, positive current will be flowing into the diode. So, it will conduct from 0 to 180 degree only. So, output will show only positive half cycle.

**Case 2:** For negative half cycles:   
In negative half cycle, single phase 230V, 50Hz AC supply is applied to the circuit. The anode terminal of the diode becomes negative with respect to cathode. Negative supply will be flowing throughout the diode.
During negative half cycle of AC supply, diode will be in reverse biased conditions. Hence, diode will not conduct. Output remains zero (it will not conduct from 180 to 360 degree).   

**Wave forms:** 

 ![image](https://user-images.githubusercontent.com/43489758/129491729-b27f73f8-c311-467e-a7cf-470e1efc2c0f.png)  

*Half wave uncontrolled rectifier with R load*  

**For inductive load:**  

Working is divided into two cases:

**Case 1:** For positive half cycle
During the positive half cycle of AC supply, the diode is in forward bias condition and diode conducts. While voltage across the inductor VL opposes the change in current through the load. During this time energy is transferred from the AC source and is stored in the form of magnetic field in the inductor.

**Case 2:** For negative half cycle

During the negative half cycle of AC supply, the diode is in the reverse bias condition. As the diode is a unidirectional device, the diode does not conduct. While the induced voltage in the inductor reverses polarity and the diode conducts due to the energy stored in the inductor. It conducts till the energy in the inductor is released through the circuit. Hence due to the negative half cycle of the supply there is little load current. 
 
 ![image](https://user-images.githubusercontent.com/43489758/129491735-a871c80c-b952-48fb-b4c5-3c0709a5fd46.png)  

*Half wave uncontrolled rectifier with L load*  

**Equations/formulas:**   

Maximum load current:   
 ![image](https://user-images.githubusercontent.com/43489758/129491782-5fe5ce68-b6aa-4c7f-9190-18766e5a69d5.png)


Average load Voltage:   

 ![image](https://user-images.githubusercontent.com/43489758/129491767-955ed2f7-44b1-4e57-84df-d8dda3bdaf98.png)


Rms value of load Voltage:   

![image](https://user-images.githubusercontent.com/43489758/129491763-26876e15-e405-4367-b48c-dd25a722364c.png)

Ripple factor:   

![image](https://user-images.githubusercontent.com/43489758/129491761-19c6498a-c77b-48e0-b673-2402484bb07f.png)


Maximum efficiency:  

 ![image](https://user-images.githubusercontent.com/43489758/129491760-88d40b27-7002-4c68-bcd5-579140cfe53c.png)


DC load power:  

 ![image](https://user-images.githubusercontent.com/43489758/129491759-240f89aa-c1fc-4bea-846e-8940dc7e2080.png)


Average current:  

 ![image](https://user-images.githubusercontent.com/43489758/129491756-9c6c4636-76f9-414a-beae-1e4126f6845f.png)

**Circuit Diagram:**

![image](https://user-images.githubusercontent.com/43489758/130924089-3e6e4138-8d41-4e0b-bdbc-642e14ce9c60.png)    
*Half wave Uncontrolled Rectifier with R load*  

![image](https://user-images.githubusercontent.com/43489758/130924141-8071e083-a567-4bf0-871f-cf5d88d1c0ac.png)  
*Half wave Uncontrolled Rectifier with L load*  

![image](https://user-images.githubusercontent.com/43489758/130924175-0d4b0504-1eea-4dfa-aa62-0d4eebfab006.png)  
*Half wave Uncontrolled Rectifier with C load*  

![image](https://user-images.githubusercontent.com/43489758/130924192-d330c7fb-d7e6-4b73-9baf-f0f8a7576df4.png)   
*Half wave Uncontrolled Rectifier with RLC load*  

![image](https://user-images.githubusercontent.com/43489758/130924206-da9d7056-5c9a-401d-8f25-a21207179860.png)   
*Half wave Uncontrolled Rectifier with RL load*  

![image](https://user-images.githubusercontent.com/43489758/130924216-8956cd28-391a-42db-8d1a-6d04f7177bc2.png)   
*Half wave Uncontrolled Rectifier with RC load*  


**Procedure:** 
  
1.	To perform the experiment on a simulator open the Simulink. 
2.	Insert the required component => Resistors, Capacitor, Inductors, Voltage supply, Voltage Measurement, Current Measurement, and Scope etc.
3.	Connect the circuit according to the circuit diagram. 
4.	Set block parameters such as VIN, R, L, C, RLC, RL, RC, time interval, etc.
5.	Run the simulator and observe the waveform using scope.

**Observation:** 

![image](https://user-images.githubusercontent.com/43489758/130924238-c26ebace-5aa4-4cff-b804-a4a24db65d7e.png)  
*(a)Output Voltage with R load*

![image](https://user-images.githubusercontent.com/43489758/130924257-d42c1185-708b-4689-96fa-193d01f02a8c.png)  
*(b) Output Voltage with L load*   

![image](https://user-images.githubusercontent.com/43489758/130924283-7aea6701-39bd-4c21-b4c2-140c5babdc68.png)  
*(c) Output Voltage with C load*  

![image](https://user-images.githubusercontent.com/43489758/130924296-768ce6a3-d519-4fc8-acb6-964ca26030d3.png)  
*(d) Output Voltage with RLC load*  

![image](https://user-images.githubusercontent.com/43489758/130924315-995628b0-082c-483f-9bf6-ec480077b424.png)  
*(e) Output Voltage with RL load*  

![image](https://user-images.githubusercontent.com/43489758/130924334-cfba82ce-1a87-4551-930f-d34e7668264c.png)  
*(f) Output Voltage with RC load*  

**Simulation File:**
[Matlab Simulink](https://matlab.mathworks.com/)

**Precautions:**

1. Check all the connections carefully.
2. Check the values of devices taken.
3. Take care of auxiliary parameters of the device

