# Experiment -2

**Aim:** To analyse the variations of pulsating dc output voltage waveform of R & L load for half wave uncontrolled rectifier.  

**Software Required:** Virtual Lab – by IITB  

**Components:** Resistors, Capacitor, Inductors, Voltage supply.  

**Theory:** A half wave uncontrolled rectifier is used to convert AC supply to pulsating DC voltage. In half wave rectifier, we are using diode as uncontrolled switch. Diode will conduct only in forward direction. So, output will show only half of positive cycles. Diode will not conduct in reverse biased direction. So, diode will not conduct in negative half cycle of AC supply.  
 
 ![image](https://user-images.githubusercontent.com/43489758/129491718-a70ae3b4-790e-4f12-bd67-047603cc7599.png)

*Circuit Diagram of Half Wave Rectifier*

**Working:**  The working of half wave rectifier is divided into two cases.  

Case 1: For positive half cycles.  
Case 2: For negative half cycles.  

**Case 1:** For positive half cycles:   
In positive half cycle, single phase 230V, 50Hz AC supply is applied to the circuit. The anode terminal of the diode becomes positive with respect to cathode. Positive supply is flowing throughout the diode.

During positive half cycle of AC supply, diode will be in forward biased conditions. Hence, positive current will be flowing into the diode. So, it will conduct from 0 to 180 degree only. So, output will show only positive half cycle.

**Case 2:** For negative half cycles:   
In negative half cycle, single phase 230V, 50Hz AC supply is applied to the circuit. The anode terminal of the diode becomes negative with respect to cathode. Negative supply will be flowing throughout the diode.
During negative half cycle of AC supply, diode will be in reverse biased conditions. Hence, diode will not conduct. Output remains zero (it will not conduct from 180 to 360 degree).   

**Wave forms:** 

 ![image](https://user-images.githubusercontent.com/43489758/129491729-b27f73f8-c311-467e-a7cf-470e1efc2c0f.png)  

*Half wave uncontrolled rectifier with R load*  

**For inductive load:**  

Working is divided into two cases:

**Case 1:** For positive half cycle
During the positive half cycle of AC supply, the diode is in forward bias condition and diode conducts. While voltage across the inductor VL opposes the change in current through the load. During this time energy is transferred from the AC source and is stored in the form of magnetic field in the inductor.

**Case 2:** For negative half cycle

During the negative half cycle of AC supply, the diode is in the reverse bias condition. As the diode is a unidirectional device, the diode does not conduct. While the induced voltage in the inductor reverses polarity and the diode conducts due to the energy stored in the inductor. It conducts till the energy in the inductor is released through the circuit. Hence due to the negative half cycle of the supply there is little load current. 
 
 ![image](https://user-images.githubusercontent.com/43489758/129491735-a871c80c-b952-48fb-b4c5-3c0709a5fd46.png)  

*Half wave uncontrolled rectifier with L load*  

**Equations/formulas:**   

Maximum load current:   
 ![image](https://user-images.githubusercontent.com/43489758/129491782-5fe5ce68-b6aa-4c7f-9190-18766e5a69d5.png)


Average load Voltage:   

 ![image](https://user-images.githubusercontent.com/43489758/129491767-955ed2f7-44b1-4e57-84df-d8dda3bdaf98.png)


Rms value of load Voltage:   

![image](https://user-images.githubusercontent.com/43489758/129491763-26876e15-e405-4367-b48c-dd25a722364c.png)

Ripple factor:   

![image](https://user-images.githubusercontent.com/43489758/129491761-19c6498a-c77b-48e0-b673-2402484bb07f.png)


Maximum efficiency:  

 ![image](https://user-images.githubusercontent.com/43489758/129491760-88d40b27-7002-4c68-bcd5-579140cfe53c.png)


DC load power:  

 ![image](https://user-images.githubusercontent.com/43489758/129491759-240f89aa-c1fc-4bea-846e-8940dc7e2080.png)


Average current:  

 ![image](https://user-images.githubusercontent.com/43489758/129491756-9c6c4636-76f9-414a-beae-1e4126f6845f.png)


**Procedure:**   

1.	Start simulator for performing the experiment.
2.	Read the procedure by click on "procedure" button.
3.	Select and place the circuits and construct the uncontrolled rectifier circuit for forward bias resistive load.
4.	User would started with “switch on circuit”, it should show assessment questions.
5.	After given the answer, user could check the final results.
6.	Get the output voltage waveform of uncontrolled rectifier for resistive load by click on next button voltmeter scope is shown. Get the output current waveform of uncontrolled rectifier for resistive load by click on next button current scope is shown.
7.	User should replace the forward bias inductive load circuit instead of forward bias resistive load circuit for uncontrolled rectifier.
8.	Repeat step 4 to step 6
9.	User should replace the reverse bias resistive load circuit instead of forward bias inductive load circuit for uncontrolled rectifier.
10.	Repeat step 4 to step 6
11.	Analyse the variations in output waveforms of resistive and inductive load by show all the waveforms button.
12.	After user has done the experiment, user should enter the values of input for resistive load as well as inductive load in the calculator table.
13.	Simulator would show the output values of average output current, voltage and power.

**Circuit Diagram:**  

 ![image](https://user-images.githubusercontent.com/43489758/129491799-4cd19fc8-a35d-4a98-8fc9-6387571b581b.png)

*Circuit Diagram for forward Bias with R Load*
 
 ![image](https://user-images.githubusercontent.com/43489758/129491803-fdeb1546-c5a4-4b1a-b4ee-cc4381b20ce8.png)

*Circuit Diagram for forward Bias with L Load*
 
 ![image](https://user-images.githubusercontent.com/43489758/129491809-e7d871ab-5a6d-4081-8e2b-87fdfd5e5ff7.png)

*Circuit Diagram for reverse Bias with R Load*

**Observations/Waveforms:**  

                        Forward Bias R load

![image](https://user-images.githubusercontent.com/43489758/129491816-43b33f8f-7275-4e2c-9c65-d1f70dbd31f3.png)

*Voltage scope for R Load*				

![image](https://user-images.githubusercontent.com/43489758/129491817-441cd5c9-c8a5-4b80-918e-89fc5329b635.png)

*Current scope for R Load*


                        Forward Bias L Load

![image](https://user-images.githubusercontent.com/43489758/129491824-d29acd2d-be7c-4872-a3a6-9d076d77fc37.png)
    
*Voltage scope for L Load*			 

![image](https://user-images.githubusercontent.com/43489758/129491830-634a5afa-8e0c-471c-90f9-6adf7489c798.png)

*Current scope for L Load*

                        Reverse Bias R Load
 

![image](https://user-images.githubusercontent.com/43489758/129491835-5f7fc58e-4ca6-4c29-af83-85de775a267c.png)

*Waveform for Reverse bias*

 ![image](https://user-images.githubusercontent.com/43489758/129491838-44a993f7-c9db-4194-8141-a7fe07c297a5.png)


**Simulation File:**

[Virtual Lab](http://vlabs.iitb.ac.in/vlabs-dev/labs/mit_bootcamp/power_electronics/labs/exp1/index.php)
