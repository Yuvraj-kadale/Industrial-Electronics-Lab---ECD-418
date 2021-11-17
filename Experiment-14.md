# Experiment - 14

**Aim:** Analyze Three-Phase PWM Inverter using MATLAB / Simulink and also design the PWM Generator.  

**Software Required:** Matlab Simulink  

**Theory:**   

*What is Pulse Width Modulation (PWM):*   

Pulse Width Modulation (PWM) controls analog circuits with a microprocessor’s digital outputs. In this technique, Digital-to-Analog conversion is not necessary as the noise effects are minimized by keeping the signal digital. In PWM technique the energy is distributed through a series of pulses rather than a continuously varying (analog) signal. By increasing or decreasing pulse width, the energy flow to the motor shaft can be controlled.  

*Generation of Pulse Width Modulation (PWM) Signal:*  

Pulse Width Modulating signal can be generated using a Comparator as shown in the below figure. Modulating signal forms one of the input to the Comparator and the other input is fed with a non-sinusoidal wave or saw tooth wave. It operates at carrier frequency. The Comparator compares the two signals and generates a PWM signal as its output waveform.   

If the value of the Saw tooth triangle signal is more than the modulation signal then the PWM output signal is at “High” else it’s in “Low” state. Thus, the value of the input signal magnitude determines the comparator output which defines the width of the pulse generated at the output.  

![image](https://user-images.githubusercontent.com/43489758/142249280-47ff1382-de4e-4054-8c1b-57a46ea9ddf5.png)  
*Generation of PWM Signal*  


**Circuit Diagram:**
 
 ![image](https://user-images.githubusercontent.com/43489758/142249316-92ddf382-01b4-4e7d-8ad8-83e84bee343f.png)  

**Procedure:**

1.	To perform the experiment on a simulator open the Simulink. 
2.	Insert the required component => IGBT, AC Voltage source, Resistor Load, voltage measurement block, scope, etc. 
3.	Connect the circuit according to the circuit diagram. 
4.	Set block parameters such as load, input supply, scope values, etc.
5.	Run the simulator and observe the waveform using scope.


**Observation:**
 
![image](https://user-images.githubusercontent.com/43489758/142249352-b5213659-48a1-4f22-989e-ab4488cb8164.png)  

![image](https://user-images.githubusercontent.com/43489758/142249369-bf140e4f-c0a2-4fee-9655-fdfc40c43809.png)   

**Precautions:**
  
1) Check all the connections carefully.
2) Check the values of devices taken.
3) Take care of auxiliary parameters of the device
