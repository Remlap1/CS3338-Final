# CS3338 Final RoboSub Documentation Project

This repository contains the CS3338 final project documentation package for the RoboSub LA Wailord autonomous underwater vehicle software system. The project focuses on requirements, design, workflow, dependency planning, snapshot objectives, and TestRail-style validation reports.

## Source Project

- Ascent RoboSub page: https://ascent.cysun.org/project/project/view/240
- RoboSub LA website: https://www.robosubla.com/
- The Ascent page links the Fall 2025 RoboSub LA SRS and SDD resources used as source context.

## Jira Kanban Board

https://cs3338robosubex.atlassian.net/jira/software/projects/KAN/boards/1?atlOrigin=eyJpIjoiNDEzOWRkZWM5MmM5NGM0NmI2NTM2NTYzYWJlOWI3ZmIiLCJwIjoiaiJ9

## Objective

The objective of the RoboSub project is to design and document a software system that supports the Wailord autonomous underwater vehicle. The system is intended to collect information from its environment, process that information, make movement decisions, navigate an underwater obstacle course, and complete tasks without user input after deployment.

The main goals are to organize the software into clear subsystems, improve documentation for future teams, support testing before real-world use, and create a reliable structure that can be expanded later.

## Document Index

- `SRSRobo.tex`: Software Requirements Specification.
- `SDDRobo.tex`: Software Design Document.
- `READMEUserManual.tex`: Formal README and user manual.
- `DesignSpecRoboSub.tex`: Design specification with dependencies and Docker package expectations.
- `RoboSubSnapshot.tex`: Snapshot 1 through Snapshot 4 objectives.
- `WorkflowDiagram.tex`: High-level workflow diagram.
- `TestRailReport1_Environment.tex`: Documentation and environment setup report.
- `TestRailReport2_Subsystems.tex`: Subsystem interface validation report.
- `TestRailReport3_Simulation.tex`: Simulation and integration validation report.
- `TestRailReport4_Acceptance.tex`: Final acceptance and handoff validation report.

## Access

RoboSub is a physical vehicle that requires on-site supervised access for hardware testing. This repository provides the documentation package and planning artifacts. A future implementation should use the dependency list in `DesignSpecRoboSub.tex` to build a Docker or ROS 2 Humble development environment for the Jetson Orin Nano, Teensy 4.1, computer vision, controls, and simulation stack.
