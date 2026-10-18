Throughout my undergraduate studies, I have worked on a range of projects in **Real-Time Operating Systems (RTOS), Linux Systems Programming, and Computer Networking**. These projects have helped me develop a strong foundation in operating systems, kernel development, embedded Linux, virtualization, and network infrastructure.

Some of my notable projects and learning experiences are outlined below.

## 1. Linux-Based RTOS for Transferring MEC Server Logs over 5G

Developed a lightweight, real-time Linux system for the Raspberry Pi 4B, based on the Broadcom BCM2711 platform, to serve as a gateway for transmitting Multi-access Edge Computing (MEC) server logs over a 5G network.

- **Custom Embedded Linux Build:** Built a customized Linux distribution using Buildroot and integrated a self-compiled PREEMPT_RT kernel to achieve deterministic, low-latency system performance.
- **Kernel Optimization:** Compiled and deployed the PREEMPT_RT kernel from source, achieving seamless integration with the Buildroot image while reducing memory and storage requirements.
- **5G Connectivity:** Integrated the SIM8200EA-M2 5G HAT, supporting the n78 band, and compiled the required drivers from source to enable modem functionality in the minimal Buildroot environment.
- **Real-Time Performance:** Achieved a maximum measured latency of **28 µs**, compared with **149 µs** on the stock image during cyclic latency testing.
- **Alternative Linux Integration:** Experimented with a customized version of the stock Linux image by removing the graphical interface and unnecessary components. Integrated the custom real-time kernel while retaining package management capabilities, achieving comparable latency performance.

This project provided valuable hands-on experience in embedded Linux development, real-time kernel configuration, device-driver integration, system optimization, and 5G networking. It also demonstrated how a carefully configured Linux system can deliver significantly improved real-time performance on resource-constrained hardware.

- if you want read the detailed [report](https://github.com/josithg/josithg.github.io/blob/v5/report/report.pdf)
## 2. QNX Hypervisor on Raspberry Pi 4 and Raspberry Pi 5

Successfully built and deployed working QNX Hypervisor images for the Raspberry Pi 4B and Raspberry Pi 5, running QNX and Linux guest environments on the same hardware platform.

- **BSP Customization:** Modified the Raspberry Pi 4 and Raspberry Pi 5 Board Support Packages (BSPs) to support the required hypervisor configurations.
- **Hypervisor Integration:** Worked with QNX Software Development Platform (SDP) 8.0 and its BSP components to configure hypervisor guests for generic ARM virtual machines.
- **Boot Image Construction:** Integrated the required Raspberry Pi firmware components, including device tree blobs (DTBs) and ELF binaries, to produce bootable hypervisor images.
- **Display and Console Configuration:** Configured the display and graphics components manually, using a UART serial connection for debugging and system-level interaction.
- **Guest Execution:** Successfully brought up the hypervisor environment with functional QNX and Linux guests on the target hardware.

This project deepened my understanding of hardware virtualization, ARM-based system architecture, board support packages, boot processes, and low-level debugging. It also provided practical experience working with QNX and configuring heterogeneous operating-system environments on embedded platforms.
- if you want to know more about the project refer this repo [qnx_hypervisor](https://github.com/josithg/qnx_hypervisor)
---

These projects reflect my interest in understanding systems from the ground up, from kernel configuration and device drivers to hypervisors and network connectivity. I particularly enjoy working close to the hardware, debugging complex system-level issues, and optimizing software for performance and reliability.

These are just a few highlights of my work. I have worked on several other projects across systems programming, real-time systems, and computer networking that are not covered on this page.
