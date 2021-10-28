# Experiment - 11

**Aim:** Analyse the waveforms of a single phase half bridge inverter using Simulink.
  
**Software Required:** Matlab Simulink 

**Components:** Voltage source, MOSFET, voltage measurement block, scope, display, pulse generator.    

**Theory:**  Single Phase Half Bridge Inverter is a type of Single-Phase Bridge Inverter. It is a voltage source inverter. Voltage source inverter means that the input power of the inverter is a DC voltage Source. Basically, there are two different type of bridge inverters: Single Phase Half Bridge Inverter and Single-Phase Full Bridge Inverter.  

As the input power source is DC, there is no meaning of single phase with respect to input power. However, it does have a meaning with reference to output. The output of singlephase bridge inverter is a single-phase output.  

**Circuit Diagram:**

![image](https://user-images.githubusercontent.com/43489758/139190159-2ab564bd-38ae-4c11-ae2b-d271de5ede7e.png)  
*Single phase half bridge inverter with R load*  
 
![image](https://user-images.githubusercontent.com/43489758/139190186-9969d8d7-f0b7-417e-b920-e50eeb08d77a.png)  
*Single phase half bridge inverter with L load*  

![image](https://user-images.githubusercontent.com/43489758/139190212-39fca061-475c-4639-8c9c-56030dc42954.png)  
*Single phase half bridge inverter with RL load*  

**Procedure:**

1.	To perform the experiment on a simulator open the Simulink. 
2.	Insert the required component =>  Voltage source, MOSFET, voltage measurement block, scope, display, pulse generator, etc. 
3.	Connect the circuit according to the circuit diagram. 
4.	Set block parameters such as load, input supply, scope values, etc.
5.	Run the simulator and observe the waveform using scope.


**Observation:**
 
![image](https://user-images.githubusercontent.com/43489758/139190241-f11678a3-18ae-4b58-846b-f6600bdd7a38.png)  
*Output waveform of single phase half wave rectifier with R load*

![image](https://user-images.githubusercontent.com/43489758/139190288-a63373aa-25d2-42cd-8539-a601a1172a61.png)  
*Output waveform of single phase half wave rectifier with L load*  

![image](https://user-images.githubusercontent.com/43489758/139190320-22980e25-dd33-4465-9c97-368d50162998.png)  
*Output waveform of single phase half wave rectifier with RL load*  


**Precautions:**
  
1) Check all the connections carefully.
2) Check the values of devices taken.
3) Take care of auxiliary parameters of the device
