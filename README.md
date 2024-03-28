This is a project developed at the university. I designed a low-frequency audio amplifier using BJTs in OrCAD Capture and LTSpice. 

This circuit is efficient in terms of power usage, is designed to handle up to 100 mA of output current, provides adjustable output current controlled by an external potentiometer, and maintains a stable gain value of approximately 10.
During the design process, the circuit was divided into four stages: the entry stage, voltage gain stage, current gain stage, and output stage. This circuit uses a negative feedback loop.

 The circuit operates differentially with power supplies at +6.5V and -6.5V and has a load resistance of 44.7 ohms. The active devices are polarized at about 1 mA from current mirrors designed with BJTs. The main current source utilizes a BJT, leveraging the voltage across the base-emitter junction of another BJT biased in the forward-active region. This configuration ensures stable and reliable current flow throughout the circuit.
The negative feedback loop is represented by a resistive network that returns the output signal to the input. Here, the differential pair of BJTs amplifies the difference between the input signal and the loop's output.

The output stage consists of a push-pull pair of BJTs biased through a 'super-diode' circuit operating in AB class.

 All the transistors work in a forward-active region.

For this project, I designed the PCB layout using OrCAD PCB Editor. The components are placed taking into consideration thermal and power dissipation criteria and IPC standards.
