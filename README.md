# Synthetix-4.0

Signal conditioning and extraction circuits designed using **LTSpice** and **KiCad** for isolating specific frequency components from a composite signal.

## Overview

This repository contains simulation schematics and PCB design files used to design and test circuits that extract required signals (such as **4 kHz** and **6 kHz**) from a composite input signal.
The project focuses on **analog filtering, signal conditioning, and frequency isolation**.

## Objectives

* Extract specific frequency components from a composite signal.
* Design **high-pass, low-pass, and band-pass filters**.
* Simulate circuits using **LTSpice**.
* Implement schematic and PCB design using **KiCad**.

## Repository Structure

| File                                | Description                                      |
| ----------------------------------- | ------------------------------------------------ |
| `4khz Signal Schematic (Bonus).asc` | LTSpice schematic for extracting a 4 kHz signal  |
| `6Khz Signal schematic.asc`         | LTSpice schematic for isolating the 6 kHz signal |
| `Potentiometer Schematic.asc`       | Adjustable circuit for tuning signal levels      |
| `Hackathon.kicad_pro`               | KiCad project file                               |
| `~Hackathon.kicad_pcb.lck`          | KiCad PCB lock file                              |
| `~Hackathon.kicad_sch.lck`          | KiCad schematic lock file                        |
| `SIRandNFS.m.txt`                   | Matlab analysis                                  |
|`SecondaryoutputSchematic.asc`        | Secondary Output to show purity of output       |
## Tools Used

* **LTSpice** – circuit simulation
* **KiCad** – schematic and PCB design
* **MatLAB**

## Concepts Used

* Signal conditioning
* Band-pass filtering
* High-pass and low-pass filters
* Noise reduction
* Frequency isolation


## Applications

* Analog signal processing
* Noise filtering
* Frequency component extraction
* Embedded hardware signal conditioning

