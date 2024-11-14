Project Overview: 4-bit Calculator in Cadence Virtuoso (GPDK45nm Technology)
To complete this project, I began by designing CMOS logic gates. This was followed by other essential components such as multiplexers (MUX), decoders, and full adders, before moving on to the calculation units. The project aimed to understand how part of the Arithmetic Logic Unit (ALU) works at the transistor level, as well as how to design a chip in Very-Large-Scale Integration (VLSI) and perform physical verification checks like Design Rule Check (DRC) and Layout Versus Schematic (LVS).

Design Process of the 4-bit Binary Calculator
The 4-bit calculator comprises two main sections: arithmetic operations and the controller. The arithmetic operations section is divided into three sub-parts: addition/subtraction, multiplication, and division. The full adder is a critical, shared component across these units. The controller's role is to select the operation to execute and output the correct result.

Here’s the hierarchy of the design process:

Logic Gates from Transistors: Designed individual CMOS logic gates.

Combinational Logic Circuits: Created combinational circuits using these gates.

Calculation Units: Designed calculation units from the combinational circuits.

Full System Integration: Combined the controller and arithmetic operation units into a complete system.

Detailed Steps:
Designed CMOS schemes with appropriate transistor sizing for each logic gate.

Created symbols for each logic gate for use in combinational logic circuits.

Constructed schematics using these symbols and ran simulations to verify logic gate functionality.

Designed layouts for each gate and performed validations like DRC and LVS to ensure proper operation, preparing them for the next stage.

Created combinational logic circuits using validated logic gates, following the same process as with individual gates.

Integrated all logic gates, combinational circuits, and components to form the final system.

Conducted a validation process for the entire system.

Ran simulations and exported the waveforms into a truth table.

All designs underwent simulation, and the layout diagrams passed DRC and LVS checks.

The layout diagram was streamed into a GDS file and imported into KLayout to export it as an SVG file. I attached the GDS file, along with the KLayout properties and SVG exporter by MayeulC.

Feel free to download the Cadence Virtuoso designs I created and use them for your projects.
