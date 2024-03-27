This is a project developed at university. 
I designed a low frequency audio amplifier using BJTs. In the process of this design I used 4 stages for the circuit, entry stage (a differential pair of BJTs), voltage gain stage (common emitter frequency compensated BJT), current gain stage (common collector BJT) and output stage (push-pull pair of two BJTs working in class AB). This circuit use a negative feedback loop which set the gain at about 10. 

The circuit is powered differential at +6.5V and -6.5V and has a load resistance of 22.5 ohms. The active devices are polarized at about 1 mA from current mirrors designed with BJTs. The main current source is a BJT which use the voltage of a base-emitter jonction of another BJT biased in forward-active region. 

The negative feedback loop is represented by a resistive network wich take the ouput signal and delivers it back at input, where the differential pair of BJTs, aplify the difference between the input signal and the output from the loop.

The output stage is a push-pull pair of BJTs biased through a "super-diode" circuit which work in AB class.

All the transistors work in forward active region.

For this project I designed the PCB layout too. Taking into consider the placement of components using thermal and power disipation criterias and IPC standards.
