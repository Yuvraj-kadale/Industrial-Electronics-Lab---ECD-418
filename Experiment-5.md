# Experiment - 5 

**Aim:**   
(a) To Study the functioning of Voltage Doubler.   
(b) To Study the variation of ripple with respect to the parameters Current, Frequency and Capacitance Values.  

**Software Required:** Matlab Simulink  

**Components:** Diodes, AC Voltage source, Resistor Load, current measurement block, voltage measurement block, scope.  

**Theory:** The Dc Voltage Produced by the half wave rectifier is less than the peak value of the sine wave. The size and rating of the capacitor is very large if very high voltage DC is to be produced. Voltage doubler are used when higher voltage doublers are used when higher DC voltages are needed. A typical Voltage doubler circuit is shown below in the circuit section.    

The capacitor C1 is charged through rectifier D1 to a voltage +Vmax with polarity as show in the circuit diagram during the negative half cycle. During the positive half cycle as the voltage of the source rises to Vmax the potential of C1 rises to 2 Vmax . The capacitor C2 gets charged through the rectifier D2 to 2Vmax. Depending on the time constant C2Rl where Rl is the load resistance, the output voltage will be less than 2Vmax. The rectifiers are rated to peak inverse voltage of 2Vmax & it is preferable that both C1 & c2 have the same rating to affect equal amount of charge transfer. The Ripple factor is directly proportional to the load Current.  

Ripple is calculated using the formula:  

> ½ x F [(1/C1) + (1/C2)] 

**Circuit Diagram:**
 
*Circuit Diagram of Voltage Doubler*  

**Procedure:**  

1.	To perform the experiment on a simulator open the Simulink. 
2.	Insert the required component => Diodes, AC Voltage source, Resistor Load, current measurement block, voltage measurement block, scope, etc. 
3.	Connect the circuit according to the circuit diagram. 
4.	Set block parameters such as load, input supply, scope values, etc.
5.	Run the simulator and observe the waveform using scope.

**Observation:**  

 
*Output Wave form of Voltage Doubler*

**Precautions:**  

1) Check all the connections carefully.
2) Check the values of devices taken.
3) Take care of auxiliary parameters of the device
