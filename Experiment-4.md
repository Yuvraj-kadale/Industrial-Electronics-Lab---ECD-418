# Experiment- 4

**Aim:**   
a) To analyze the output waveforms of a Full Wave Bridge Rectifier with capacitor filter using Matlab Simulink.  
b) To analyse the output waveforms of a Centre tapped Full Wave Rectifier with resistive load using Matlab Simulink
Software Required: Matlab Simulink.  

**Components:** Diodes, AC Voltage source, Resistor Load, current measurement block, voltage measurement block, scope.  

**Theory:** Rectifier changes ac to dc and it is an essential part of power supply. The unique property of a diode, permitting the current to flow in one direction, is utilized in rectifiers. Full Wave Rectifier During the positive half cycle of the transformer secondary voltage, diode is forward biased and is reverse biased. So a current flows through the diode, load resistor and upper half of the transformer winding. During the negative half cycle, diode becomes forward biased and becomes reverse biased. The current then flows through the diode, load resistor and lower half of the transformer winding. Current flows through the load resistor in the same direction during both the half cycles. Peak value of the output voltage is less than the peak value of the input voltage by 0.6V because of the voltage drop across the diode.  

**(A)	Rectifiers with filter –**   

Capacitor input filter is the simplest and cheapest. A high value capacitor C is connected in shunt with the load resistor. Capacitor charges to peak voltage when the half cycle appears at the output. After the peak value is passed, the capacitor discharges through the load resistor slowly since the diode is reverse biased by the capacitor voltage. Before the capacitor voltage drops substantially, next output cycle arrives and the capacitor recharges to peak.

**Circuit Diagram:**
 
*Full-wave Bridge Rectifier with Capacitor filter.*


**(B)	Center tap full wave rectifier with resistive load.**  

In the case of center-tap full wave rectifier, only two diodes are used, and are connected to the opposite ends of a center-tapped secondary transformer. The center-tap is usually considered as the ground point or the zero voltage reference point. 

**Working –**   

An AC input is applied to the primary coils of the transformer. This input makes the secondary ends P1 and P2 become positive and negative alternately. For the positive half of the ac signal, the secondary point D1 is positive, GND point will have zero volt and P2 will be negative. At this instant diode D1 will be forward biased and diode D2 will be reverse biased. As explained in the Theory behind P-N Junction and Characteristics of P-N Junction Diode, the diode D1 will conduct and D2 will not conduct during the positive half cycle. Thus the current flow will be in the direction to ground. Thus, the positive half cycle appears across the load resistance RLOAD. During the negative half cycle, the secondary ends P1 becomes negative and P2 becomes positive. At this instant, the diode D1 will be negative and D2 will be positive with the zero reference point being the ground, GND. Thus, the diode D2 will be forward biased and D1 will be reverse biased. The diode D2 will conduct and D1 will not conduct during the negative half cycle.

**Circuit Diagram:**

 
*Center tap full wave rectifier with resistive load*  




**Procedure:**  
1.	To perform the experiment on a simulator open the Simulink. 
2.	Insert the required component => Diodes, AC Voltage source, Resistor Load, current measurement block, voltage measurement block, scope, etc. 
3.	Connect the circuit according to the circuit diagram. 
4.	Set block parameters such as load, input supply, scope values, etc.
5.	Run the simulator and observe the waveform using scope.

**Observation:**

 
*(a)	Output waveforms of a Full Wave Bridge Rectifier with capacitor filter*  
 
*(b)	output waveforms of a Centre tapped Full Wave Rectifier with resistive load*


**Precautions:**
1) Check all the connections carefully.
2) Check the values of devices taken.
3) Take care of auxiliary parameters of the device
