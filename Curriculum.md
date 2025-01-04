# Marcello Ziotti

## Personal Information & Contacts

**Name** Marcello Ziotti

**Birth Date** December 16th, 1990

**Birth Place** Ferrara, ITALY

**Nationality** Italian

**LinkedIn** <https://www.linkedin.com/in/marcelloziotti>

**Email** [marcello.ziotti@gmail.com](mailto:marcello.ziotti@gmail.com)

## Work

### Intel Corporation - Ferrara (Italy) - (Apr 2022, Present)

#### Simulation and Modeling Engineer - SystemC and Simics Simulation - Technical Lead

Building on my prior experience with single-IP simulation and integration, I was entrusted with my first SoC-level assignment, a role that significantly expanded my responsibilities and scope. SoC-level tasks are particularly challenging because they involve system-wide changes that impact the interconnects between IPs and the overall platform functionality. My initial project was to overhaul the Sideband network to enable communication between IPs spanning multiple dies and domains. This complex undertaking required meticulous validation, especially for multicast messages, which were prone to subtle issues. Utilizing smoke platform initialization tests, I identified and resolved critical challenges, ensuring a robust and reliable communication framework. Once the Sideband network was operational, I played a key role as an interconnect expert during the platform’s first BIOS UEFI shell boot.

As part of the platform integration team, I also tackled broader challenges affecting the entire Simics SoC ecosystem. One of my most impactful initiatives was the modernization of the build system. The existing build process relied on Make, which was both time-consuming and inefficient. By leading the transition to CMake with a Ninja generator, I reduced build times from 50 minutes to just 15 minutes — a 70% improvement. This was a collaborative effort requiring alignment across all IP teams contributing to the SoC, but the outcome transformed productivity for developers and dramatically accelerated CI pipelines.

Another significant contribution was addressing inefficiencies in the testing strategy for the Simics SoC platform. The traditional reliance on system-level tests, which required running firmware, software, and the operating system, was not sustainable for detecting issues early in development. To remedy this, I designed and implemented a unit test framework tailored for individual IP teams. This framework made it simple to create initialization tests and enabled more granular validation at the IP level before integration into the platform. To ensure widespread adoption, I worked closely with technical leads to streamline the framework and make IP-level testing mandatory for integration.

Recognizing the importance of quality assurance, I extended this effort by introducing a code coverage monitoring system integrated with GitHub workflows. This system automatically checks that any proposed changes maintain or improve test coverage, blocking commits that could degrade the reliability of an IP model. This mechanism has pushed the organization toward adopting Test-Driven Development (TDD), driving a cultural shift that prioritizes robust, tested code.

These initiatives, combined with my foundational work on platform integration and cross-team collaboration, culminated in my promotion to Technical Lead. In this role, I continue to oversee platform-wide projects, mentor colleagues, and champion innovative practices that enhance the quality, efficiency, and reliability of Intel’s SoC simulation platforms.

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

### Visiting Researcher at National University of Singapore (2017)

**Thesis:** Many-core Architecture Design for LTE Base Station

**Advisors:** Prof. Davide Bertozzi & Prof. Tulika Mitra

Designed a programmable many-core architecture for high-throughput, low-latency LTE base stations. Focused on real-time physical layer processing using Software Defined Radio (SDR) technology. The project addressed the challenges of 10x throughput increases and latency reductions in 5G wireless standards, integrating RTOS design and realistic 5G applications for end-to-end performance evaluation.

### MSc in Electrical and Telecommunication Engineering, University of Ferrara (Italy) (2016)

**Thesis:** NoC Spatial-Temporal Partitioning for Application Isolation in Many-Core Systems

**Advisor:** Prof. Davide Bertozzi

Proposed an innovative Network-on-Chip (NoC) architecture combining spatial and temporal partitioning to balance performance and isolation in many-core platforms. Developed a SystemC-based simulation to validate the concept, performing functional tests and analyzing engineering trade-offs like reduced memory access delays.

### BSc in Electrical Engineering, University of Ferrara (Italy) (2013)

**Thesis:** RTOS-Based Driver for a Wi-Fi Gateway

**Advisor:** Prof. Massimiliano Ruggeri

Developed a driver integrating a Microchip ZG2100M Wi-Fi module with an ARM-based STM32F407ZGT6 microcontroller. The project featured ChibiOS RTOS, SPI communication, and tools like Eclipse CDT, GDB, and OpenOCD. Key outcomes included network scanning, SSID connection, and Wi-Fi packet exchange.

### University Projects

- **Many-Core Network-On-Chip Router (SystemC)**: Modeled a 5x5 NoC router with SystemC, including buffers, arbiters, and routing logic, exploring arbitration policies and synthetic traffic patterns.
- **Mixed-Signal Heart-Rate Monitor (VHDL)**: Designed a heart-rate monitor with FPGA (Basys3), I2C, and DAC converters integrated with Texas Instruments ASLKPRO Board.
- **Orthogonal Frequency-Division Multiplexing (Matlab)**: Simulated a base station handling random user access, applying fairness algorithms for subcarrier allocation.
- **Firewall Implementation (Python)**: Developed flow control, IP routing, and cryptographic protocols.
- **FPGA Flash Programming (Intel Altera Quartus)**: Implemented an LPF filter on Altera StratixII EP2S60 FPGA and flashed the bitstream to the board.
- **Power Amplifier for WLAN 802.11B (AWR Microwave Office)**: Designed a power amplifier meeting IEEE 802.11b specifications using AWR Microwave Office.

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
