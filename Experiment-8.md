# Experiment - 8

**Aim:** Simulation of Step-Up Chopper using Matlab Simulink.  
  
**Software Required:** Matlab Simulink 

**Components:** AC Voltage source, Resistor Load, voltage measurement block, scope.    

**Theory:**  Step-up chopper is a static device whose average output DC voltage is greater than its input DC voltage.  

![image](https://user-images.githubusercontent.com/43489758/141697555-2d7d3327-3e43-4972-af38-5c7ef478445d.png)  
 
Switch ON Period:  When chopper (CH) is switched ON, the current will flow through the closed path formed by supply source Vs, inductor L and chopper CH. During this period, no current will flow through the load. Only source current is will flow and the value of load current io will be ZERO during the ON period. This case is depicted in figure below.  
![image](https://user-images.githubusercontent.com/43489758/141697568-1f9731ee-cbcb-4c53-91c1-52375503591b.png)  

 
Also, during the TON period, energy is stored in the inductor L. This energy storage in L is essential to boost the load output voltage above the source voltage. Therefore, a large value of L is essential in a step-up chopper. 


Switch OFF period:  When the chopper CH is switched OFF, the current through the L can not die instantaneously rather it decays exponentially. Due to this behavior of L, it will force the current through the diode D and load for the entire time period TOFF. This is shown in figure below.  

![image](https://user-images.githubusercontent.com/43489758/141697578-787955f0-6aae-41df-88a6-c106a5e29fd0.png)  

Since, the current through the inductor L tends to decrease, the polarity of the emf induced in inductor L is reversed as shown in above figure. As a result, the voltage across the load becomes equal to the sum of source voltage and emf induced in inductor. Thus, the output voltage exceeds the source voltage Vs. The load / output voltage may be written as below.  

```
Vo = Vs + L(di/dt)
```
Thus, the circuit works as a step-up chopper. It may be noted here that, the voltage across the load increases because the inductor releases its stored energy to the load during the OFF period. 
Formula for output voltage of step-up chopper:  

  ![image](https://user-images.githubusercontent.com/43489758/141697589-c3b7ad9f-0db4-4a8b-888a-bcd7a73148a5.png)  
  
It can be seen that output voltage can be stepped up by varying the duty cycle α. If the chopper is always OFF, α = 0 and hence, the output voltage Vo will be equal to source voltage Vs. Similarly, if chopper is kept always ON, the value of duty cycle will become unity and hence output voltage will become infinite. However, chopper is turned ON and OFF in such a manner that duty cycle is variable and the required stepped up average output voltage, more than source voltage, is obtained.  

  

**Circuit Diagram:**  

![image](https://user-images.githubusercontent.com/43489758/141697600-1ec84f13-5015-4ae4-9b3c-3d8329741ac1.png)  

*Step-Up Chopper*

**Procedure:**

1.	To perform the experiment on a simulator open the Simulink. 
2.	Insert the required component =>  AC Voltage source, Resistor Load, voltage measurement block, scope, etc. 
3.	Connect the circuit according to the circuit diagram. 
4.	Set block parameters such as load, input supply, scope values, etc.
5.	Run the simulator and observe the waveform using scope.


**Observation:**  

![image](https://user-images.githubusercontent.com/43489758/141697610-b4ded5a3-9dec-43e2-97bd-a24b5b505cac.png)  

*Output waveform of Step-Up Chopper*


**Precautions:**
  
1) Check all the connections carefully.
2) Check the values of devices taken.
3) Take care of auxiliary parameters of the device
