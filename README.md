# Robotic-Arm-Automation - Proof of Concept
Overview

This project presents a proof-of-concept robotic arm automation system developed during the early pre-production phase at Boston Scientific, Galway.
The objective was to explore automation techniques for precision handling, assembly, and demonstration tasks in biomedical device development.
The robotic arm was programmed through its native control interface connected via a computer, allowing direct coding and task command execution.

Project Structure
Robotic-Arm-Automation/
│
├── src/           # Source codes for robotic arm task sequences
│   ├── robotic_arm_text_writing_sequence_A.py
│   ├── robotic_arm_text_writing_sequence_B.py
│   ├── robotic_arm_gluing_demo.py
│   ├── robotic_arm_electrical_tester_demo.py
│   └── robotic_arm_soldering_demo.py
│
├── models/        # 3D CAD models and assemblies used in the automation setup
│   ├── grippers/
│   ├── stands/
│   ├── nozzle_fixtures/
│   └── arm_assembly_files/
│
└── media/         # Demonstration videos and visual documentation
    ├── writing_demo.mp4
    ├── gluing_demo.mp4
    ├── soldering_demo.mp4
    └── electrical_test_demo.mp4

Key Features
Custom-coded multi-task sequences for writing, gluing, soldering, and electrical testing.
Direct programming and control via the robotic arm’s integrated web-based interface.
3D-printed fixtures and assemblies designed in SolidWorks for prototype support and tool positioning.
Code conversion to C (in progress) for integration with broader automation environments.
Future development: integration of a vision-assisted task guidance system for higher precision and adaptive motion.

Tools & Technologies
6-DOF Robotic Arm
Proprietary Web Control Interface (PC-connected)
Python / C Programming
SolidWorks (3D Modelling & Assembly Design)
3D Printing for Custom Fixtures and Grippers

Confidentiality Statement
This project was completed as part of an internship at Boston Scientific within the Process Engineering & R&D Team.
All data and files included in this repository have been reviewed and approved for external sharing.
No confidential production details, proprietary device information, or intellectual property have been disclosed.

Acknowledgment
Developed during the Boston Scientific Internship Program (2025–2026).
This project served as an exploratory stage in automation feasibility, combining elements of mechanical design, programming, and pre-production testing for biomedical device manufacturing.
