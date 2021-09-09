# Experiment - 6

**Aim:** To analyse IGBT based Inverter response with various loads  
**Software Required:** Matlab Simulink
**Components:** AC Voltage source, Resistor Load, voltage measurement block, scope, IGBT. 
**Theory:** IGBT is a voltage controlled device. It is a power switching transistor which combines the advantages of MOSFETs and BJTs for use in power supply and motor control circuits. It is a three terminal, Trans conductance device that combines an insulated gate N-channel MOSFET input with a PNP bipolar transistor output connected in a type of Darlington configuration.
The IGBT block implements a semiconductor device controllable by the gate signal. The IGBT is simulated as a series combination of a resistor Ron, inductor Lon, and a DC voltage source Vf in series with a switch controlled by a logical signal (g > 0 or g = 0).
Power IGBT is high frequency operating device. It’s turn on and turn off time is small. In the IGBT based inverter 4 IGBT are used and dc voltage is converted to 230v output ac voltage. Since it is based on PWM technique pulse voltage from pulse generator is applied to all IGBT with the difference that 2 diagonal IGBT run with same start time while for other 2 IGBT some delay is provided in their pulse generator voltage. So as a result when pulse with no delays are applied they make positive output voltage across load on the other hand when pulse with delay is provided to IGBT it gives negative output voltage across load.

Circuit Diagram:
 
IGBT based PWM with R load
 
IGBT based PWM with RL load

 
IGBT based PWN with RLC load

Procedure:
1.	To perform the experiment on a simulator open the Simulink. 
2.	Insert the required component => IGBT, AC Voltage source, Resistor Load, voltage measurement block, scope, etc. 
3.	Connect the circuit according to the circuit diagram. 
4.	Set block parameters such as load, input supply, scope values, etc.
5.	Run the simulator and observe the waveform using scope.


Observation:
 
Output Wave form of IGBT based PWM with R load
 
Output Wave form of IGBT based PWM with RL load

 
Output Wave form of IGBT based PWM with RLC load


Precautions:
1) Check all the connections carefully.
2) Check the values of devices taken.
3) Take care of auxiliary parameters of the device
