# Marcello Ziotti

## Personal Information & Contacts

**Name** Marcello Ziotti

**Birth Date** December 16th, 1990

**Birth Place** Ferrara, ITALY

**Nationality** Italian

**LinkedIn** <https://www.linkedin.com/in/marcelloziotti>

**Email** [marcello.ziotti@gmail.com](mailto:marcello.ziotti@gmail.com)

## Work

### Intel Corporation - Ferrara (Italy) - (Apr 2022, current)

#### System Software and Simulation Modeling Engineer in Virtual Platforms Simulator

Platform level integration, test expert.

CMake migration across multiple teams.

Unit test framework for the whole org.

Pre-commit code coverage check integrated in CI.

### Intel Corporation - Munich (Germany) - (Jul 2018, Apr 2022)

#### Simulation and Modeling Engineer - SystemC and Simics Simulation

I joined Intel as part of a highly experienced team focused on the development and simulation of the Audio IP model for the Alderlake and Meteorlake SoC platforms. Initially starting with smaller tasks and bug fixes, my deep knowledge of SystemC allowed me to quickly take on more critical responsibilities. I was tasked with extending the Audio IP model by integrating serial interfaces like I2C, SPI, and I3C, collaborating closely with IP architects who used Simics as a primary validation tool for their specifications. This led to the seamless integration of these interfaces into the simulation environment.

I also spearheaded the migration of the Audio IP build system from Make to CMake, significantly improving efficiency. This transition, integrated into the Continuous Integration (CI) pipeline, resulted in a 70% speedup in build times and increased the team's overall productivity.

My second major task involved leading the update of the Intel Sideband SystemC library to align with new architecture specifications. This cross-team project required collaboration with the Simics Simulator team to integrate the updated Sideband interface model into the core Simics libraries. The successful integration not only enhanced the Audio IP model but also benefited all SystemC-based models used within Simics.

In parallel, I took ownership of wrapping the Camera IP (developed by the core IP team) into a SystemC Simics model for the Meteorlake SoC. This involved transforming a plain C++ model into a SystemC model with key interfaces such as IOSF PCIe and Sideband, ensuring seamless integration into the simulator. Collaboration with the core IP team was crucial in ensuring the accuracy of the final model. Both the Audio and Camera IPs were deployed with separate CI jobs for efficient continuous integration, ensuring reliability before integration into the larger SoC platform.

As the Lunarlake SoC project began, I continued overseeing the Audio and Camera IPs and was given the opportunity to work on a groundbreaking new feature: Total Storage Encryption (TSE), based on the AES-256b cryptographic algorithm. This was my first project using Device Modeling Language (DML) instead of SystemC, expanding my skillset and allowing me to adopt Test Driven Development (TDD) from the start. The feature was rigorously unit tested and validated, with the BIOS team playing a key role in its end-to-end validation. A critical validation step was creating a UEFI application to test both UEFI behavior and the hardware in Simics, ensuring robust functionality. Once tested at the OS level using Microsoft Windows, most use-cases passed quickly, showcasing the feature’s reliability and performance.

A key milestone was our collaboration with Microsoft, using Simics for OS-level validation. The Simics model was able to detect and fix five important bugs in the Windows OS prior to public release. This collaboration was invaluable and solidified our relationship with Microsoft, as they continued to rely on Simics for future SoC and OS releases.

In addition to my core responsibilities, I initiated the Software Continuous Integration (SWCI) project, which aimed to automate the integration and testing of BIOS/FW components alongside the SoC build. This mechanism allowed for rapid identification of failures in firmware components, ensuring that any issues were addressed early in the process. While the initiative proved successful for BIOS integration and helped streamline the process, its complexity required cross-team coordination. The SWCI initiative continued to evolve and was carried forward in subsequent SoC projects, such as Pantherlake.

### Intel Corporation - Munich (Germany) - (Feb 2018, Jul 2018)

#### Design Verification Engineer

Before transitioning to my work on Simics, I contributed to the cellular 5G chip design verification efforts, focusing on SystemVerilog and the UVM (Universal Verification Methodology) framework. This role involved both behavioral and performance/power validation, ensuring the chip met key design and functionality requirements.

One of my primary tasks was the DMA backdoor access implementation, which allowed for efficient communication and validation of internal chip components. This was my first exposure to RF/5G chip validation, where I gained foundational experience in both system-level verification and performance/power estimation, contributing to the overall design validation process.

## Education

### Pre-University Studies

#### Scientific Certificate - Italian Secondary School Diploma

#### Bachelor Degree in Electrical Engineering at University of Ferrara (Italy)

##### Thesis: Design and development of an RTOS-based driver for a Wi-Fi gateway

**Advisor** - Prof. Massimiliano Ruggeri

**Abstract** - The main goal of the thesis project is a cable
replacement in an embedded system through the integration of an
external wireless module. The chosen Microchip ZG2100M Wi-Fi
module does not incorporate any TCP/IP stack leaving an extra
degree of freedom to the developer to customize the functionality
according to the application requirements. The main target board
hosts an ARM-based microprocessor (STM32F407ZGT6) and the
communication with the wireless module relies on a SPI bus. The
application leans on ChibiOS, a compact and efficient open-
source real-time operating system and the development
environment consists of Eclipse CDT, GDB (Gnu Debugger) e
OpenOCD (GDB server on JTAG). The application starts with a
network scan with a subsequently connection to the desired SSID
which allows the exchange of packets over the Wi-Fi protocol.

#### MSc Degree (2nd level Degree) in Electrical and Telecommunication Engineering at University of Ferrara (Italy)

##### Thesis: NoC Spatial-temporal partitioning technology for application isolation in many-core systems

**Advisor** - Prof. Davide Bertozzi

**Abstract** - With tens or even hundreds of compute cores on a
single processor, many-core platforms provide enough
computational performance to host several applications, while
their low energy consumption makes them well-suited to serve as
programmable accelerators in the high-performance embedded
computing domain. The consolidation of several types of
applications with different criticality levels on the same hardware
platform raises severe practical issues, ranging from system
composability challenges for easier verification to performance
predictability and security concerns. The goal of this thesis is to
propose an innovative architecture with built-in hardware support
for efficient resource sharing between a multi-program workload.
The idea consists of synergistically exploiting space-division
multiplexing and time-division multiplexing to trade performance
for isolation. At the same time, the proposed architecture performs
positively in terms of minimizing the non-uniform memory access
effects. Goal of the thesis is to develop a SystemC-based platform
capable of validating the concept with high level of accuracy, and
of performing basic functional tests, as well as verifying the
engineering trade-offs.

#### Visiting Researcher at National University of Singapore

##### Thesis: Many-core architecture design for LTE base station

**Advisors** - Davide Bertozzi & Tulika Mitra

**Abstract** - The objective of this project is to design a real-time,
high-throughput, low-power base station for future 5G wireless
baseband processing using Software Defined Radio (SDR)
technology. In particular, the project is focused on many-core
architecture design for high-throughput processing, real-time
operating systems (RTOS) design to fully leverage the underlying
architecture, and an end-to-end performance evaluation with
realistic 5G applications and their corresponding network
traffic.The main challenge in 5G wireless baseband processing is
the 10x increase in throughput and 10 fold reductions in latency.
The physical layer processing is the most computationally
demanding component in the base station protocol stack.
Traditionally, the physical layer has been implemented using
customized fixed-function hardware accelerator and DSP (digital
signal processing) cores. However, these designs are inflexible in
the face of updates in the standard and supporting multiple
standards as required by SDR. Software-programmable
processors can offer easy migration path. However, current many-
core architectures (both commercial and academic) are far from
achieving 5G throughput. The goal of this project is to design fully-
programmable, power-efficient many-core architecture for real-
time, high-throughput processing of the physical layer in a base
station.
Collaboration between University of Ferrara (Prof. Davide
Bertozzi) and School of Computing at National University of
Singapore (<http://www.comp.nus.edu.sg/>)

## University Projects

### Design of a power amplifier for WLAN 802.11B applications

The project focus was to assess all the specifications required by
the IEEE 802.11b standard concerning power, gain and spectral
density. To achieve the results, I relied on AWR Microwave Office
simulation tool.

### FPGA Flash Programming

The aim of the project was a simple implementation of a LPF filter
for the Altera StratixII EP2S60 FPGA with Matlab and Altera
Simulink libraries. The main achievement was to flash the
bitstream of the application in the flash memory of the board,
relying on Quartus II tool.

### Firewall implementation and cryptography

The main scope of the project was the implementation of flow
control applications, networking rules with IP-tables, routing
restrictions and development of cypher protocols with Python.

### Peer-to-peer protocols

The project consisted of the Python development of peer-to-peer
protocols like Kazaa, Gnutella, Napster and BitTorrent.

### Orthogonal Frequency-Division Multiplexing Matlab simulation

The purpose of the project was implementing a real scenario with
a base station and random number of users that want to access it,
with fairness algorithm for subcarriers’ allocation.

### Mixed-signal heart-rate monitor implementation

VHDL-based design of mixed-signal system to monitor the activity
of internal registers through I2C, DAC converter and oscilloscope.
The target system consisted of of Digilent Basys3 FPGA, Texas
Instrument ASLKPRO Board and Max 30100 heart-rate module.

### SystemC modelling of Network On-Chip router’s internal architecture

This was a course project for the course "Architecture of Digital
Integrated Systems", aimed at learning the fundamentals of
SystemC programming. Hardware modelling with SystemC
represents one third of the total course content (prof. Davide
Bertozzi). The project goal was the RTL-equivalent SystemC
implementation of the internal blocks of a 5x5 router, consisting of:
input buffers, arbiters, routing logics, crossbar and output buffers.
Finally, a deep exploration of several arbitration policies and the
evaluation of the whole structure through synthetic traffic pattern
generators were provided.

## Skills

### Languages

**Italian** (native speaker)

**English** (fluent)

**German** (good)

**Spanish** (basic)

### Programming Languages

- Python
- DML
- SystemC
- C
- C++
- Bash
- Csh
- Make
- CMake
- Java
- VHDL
- Verilog
- Assembly (ASM)
- HTML
- HTML5
- CSS
- XML

### Tools

- Gtkwave
- iWork Suite (Pages, Numbers, Keynote)
- LibreOffice Suite (Writer, Calc, Impress, Draw, Charts, Math)
- Microsoft Office Suite (Word, Excel, PowerPoint, Outlook)
- MatLAB with Simulink
- Octave
- GNU Debugger (GDB)
- OpenOCD GDB Server
- Quartus II
- Synopsys Design & IC Compiler
- Xilinx SDK - Vivado

### Simulators

- Simics
- VirtualSoC
- MPARM
