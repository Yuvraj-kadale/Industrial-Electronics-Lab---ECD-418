# Experiment -1

**Aim:**   
To observe the wave that 555 timer gives when acted as an Astable Multivibrator.  

**Software Required:**  
Multisim or MATLAB.

**Components:**  
555 Timer , Resistors , Capacitor , CRO.

**Theory:**   
An electronic device that produces a non-sinusoidal waveform as its output is known as a Multivibrator. The generated non-sinusoidal waveforms are basically a square wave, rectangular wave, a triangular wave, sawtooth wave, or ramp wave etc.
**Astable Multivibrator** is a type of multivibrator also termed as a *free running multivibrator*. It is called so because here the state changes on its own after some predetermined time interval and thus does not require a triggering pulse. Here, the output of the circuit simply oscillates between high and low state freely. Hence is just an oscillator.  

![image](https://user-images.githubusercontent.com/43489758/129487409-895aef0c-3f27-41b6-9611-a199d3a774a7.png) 
   
In Astable multivibrator, both outputs states are unstable. It can be built using 555 timer IC. A 555 timer IC has two comparators, a R-5 Flip-flop, 2 Transistors and a resistive network. The Resistive network consists of three equal resistors (5K ohms each) and acts as a voltage divider. 
Voltage at the inverting of comparators 1 will be 2/3 Vcc and the positive terminal of comparator 2 will be 1/3 Vcc. Comparator 1 compares the threshold voltage (at pin 6) with the reference voltage +2/3 Vcc. Comparator 2 compares the trigger voltage (at pin 0.2) with +1/3 Volts.  

Output of comparator 1 is applied to S input of Flip-flop A high output from flip-flop to the base of discharge transistor saturates it and thus discharge the transistor that is connected to externally to discharge pin 7 . High flip-flop output produces low timer output at pin 3. When voltage at trigger input falls below 1/3 Vcc comparator 2 produces low output. It turns off discharge transistor and Flip-flop produced low output and output timer pin goes high.

An Astable Multivibarator can be designed by adding tow resistors R1 and R2 and a capacitor C1 to the IC. Let’s assume the circuit is powered up and timer output is high. SR flip-flop output is connected to discharge transistor base. So when theta is low transistor is off. So capacitor C1 will start charging through R1 and R2. When it charges up to 2/3 Vcc comparator 1 output will go high, which is connected to s terminal of flip-flop. Theta1 will go high, timer output will be low and transistor R2 turns on. Capacitor will discharge throough the transistor and R2 when it discharges below 1/3 Vcc trigger will go low and comparoator2 will go high which is connected to R. Do theta will be low. Timer output will go high and the cycle will continue.

**Circuit Diagram:**
 
 ![image](https://user-images.githubusercontent.com/43489758/129487421-bfb914a4-7679-446b-b53d-22953a2d558d.png)  
  
*IC- 555 Block Diagram*

![image](https://user-images.githubusercontent.com/43489758/129487429-64b3c9e6-312e-45eb-8964-27d3667acf58.png)  
 
*Circuit Diagram (Simulation on Multisim- online simulator)*

**Calculations:**  

Let Thigh = Time taken to charge from 1/3 Vcc to 2/3 Vcc.  

Vc = Vcc (1-e-t/RC)  

•	1/3 Vcc = Vcc (1-e-t1/RC)  

e-t1/RC = 2/3 => t1 = -RC ln(2/3) ____________________ eq-1  

•	2/3 Vcc = Vcc (1-e-t2/RC)  

e-t2/RC = 1/3 => t2 = -RC ln(1/3) _____________________eq-2  

Subtracting eq-1 from eq-2, we get   

Thigh = t2-t1 = (1.0986 – 0.405) RC = 0.693 RC  

Where R = R1 + R2  

Therefore,  

Thigh = 0.693 (R1 + R2) C  

Now TLow = Time taken to discharge from 2/3 Vcc to 1/3 Vcc (It discharge through R2)

>So, Tlow = 0.693 R2C

Therefore, Overall period of oscillation = T.   
Where, 

>T = 0.693 (R1 + R2) C

**Procedure:**
1)	To perform the experiment on a simulator open the Simulink.
2)	Insert the required component => 555 Timer IC, Resistor, Capacitor, voltage supply , Electrical ground , reference , scope etc.
3)	Connect the circuit according to the circuit diagram.
4)	Set block parameters such as Vcc , R1 , R2, C1,C2 , time interval , etc.
5)	Run the simulator and observe the waveform using scopes.


**Observation:**

![image](https://user-images.githubusercontent.com/43489758/129487448-3968708a-be89-458e-8c5e-056e0e93fdd6.png)  

*Output Wave form of IC 555*


 ![image](https://user-images.githubusercontent.com/43489758/129487457-171d7f2d-27bc-48ff-98bc-68cfefd3fc48.png)  

*Simulation and observation on LT spice*

**Results:**
 
 
 ![image](https://user-images.githubusercontent.com/43489758/129487470-af4a730a-d460-4218-9e39-e3518e6dd936.png)  

*Simulation and waveform on multism online simulator*  


**Simulation file:**  
[![](https://www.multisim.com/api/v1/image/2129024/thxn2m9a7d7q2o9jo7lzxd-pngthumbnailcircuit/555_astable_mv_184534.png)   
Multisim Live: 555_astable_mv_184534](https://www.multisim.com/content/THxn2M9A7D7Q2o9jo7LzXD/555_astable_mv_184534/)


In the performed experiment by taking R1 = 1K ohms, R2= 1K ohms , C1= 1 microF, C2=0.01 microF.

We get Thigh = 0.693 (1K+1K) *1 = 1.386 ms.  
Tlow = 0.693 (1k)*1 = 0.693 ms.  
Total Time period = T = 2.079 ms  
The observed wave form has quite comparable result.  

**Precautions:**
1)	Check all the connections carefully.
2)	Check the values of devices taken.
3)	Take care of auxiliary parameters of the device.
