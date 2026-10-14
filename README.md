# Dual-subgate-bipolar-assisted-TFET
This project investigates an advanced Tunnel Field-Effect Transistor (TFET) architecture based on a dual-subgate-assisted MoS₂ channel, with a focus on electrostatic doping, energy-band engineering, and bipolar current amplification.
The objective is to study how electrostatic control can regulate band-to-band tunnelling and explore the potential integration of a bipolar amplification mechanism to improve output current while maintaining low OFF-state leakage and favourable switching characteristics.
Device modelling and electrical characterization are being carried out using Silvaco ATLAS TCAD, with energy-band analysis performed in TonyPlot.

OBJECTIVES:

Study the operation of a dual-subgate-assisted MoS₂ TFET.

Understand electrostatic doping and gate-induced modulation of the channel potential.

Analyse conduction-band and valence-band profiles under different bias conditions.

Investigate band-to-band tunnelling (BTBT) and its relationship with device current.

Explore the potential integration of bipolar current amplification.

Evaluate the trade-offs among ON-current, OFF-state leakage, current gain, and switching delay.

DEVICE ARCHITECTURE:

The dual-subgate TFET structure includes:

Source: Carrier injection region.
Drain: Output-current collection terminal.
Source subgate (SG): Regulates the source-side electrostatic potential.
Main gate: Controls the central channel potential.
Drain subgate (DG): Regulates the drain-side electrostatic potential.
MoS₂ channel: Two-dimensional semiconductor channel.
Al₂O₃: Gate dielectric.
SiO₂: Substrate.

The three gate terminals provide electrostatic control over different regions of the channel. Their bias conditions influence the energy-band profile and the tunnelling barrier.


 WORKING PRINCIPLE:

1. Dual-Subgate-Assisted TFET

A TFET operates through band-to-band tunnelling. The applied gate voltages modify the electrostatic potential and energy-band alignment, potentially enabling electrons to tunnel from occupied valence-band states into available conduction-band states.

The source and drain subgates provide additional control over the local band profile, allowing the tunnelling barrier to be regulated.

2. Electrostatic Doping

Electrostatic doping refers to controlling the local carrier concentration through an electric field rather than relying exclusively on chemical doping.

In this project, the subgates are investigated as a means of modifying the carrier distribution and electrostatic potential along the MoS₂ channel.

3. Bipolar Current Amplification

A bipolar amplification mechanism can potentially increase the output current through carrier injection and bipolar carrier transport.

The project explores whether this mechanism can be integrated with dual-subgate electrostatic control to improve current drive while retaining the desired low-leakage characteristics.

Note: The combined architecture is an ongoing research objective. Its current gain, leakage, and switching performance require further simulation and validation.

TOOLS AND TECHNOLOGIES:

TCAD Simulation: Silvaco ATLAS

Device Visualization: TonyPlot

Device Modelling: Semiconductor regions, gate dielectrics, electrodes, and contact work functions

Analysis: Energy-band profiles and drain-current versus gate-voltage characteristics

SIMULATION WORKFLOW:

Define the device geometry and computational mesh.

Assign material properties to MoS₂, Al₂O₃, and SiO₂.

Define the source, drain, main gate, and subgate electrodes.

Specify material parameters, doping, contact work functions, and physical models.

Apply the subgate and drain bias conditions.

Sweep the main-gate voltage and record electrical characteristics.

Visualize the conduction and valence bands in TonyPlot.

Examine the band alignment and investigate the conditions for band-to-band tunnelling.

Extend the model to investigate bipolar amplification and compare device performance.
