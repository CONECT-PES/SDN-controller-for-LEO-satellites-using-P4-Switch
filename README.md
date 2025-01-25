# SDN-controller-for-LEO-satellites-using-P4-Switch



![image](https://github.com/user-attachments/assets/417d8901-6ca8-4954-beec-0f7f4805ccee)



## Project Overview
This project aims to develop a novel satellite communication architecture leveraging Software-Defined Networking (SDN) for Low Earth Orbit (LEO) satellites. The solution integrates **GNU Radio** and **Mininet** with **P4 programming** to enhance satellite network traffic control, demonstrating improved Quality of Service (QoS) across different scenarios.

## Key Features
- **SDN Integration**: Efficient satellite traffic management using Mininet.
- **P4 Programming**: Implementation of custom switch architecture for enhanced forwarding capabilities.
- **Simulation and Validation**: Performance validation through three scenarios:
  - With SDN
  - Without SDN
  - SDN with P4 switch
- **Future Scope**: Exploring FPGA deployment for performance improvements.

## Tools and Technologies
- **Mininet**: Network emulation.
- **GNU Radio**: Software-defined radio implementation.
- **Python 3**: Scripting for automation and simulation.
- **P4 Language**: Programming for packet processing and switch customization.
- **Scapy**: Packet crafting and handling.

## Achievements
1. **Phase 1**: Successfully integrated GNU Radio and Mininet.
2. **Phase 2**: Developed the satellite transceiver and validated it through guidance from the paper's author.
3. **Phase 3**: Implemented basic forwarding using P4 and performed TCP throughput analysis with and without load.

## Next Steps
- Perform comparative results analysis to showcase the performance benefits of the P4 switch with SDN.
- Conduct iPerf3 tests for accurate performance measurements.
- Explore FPGA deployment for enhanced efficiency.

## Improvements
- Implement P4 programs on an FPGA for potential performance enhancements.

## Team
- **Project Guide**: Dr. Sireesha B
- **Team Members**: Team 16
