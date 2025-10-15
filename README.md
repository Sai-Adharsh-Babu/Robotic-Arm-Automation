# Robotic-Arm-Automation - Proof of Concept

## Overview
This project demonstrates a proof-of-concept robotic arm automation developed during the early pre-production phase at **Boston Scientific, Galway**.  
The goal was to explore precision automation techniques for handling and assembly tasks in biomedical device manufacturing.  
The system was programmed to perform a range of controlled demonstrations, showcasing flexibility in motion planning, tool integration, and process reliability.

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

## Repository Contents
- **src/** – Python codes for robotic arm task sequences (writing, gluing, soldering, testing)
- **models/** – SolidWorks 3D models and assemblies for automation
- **media/** – Demonstration videos showing working sequences


## Confidentiality Statement

This project was completed as part of an internship at Boston Scientific within the Process Engineering & R&D Team.
All data and files included in this repository have been reviewed and approved for external sharing.
No confidential production details, proprietary device information, or intellectual property have been disclosed.

## Acknowlwdgement

Developed during the Boston Scientific Internship Program (2025–2026).
This project served as an exploratory stage in automation feasibility, combining elements of mechanical design, programming, and pre-production testing for biomedical device manufacturing.
