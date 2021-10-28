# Experiment - 7

**Aim:** To analyze the Three Phase Mid-Point 6-Pulse Uncontrolled Rectifier or six-phase half-wave diode rectifier or threephase M-6 diode rectifier with various loads. (using MATLAB Simulink).  
  
**Software Required:** Matlab Simulink 

**Components:** AC Voltage source, Resistor Load, voltage measurement block, scope, IGBT.    

**Theory:**  Three-phase rectification, also known as poly-phase rectification circuits are similar to the previous single-phase rectifiers, the difference this time is that we are using three, singlephase supplies connected together that have been produced by one single three-phase generator. The advantage here is that 3-phase rectification circuits can be used to power many industrial applications such as motor control or battery charging which require higher power requirements than a single-phase rectifier circuit is able to supply.  

3-phase supplies take this idea one step further by combining together three AC voltages of identical frequency and amplitude with each AC voltage being called a “phase”. These three phases are 120 electrical degrees out-of-phase from each other producing a phase sequence, or phase rotation of: 360o ÷ 3 = 120o As before, assuming a phase rotation of Red-Yellow-Blue (VA – VB – VC) and the red phase (VA) starts at 0o . Each phase connects between a pair of diodes as shown. One diode of the conducting pair powers the positive (+) side of load, while the other diode powers the negative (-) side of load. Diodes D1 D3 D2 and D4 form a bridge rectifier network between phases A and B, similarly diodes D3 D5 D4 and D6 between phases B and C and D5 D1 D6 and D2 between phases C and A.    

Thus diodes D1 D3 and D5 feed the positive rail and depending on which one has a more positive voltage at its anode terminal conducts. Likewise, diodes D2 D4 and D6 feed the negative rail and whichever diode has a more negative voltage at its cathode terminal conducts. Then we can see that for three-phase rectification, the diodes conduct in matching pairs giving a conduction pattern for the load current of: D1-2 D1-6 D3-6 D3-6 D3-4 D5-4 D5-2 and D1-2In 3-phase power rectifiers, conduction always occurs in the most positive diode and the corresponding most negative diode.   

Thus as the three phases rotate across the rectifier terminals, conduction is passed from diode to diode. Then each diode conducts for 120o (one-third) in each supply cycle but as it takes two diodes to conduct in pairs, each pair of diodes will conduct for only 60o (one-sixth) of a cycle at any one time.   

So the average DC value of the output voltage waveform from a 3-phase full-wave rectifier is given as  
  

**Circuit Diagram:**

*with R load*  

*with L load*  

*with RL load*  

**Procedure:**

1.	To perform the experiment on a simulator open the Simulink. 
2.	Insert the required component =>  Voltage source, MOSFET, voltage measurement block, scope, display, pulse generator, etc. 
3.	Connect the circuit according to the circuit diagram. 
4.	Set block parameters such as load, input supply, scope values, etc.
5.	Run the simulator and observe the waveform using scope.


**Observation:**
 
*with R load*

*with L load*  

*with RL load*  


**Precautions:**
  
1) Check all the connections carefully.
2) Check the values of devices taken.
3) Take care of auxiliary parameters of the device
