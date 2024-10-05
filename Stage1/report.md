## Stage 1 Report: Datasheet Extraction and Circuit Design

The first stage of the project focuses on analyzing the 2DA1201Y PNP BJT device from Diodes Incorporated, extracting critical parameters, and developing a structural design and a basic circuit. The report is structured in the following way to ensure a comprehensive understanding of the PNP BJT device and its practical application.

### 1. Theoretical Framework
To provide a foundation for the report, we begin with key theoretical expressions related to PNP BJT operation. This section introduces the fundamental concepts and terminologies, ensuring clarity for the subsequent sections. Topics covered include:
   - PNP BJT fundamentals: current flow, carrier injection, and recombination.
   - Biasing concepts: active, cutoff, and saturation regions.

### 2. Device Parameters and Current Equations
This section delves deeper into the mathematical representation of the PNP BJT's behavior. The current equations governing the base, collector, and emitter currents are presented, offering insights into the current-voltage (I-V) characteristics of the device. Equations for collector current (Ic) and base current (Ib) are derived as functions of voltage and doping profiles. The following are discussed:
   - Current relations between the emitter, base, and collector terminals.
   - Important parameters such as current gain (β), saturation voltage, and breakdown voltage.
   - Equation formulations based on the device’s physical and material properties.

### 3. Datasheet Parameter Extraction
The key parameters of the 2DA1201Y PNP BJT device are extracted from the provided datasheet. In this section, we interpret the plots and maximum ratings from the datasheet, focusing on:
   - Breakdown voltages (Vceo, Vcbo, Vebo).
   - Maximum continuous current (Ic(max)).
   - Estimation of Early Voltage, VA
   - Estimation of doping and physical parameters
   - Estimation of ideality factor, n
   - Estimation of Parasitic Capacitance at Base

Each parameter is derived from either the plot analysis or the maximum ratings specified, providing the foundation for the design in the following sections.

### 4. Cross-Sectional View and Layout Design
We propose the physical design of the 2DA1201Y PNP BJT, which includes:
   - **Cross-sectional view**: This depicts the vertical structure of the device, showing the key regions such as the emitter, base, and collector, along with their respective doping profiles. The cross-sectional dimensions are also discussed in relation to the extracted parameters.
   - **Top-view layout**: The top-view layout illustrates the planar structure of the device, highlighting the regions for metal contacts, isolation regions, and the junction boundaries.

This design section will also touch on the materials and dimensions used for the layers and junctions to ensure optimal device performance.

### 5. Ohmic Contact Discussion
In this section, we discuss the critical aspect of **Ohmic contact formation**, which ensures minimal resistance between the metal contacts and the semiconductor layers. The materials and techniques used to achieve proper Ohmic contact for the emitter, base, and collector terminals are highlighted, including:
   - Metal-semiconductor interface properties.
   - Contact resistance minimization strategies.

### 6. Voltage Follower Circuit Design
To illustrate the practical application of the extracted parameters, we propose a **Voltage Follower Circuit** using the 2DA1201Y PNP BJT. 
