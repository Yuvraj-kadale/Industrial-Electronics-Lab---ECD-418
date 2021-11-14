# Experiment - 9

**Aim:** Simulation of Step-down Chopper using Matlab Simulink.    
  
**Software Required:** Matlab Simulink 

**Components:** AC Voltage source, Resistor Load, voltage measurement block, scope.    

**Theory:**  A Step-down chopper is a static device that step downs its DC input voltage. The value of average output DC voltage of this chopper is less than that of its fixed DC input source voltage. This type of chopper is more common.  

![image](https://user-images.githubusercontent.com/43489758/141698075-240eadd8-e0b2-4f77-9c83-d274e4735e98.png)   

*Working principle:*

*Case-1: When Chopper CH is switched ON.*

When CH is switched ON, the source is directly connected to load and hence the output voltage Vo becomes equal to Vs. The time period for which chopper is kept ON is called ON Time of chopper and represented by TON. Thus, Vo will be equal to Vs for time TON. During the ON period of chopper, the current will build in the load exponentially and will reach its maximum value at the end of TON (It is assumed that TON is less than the time required for load current to reach its steady state value). This, simply means that the maximum value of load current io will be less than the steady state value.  

*Case-2: When Chopper CH is switched OFF.* 

When chopper in figure-(i) is switched OFF, the load is disconnected from the source Vs and hence load voltage Vo will be ZERO during the entire period for with CH is OFF. The time for which chopper is kept OFF is known as OFF time and represented by TOFF. As soon as the CH is switched OFF, the current through the inductor L (io) cannot suddenly drop to zero. Rather, it starts decreasing and hence the polarity of induced emf across the inductor reverses (opposite of polarity as shown in figure-i).
This induced emf of inductor makes free-wheeling diode forward biased and hence, free wheeling diode (D) acts as a short during TOFF. Thus, the load current continues to decay through inductor L, free-wheeling diode D and load even though the source Vs is disconnected.  

Formula of Average DC Output Voltage:  

![image](https://user-images.githubusercontent.com/43489758/141698088-a618c693-8a08-4a79-9d32-dedd3091b1d5.png)  

From the above formula, it can be concluded that the output voltage of step-down chopper can be varied from zero to source voltage Vs. This is achieved by varying the duty cycle (α)  

**Circuit Diagram:**  

![image](https://user-images.githubusercontent.com/43489758/141698095-00edaab5-b525-4c97-8bef-b22ac45a1ecd.png)  

*Step-Down Chopper*

**Procedure:**

1.	To perform the experiment on a simulator open the Simulink. 
2.	Insert the required component =>  AC Voltage source, Resistor Load, voltage measurement block, scope, etc. 
3.	Connect the circuit according to the circuit diagram. 
4.	Set block parameters such as load, input supply, scope values, etc.
5.	Run the simulator and observe the waveform using scope.


**Observation:**  

![image](https://user-images.githubusercontent.com/43489758/141698106-3d1fd50d-2e7d-4fe2-942a-a3e3e302b92b.png)  
*Output waveform of Step-Down Chopper*


**Precautions:**
  
1) Check all the connections carefully.
2) Check the values of devices taken.
3) Take care of auxiliary parameters of the device
