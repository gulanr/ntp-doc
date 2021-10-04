---
title: Hardware
parent: Test Facility Design
has_children: true
nav_order: 2
---
# Overview of the Test Stand Hardware

## Test Stand Configuration
The test stand is capable of suppling 100 psi to a heated test article. A 30 gallon supply tank provides air storage, or other gas canisters can be connected as required by the experiment. Analog pressure, temperature, and mass flow gauges are attached to the tank. A manual run globe valve and pressure regulator are connected just downstream of the tank. Next is a proportional/adjustable solenoid valve to prescribe the desired mass flow rate. A digital mass flow sensor interfaces with the control software to measure the flow rate of gas to the test article. Upstream of the test article is a sensor tree which contains a thermocouple and pressure transducer. This sensor tree measures flow conditions just upstream of the test article. An additional two sensor trees measure the flow at the midpoint of the test article, and at the outlet of the test article. The P&ID for the test stand is shown below, and a list of components and their data sheets [here](datasheets.md).
|![Test Stand P&ID](media/PID.png)|
|:-:|
|*Test Stand P&ID*|

## Test Article & Interfaces
The test stand has a 12-24 UNC fluid connection with 80/20 aluminum extrusion support structure to contain the test article. While the test stand allows connecting an alternative test article, a tie tube simulator with heat sink is typically used.
|![Test Article Render](medial/../media/20210203%20-%20TA.png)|
|:-:|
|*Test Article Render*|

|![Tie Tube Render](media/20210203%20-%20TT.png)|
|:-:|
|*Tie Tube Render*|

## Part Numbers
| Project | Assembly | Subassembly | Component | Configuration | Part Number | Name                       |
| ------- | -------- | ----------- | --------- | ------------- | ----------- | -------------------------- |
| 1       | 0        | 00          | 00        | 0             | 1000-00.0   | NTP Project                |
| 1       | 1        | 00          | 00        | 0             | 1100-00.0   | Test Article               |
| 1       | 1        | 00          | 00        | M             | 1100-00.M   | Test Article Master        |
| 1       | 1        | 01          | 00        | 0             | 1101-00.0   | Tie Tube assembly          |
| 1       | 1        | 01          | 01        | 0             | 1101-01.0   | Filler                     |
| 1       | 1        | 01          | 02        | 0             | 1101-02.0   | Outer Tie Tube             |
| 1       | 1        | 01          | 03        | 0             | 1101-03.0   | Moderator                  |
| 1       | 1        | 01          | 04        | 0             | 1101-04.0   | Inner Tie Tube             |
| 1       | 1        | 01          | 05        | 0             | 1101-05.0   | Cap                        |
| 1       | 1        | 01          | 05        | 1             | 1101-05.1   | Cap - As Printed           |
| 1       | 1        | 01          | 06        | 0             | 1101-06.0   | Manifold                   |
| 1       | 1        | 01          | 06        | 1             | 1101-06.1   | Manifold - As Printed      |
| 1       | 1        | 01          | 07        | 0             | 1101-07.0   | Gasket A                   |
| 1       | 1        | 01          | 08        | 0             | 1101-08.0   | Gasket B                   |
| 1       | 1        | 01          | 09        | 0             | 1101-09.0   | Gasket C                   |
| 1       | 1        | 01          | 11        | 0             | 1101-11.0   | O-Ring A                   |
| 1       | 1        | 01          | 12        | 0             | 1101-12.0   | O-Ring B                   |
| 1       | 1        | 02          | 00        | 0             | 1102-00.0   | Heat Sink Assembly         |
| 1       | 1        | 02          | 01        | 0             | 1102-01.0   | Heat Sink Conductor        |
| 1       | 1        | 02          | 02        | 0             | 1102-02.0   | Heat Sink Beam             |
| 1       | 1        | 02          | 03        | 0             | 1102-03.0   | Heat Sink Screw            |
| 1       | 1        | 02          | 04        | 0             | 1102-04.0   | Heat Sink Washer           |
| 1       | 2        | 00          | 00        | 0             | 1200-00.0   | Test Stand                 |
| 1       | 2        | 00          | 01        | 0             | 1200-01.0   | P&ID Title Sheet           |
| 1       | 2        | 00          | 01        | 1             | 1200-01.1   | P&ID Process Sheet         |
| 1       | 2        | 01          | 00        | 0             | 1201-00.0   | Test Stand Structure       |
| 1       | 2        | 02          | 00        | 0             | 1202-00.0   | Test Stand Process         |
| 1       | 2        | 03          | 00        | 0             | 1203-00.0   | Test Stand Instrumentation |
| 1       | 2        | 03          | 01        | 0             | 1203-01.0   | Instrumentation Diagram    |
| 1       | 2        | 03          | 02        | 0             | 1203-02.0   | Pressure Transducer        |