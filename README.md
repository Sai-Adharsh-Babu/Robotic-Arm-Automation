# Robotic-Arm-Automation - Proof of Concept

## Overview
This repository documents an **ongoing proof-of-concept project** developed during the early pre-production phase at **Boston Scientific, Galway**.  
The project explores robotic automation methods for biomedical device manufacturing, focusing on **precision motion control, modular tooling, and process integration**.  
It demonstrates programmable task sequences for nozzle handling, gluing, soldering, and testing—serving as a foundation for future vision-assisted and sensor-integrated automation.

## Key Features
- **Web-based robotic arm control interface** connected to a laptop for code upload and command execution.  
- **Automated task sequences** for writing, gluing, soldering, and electrical testing.  
- **Custom 3D-printed grippers and fixtures** designed to support automation tasks.  
- **C-language integration (in progress)** for potential industrial deployment.  
- **Vision-assisted alignment (planned extension)** for improved precision and adaptability.  

## Hardware & Tools
- 6-DOF Robotic Arm  
- Proprietary web-based programming and control system  
- Python / C Programming  
- SolidWorks (3D Modelling & Assembly Design)  
- 3D Printing for Custom Fixtures  

## Demonstration Codes
| File | Description |
|------|--------------|
| `robotic_arm_text_writing_sequence_A.py` | Writing sequence demonstrating text tracing and motion accuracy. |
| `robotic_arm_text_writing_sequence_B.py` | Alternate writing sequence with different motion path and calibration parameters. |
| `robotic_arm_gluing_demo.py` | Automated adhesive path application using precise trajectory control. |
| `robotic_arm_electrical_tester_demo.py` | Probe movement demonstration for automated contact testing. |
| `robotic_arm_soldering_demo.py` | Automated soldering sequence managing tip positioning and heating intervals. |

> **Confidentiality Note:**  
> This repository contains only non-confidential, internship-approved content.  
> No proprietary design files, device data, or production details have been disclosed.  
> All shared CAD models, code samples, and media were cleared for educational and demonstrative use.

## Repository Structure  
```
Robotic-Arm-Automation/
│
├── src/                        # Source codes for robotic arm task sequences
│   ├── robotic_arm_text_writing_sequence_A.py
│   ├── robotic_arm_text_writing_sequence_B.py
│   ├── robotic_arm_gluing_demo.py
│   ├── robotic_arm_electrical_tester_demo.py
│   ├── robotic_arm_soldering_demo.py
│   └── robotic_arm_OIST_logo_writing_sequence.py
│
├── models/                     # 3D CAD models and assemblies for automation
│   ├── 15+ individual CAD parts (.SLDPRT)
│   ├── Multiple assemblies (.SLDASM) for end-effectors, bases, and fixtures
│   └── Supporting reference files and exports (.STEP / .STL)
│
├── media/                      # Demonstration videos and documentation
│   ├── writing_demo_A.mp4
│   ├── writing_demo_B.mp4
│   ├── gluing_demo.mp4
│   ├── soldering_demo.mp4
│   ├── electrical_tester_demo.mp4
│   ├── OIST_logo_writing_sequence_demo.mp4
│   └── OIST_logo_writing_demo.mp4
│
├── LICENSE                        # License file
└── README.md                      # Project documentation (this file)
```

## Media Description
The `media/` folder contains short demonstration clips showing the robotic arm executing programmed movements for:
- Text writing sequences  
- Controlled gluing and adhesive application  
- Automated soldering and contact testing  

## License  
This project is licensed under the terms specified in the **[LICENSE](./LICENSE)** file.  

## Acknowledgment
Developed as part of an **internship at Boston Scientific** under the **Process Engineering & R&D Team**.  
This ongoing project explores the potential for robotic automation in biomedical manufacturing and aims to bridge design, coding, and real-world system integration.
