# Transistor / Amplifier Characterization

Hey! This code provides a set of tools to characterize Amplifiers in emisor or base common configuration , this is done by providing it a set of parameters: 

*   VCC - DC Supply
*   RE - Emisor Resistor
*   R1 - First resistor in the voltaje divisor
*   R2 - Second resistor in the voltaje divisor
*   R3 - Third resistor in the voltaje divisor
*   RC - Collector resistor
*   BETA - Beta/HF value
*   RL - Carge resistor
*   CC - Collector capacitance
*   CE - Emisor Capacitance 
*   CB - Base Capacitance 

Also it's able to resolve for a voltaje divisor using 1, 2 or 3 resistors. The output corresponds to: 

*   VBB
*   RB
*   VBE
*   IB
*   IC
*   VCE
*   HFE
*   HIE
*   GV
*   GI
*   ZI
*   ZO
*   FCB
*   FCE
*   FCC
*   F_min - Minimum amplification frequency for a stable voltage
*   VI_Max 
