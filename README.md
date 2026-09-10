# Factory I/O Color Sorting Station

A color-sorting automation project built with Factory I/O and Siemens TIA Portal.

## Features
- Vision-sensor color detection
- Blue, green, and metal sorting routes
- PLC ladder logic in TIA Portal
- HMI start/stop controls and color status lamps
- Factory I/O simulation

## Demo
LinkedIn video:http://www.linkedin.com/in/ibrahim-babiker-108837246

## Software
- Factory I/O
- Siemens TIA Portal
- S7-PLCSIM / 1211C DC/DC/DC
- WinCC

## Connections and Communication

Factory I/O
    │
    │ Driver communication
    │ (MHJ / Siemens S7-PLCSIM - 1211C DC/DC/DC)
    ▼
PLC Runtime / S7-1200 CPU
    │
    │ PROFINET (PN/IE)
    ▼
WinCC / HMI KTP700 Basic PN


## How to Run
1. Open the TIA Portal project.
2. Download the PLC program and set the CPU to RUN.
3. Start HMI Runtime.
4. Open the Factory I/O scene.
5. Configure/connect the Factory I/O driver.
6. Run the scene and operate it from the HMI.


Visit my website at: https://ibrahim-enginesite.lovable.app
