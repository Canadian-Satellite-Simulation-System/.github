# COS3: Canadian Operational Satellite Simulation System

A flexible, easy-to-use satellite mission simulation platform built on NASA's open-source [NOS3](https://github.com/nasa/nos3) framework, developed for the Canadian Space Agency (CSA).

> **Status:** In development. This is an ECSE 458 Capstone Design Project at McGill University (Fall 2026 / Winter 2027).

## Overview

The CSA trains satellite operators and rehearses missions with a simulation tool that is now outdated and difficult to configure. COS3 replaces it with a platform that lets an operator:

- configure and launch a satellite mission through a guided setup wizard
- run basic exercises in a clean, repeatable way
- inject faults to practice contingency response
- feed the simulation with real sensor data (hardware-in-the-loop) so that, in the long term, physical sensors can be verified

COS3 reuses NOS3's flight software, ground software, simulators, and middleware, and adds a cleaner front end, new components, and hardware integration on top.

## Team

| Name | Role |
|---|---|
| Dimitri Christopoulos | Backend Developer |
| Edouard Dupont | Tester and Devops Lead |
| Clara Dupuis | Frontend Developer |
| Kenny-Alexander Joseph | Hardware Integration Lead |
| Lune Letailleur | Project Manager |
| Trevor Piltch | Software Architect |

**Supervisor:** [Dennis Giannacopoulos](https://www.mcgill.ca/ece/dennis-giannacopoulos)

**Course:** ECSE 458 Capstone Design Project, Department of Electrical and Computer Engineering, McGill University

## Acknowledgements

- [NASA NOS3](https://github.com/nasa/nos3) and the NASA Goddard team
- [42 spacecraft simulation](https://github.com/ericstoneking/42)
- The Canadian Space Agency, for the project proposal and guidance

> Parts of this documentation were prepared with AI assistance. All technical content was verified and revised by the team.
