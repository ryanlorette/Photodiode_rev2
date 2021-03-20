# Photodiode_rev2
This function simulates the photodiode circuit, designed to take an input of five doubles which represent the current produced by the photodiodes. 
The input currents are expected to have values ranging from 1.7 uA to 170 uA 
The Reference voltage used is 3.3 V, and the resistor implemented is 10 kOhms. 
The input currents are compiled in an array named PD_comp. 
The current to voltage transition is incorporated into the ADC digital conversion equation, which was provided in page 28 of the ADC datasheet. 
That is, V_in = I_in x R_ref (Ohm's Law) was incorporated into the digital equation. 
