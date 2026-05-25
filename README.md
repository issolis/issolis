# Hi, I'm Isaac

### From Assembly to Cloud — Systems, Backend and Embedded Linux Developer

Computer Engineering student. I work across the full stack of a computing system: hardware description and assembly at the bottom, embedded Linux and systems software in the middle, and APIs, databases and cloud deployment at the top. I am most interested in projects where these layers have to talk to each other.

---

## What I work on

- Software development in C, C++, Java, Python and JavaScript
- Backend development with Node.js, Express and NestJS
- Database design and management with SQL, PostgreSQL and Microsoft SQL Server
- Cloud services on Azure, AWS and Render
- Programming in x86 and ARM Assembly
- Embedded Linux development using the Yocto Project
- Build automation with Makefiles and Bash scripting
- Hardware description in SystemVerilog
- End-to-end integration from hardware up to web interfaces

---

## Languages and tools

![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Java](https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=java&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white)
![Assembly](https://img.shields.io/badge/x86-525252?style=for-the-badge&logo=asm&logoColor=white)
![Bash](https://img.shields.io/badge/Shell_Scripting-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white)
![Makefile](https://img.shields.io/badge/Makefile-0769AD?style=for-the-badge&logo=cmake&logoColor=white)
![SystemVerilog](https://img.shields.io/badge/SystemVerilog-00979D?style=for-the-badge&logo=verilog&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![SQL Server](https://img.shields.io/badge/Microsoft_SQL_Server-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white)
![Azure](https://img.shields.io/badge/Microsoft_Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)
![Render](https://img.shields.io/badge/Render-46E3B7?style=for-the-badge&logo=render&logoColor=black)
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

---

## Featured projects

### [FedSol — Federated Learning Framework](https://github.com/issolis/FedSol)
Hybrid C++/Python framework for federated learning, built around a client/server architecture where every component (model, dataset, training, evaluation, reporting) is driven by JSON configuration.

The C++ side handles the networking layer, the federation protocol, the JSON-based configuration management and the orchestration of training rounds across clients. The Python side performs the actual machine learning work through modular components for model building, training, dataset handling, loss functions, evaluation and metric reporting. Configurations select the model architecture and the task at runtime, and the framework supports object detection workloads such as YOLO in addition to classification.

The project covers end-to-end concerns of a distributed training system: a binary protocol for transferring model weights between server and clients, weight validation against the declared architecture, per-run statistics and reports, and a clean separation between transport, configuration and training logic.

### [Embedded Vehicle — Yocto-Based Remote Control System](https://github.com/kronk99/Embedded_vehicle) (collaboration)
Custom embedded Linux platform for a remote-controlled vehicle, built from scratch. A tailored Linux image was produced with the Yocto Project for hardware control on Raspberry Pi. The system includes modular motor control logic, GPIO abstraction, REST APIs in Flask, live camera streaming, ultrasonic sensor monitoring and systemd autostart services, all exposed through a web interface for real-time control of the physical vehicle. It exercises embedded Linux customization, hardware-software integration and full-stack system design.

### [Secure Surgery System — Backend](https://github.com/gabrielwolfw/secure_surgery_system) (collaboration)
Hospital platform for surgery scheduling and management with a security-first design. I was fully responsible for the backend: a RESTful API built with Node.js and Express on top of PostgreSQL, including the full database schema and relational modeling for patients, staff, procedures and operating rooms. Authentication and authorization are handled with JWT and role-based access control across the different user types. The PostgreSQL database is deployed as a managed instance on Render, which lets the backend run against a live cloud-hosted database during development and demos.

### [Interconnect Simulator](https://github.com/issolis/InterconnectSimulator)
C++ simulation of a distributed system interconnect modeling communication and data flow between nodes.

### [MusicTree](https://github.com/AlbertVega/MusicTree) (collaboration)
Backend built with Node.js and NestJS, handling APIs and data management.

### [GranTrackx86](https://github.com/issolis/GranTrackx86)
Racing game written entirely in x86 Assembly, with direct memory and graphics control.

### [NPU_MATRIX](https://github.com/issolis/NPU_MATRIX)
Basic Neural Processing Unit implemented on FPGA in SystemVerilog.

### [TxtProcessing-ARM](https://github.com/issolis/TxtProcessing-ARM)
Text processing system in ARM Assembly that generates word histograms.

### [PacCEMan](https://github.com/issolis/PacCEMan)
Hybrid C and Java client-server game with A* pathfinding and optimized data structures.

### [API Hospitec](https://github.com/issolis/api-hospitec)
RESTful API built with NestJS, deployed with a cloud-hosted database on AWS.

### [Eagle-Defender](https://github.com/kunZhen/Eagle-Defender) (collaboration)
Large-scale Python game project focused on core mechanics and system logic.

### [Python-Portfolio](https://github.com/issolis/Python-Portfolio)
Collection of structured Python problem-solving implementations.

---

## GitHub stats

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=issolis&layout=compact&theme=radical)

---

## Contact

Email: issolis@estudiantec.cr
