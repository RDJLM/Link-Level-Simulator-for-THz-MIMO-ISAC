# A Link-Level Simulator for Terahertz MIMO Integrated Sensing and Communication v1.0

## The code provides a demo for the following paper

If you use this simulator for education, academic research, publication, and/or other purposes, then you must cite the following paper:

H. Shi, C. Yang, and M. Peng, "Comprehensive Link-Level Simulator for Terahertz MIMO Integrated Sensing and Communication Systems with TDD Framework," TechRxivpreprint TechRxiv:170630579.91754896, 2024. DOI: doi.org/10.36227/techrxiv.170630579.91754896/v1

## License

THz MIMO ISAC System Simulator V1.0

Copyright © 2024 Beijing University of Posts and Telecommunications

All rights reserved.

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), subject to the following conditions:

The Software has already been copyrighted, and commercial use is not permitted. The above copyright notice and permission notice shall be included in all copies or substantial portions of the Software. Users shall cite the publications regarding this work.

## MATLAB version and toolboxes required

- MATLAB R2023a or above.
- Parallel Computing Toolbox, Communications Toolbox, and Phased Array System Toolbox.

## Main characteristics

- Link-level performance evaluation and analysis for THz MIMO ISAC based on TDD framework.
- Terahertz peculiarity modeling.
- Standard OFDM and DFT-s-OFDM waveforms.
- Range-velocity-angle estimation and localization with virtual MIMO array technique.
- Sensing-aided downlink communication with spatial multiplexing.
- A user interface with elaborate parameter configuration.

## How to get started

- Simply click and run THz_MIMO_ISAC_Simulator.mlapp,
- Configure the required parameters on the user interface and click 'Run Simulation',
- Wait for the simulation to complete and pop up a successful run message box, then click the 'Plot' and 'Show Numerical Results' buttons to view the simulation results.

## Notes

- 32 GB RAM or above is recommended for the simulation of large number of subcarriers, symbols and antennas.
- Before running the simulation, it is recommended to load parallel operations via the command of 'parpool('Processes');' for faster computation of terahertz molecular absorption coefficient.
- The logical connection between the user interface and the main functions (THz_MIMO_OFDM_Sen.p and THz_MIMO_OFDM_Com.p) can be checked in the 'Design View' and 'Code View' of file THz_MIMO_ISAC_Simulator.mlapp, and users can modify the details.
- When inappropriate parameters are set, the simulator will force a stop and present an error warning via both message box and command line window.

## Version history

- v1.0: Initial version and demo for GitHub release and paper publication, and still under developing and debugging.

## Contact information

Postgraduate student: rdjlm@bupt.edu.cn (currently in charge)

Doctoral student: zx2000@bupt.edu.cn
