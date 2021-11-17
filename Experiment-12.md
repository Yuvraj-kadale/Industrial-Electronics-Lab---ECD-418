# Experiment - 12

**Aim:** Study the Characteristics of MOSFET, Thyristor, IGBT and GTO using MATLAB / Simulink.  
  
**Software Required:** Matlab Simulink 

**Components:** Demux, Mux, MOSFET, scope, IGBT, GTO, pulse generator, Thyristor.    

**Theory:**  
***Thyristor*** – 
A thyristor is a four-layer semiconductor device, consisting of alternating P type and N type materials (PNPN).The most common type of thyristor is the silicon-controlled rectifier (SCR). When the cathode is negatively charged relative to the anode, no current flows until a pulse is applied to the gate. The primary function of a thyristor is to control electric power and current by acting as a switch.  

***MOSFET*** – 
MOSFET stands for Metal Oxide Silicon Field Effect Transistor or Metal Oxide Semiconductor Field Effect Transistor. This is also called as IGFET meaning Insulated Gate Field Effect Transistor. The FET is operated in both depletion and enhancement modes of operation. The MOSFET (Metal Oxide Semiconductor Field Effect Transistor) transistor is a semiconductor device which is widely used for switching and amplifying electronic signals in the electronic devices. The MOSFET is a three terminal device such as source, gate, and drain.  

***IGBT*** – 
IGBT stands for insulated-gate bipolar transistor. It is a bipolar transistor with an insulated gate terminal. The IGBT combines, in a single device, a control input with a MOS structure and a bipolar power transistor that acts as an output switch. IGBTs are suitable for high-voltage, high-current applications. IGBTs are widely used as switching devices in the inverter circuit (for DC-to-AC conversion) for driving small to large motors. IGBTs for inverter applications are used in home appliances such as air conditioners and refrigerators, industrial motors, and automotive main motor controllers to improve their efficiency.   

***GTO*** – 
A gate turn-off thyristor is a special type of thyristor, which is a high-power semiconductor device. It was invented by General Electric. GTOs, as opposed to normal thyristors, are fully controllable switches which can be turned on and off by their third lead, the gate lead. It is used in high performance drive systems, such as the field oriented control scheme used in rolling mills, robotics and machine tools. It is used for traction applications because of their lighter weight. The GTO is used in inverters.
  

**Circuit Diagram:**  

![image](https://user-images.githubusercontent.com/43489758/142247615-b6a2e3a7-c875-491c-9148-4fbabe612762.png)  
*Circuit Diagram with thyristor*  
 
![image](https://user-images.githubusercontent.com/43489758/142247649-d0be9625-73bd-4be4-885a-2b7d041568d1.png)  
*Circuit Diagram with MOSFET*  

![image](https://user-images.githubusercontent.com/43489758/142247669-55ff839a-40aa-4d03-8521-253557a82236.png)  
*Circuit Diagram with IGBT*  

![image](https://user-images.githubusercontent.com/43489758/142247684-5179f697-0803-4634-9878-75a8862055db.png)  
*Circuit Diagram with GTO*  

**Procedure:**

1.	To perform the experiment on a simulator open the Simulink. 
2.	Insert the required component =>  AC Voltage source, Resistor Load, voltage measurement block, scope, etc. 
3.	Connect the circuit according to the circuit diagram. 
4.	Set block parameters such as load, input supply, scope values, etc.
5.	Run the simulator and observe the waveform using scope.


**Observation:**  

![image](https://user-images.githubusercontent.com/43489758/142247699-ba1296fb-1c03-4f99-924f-818e146b7cea.png)  
*Characteristics of thyristor*  

![image](https://user-images.githubusercontent.com/43489758/142247717-0ead9430-ea2d-4329-af98-08a78468e546.png)  
*Characteristics of MOSFET*  

![image](https://user-images.githubusercontent.com/43489758/142247735-43b9f83f-b927-484d-9091-814451d7059c.png)  
*Characteristics of IGBT*  

![image](https://user-images.githubusercontent.com/43489758/142247749-7dc0a916-1ea4-4d3f-8231-9350b9164260.png)  
*Characteristics of GTO*  


**Precautions:**
  
1) Check all the connections carefully.
2) Check the values of devices taken.
3) Take care of auxiliary parameters of the device
