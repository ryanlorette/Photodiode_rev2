# Photodiode_rev2
This function simulates the photodiode circuit, designed to take an input of five doubles which represent the current produced by five distinct photodiodes. 
The input currents are expected to have values ranging from 1.7 uA to 170 uA 
The Reference voltage used is 3.3 V, and the resistor implemented is 10 kOhms. 
The input currents are compiled in an array named PD_comp. 
The current to voltage transition is incorporated into the ADC digital conversion equation, which was provided in page 28 of the ADC datasheet. 
That is, V_in = I_in x R_ref (Ohm's Law) was incorporated into the digital equation. 
The output is an array of 5 digital signals with values ranging from 0 to 2095. These signals are 12 bits long, stored inside an unsigned integer with four leading zeros. 
