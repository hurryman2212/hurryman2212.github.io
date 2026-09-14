---
layout: default
---

I am a Korean passionate researcher with a strong background in _Operating
System_, _Computer Architecture_ and _Computer Networking_. My current work
focuses on **_userspace system call interception_**, **_inter-VM shared memory
and device sharing_**, **_intra-node network acceleration_** and **_device
simulation_** such as **_Processing-In-Memory device_**. I am currently a Ph.D.
Candidate at
[Computer Systems and Platforms Laboratory](https://csap.snu.ac.kr/), Seoul
National University. Before that, I was at High Performance Computing Lab, Inha
University.

Alongside my research, I develop _user-space libraries_ and _kernel & userspace
drivers_ on Linux platforms, and _device firmwares_ and contribute to
open-source software. My engineering work focuses on transparently improving
software performance through enhanced system software or hardware support
exposed via standard interfaces.

---

## Education

- Ph.D. Candidate in Computer Science and Engineering - _Seoul National
  University_, (present)
- M.S. in Electrical and Computer Engineering - _Inha University_, 2021
- B.S. in Computer Engineering - _Inha University_, 2019

## Publications

1. **Jihong Min**, Bernhard Egger. "HostPIMSim: A High-Productivity Framework
   for Host-Side Processing-in-Memory Simulation," GECON, 2026.
   \[[Source](https://github.com/hurryman2212/hostpimsim-gecon2026)\]
2. **Jihong Min**, Jorn Altmann, Bernhard Egger. "OverlaySys: Easing Development
   Cost for Interposing Systems," GECON, 2026.
   \[[Source](https://github.com/hurryman2212/overlaysys-gecon2026)\]
3. **Jihong Min**, "Inter-VM Network Communication Using Shared Memory with
   User-Mode Access and Its Effectiveness", thesis, 2021.
4. **Jihong Min**, Juhyung Park, Joonseok Park. "Binary-Compatible User-Mode
   Polling-Based Inter-VM Communication Techniques Using Shared Memory," Journal
   of Korean Institute of Information Scientists and Engineers (JOK), vol. 47,
   no. 11, pp. 1015-1020, 2020, Invited Paper.
5. **Jihong Min**, Juhyung Park, Joonseok Park. "A Research on Binary-Compatible
   Data Transmission for Local Inter-VM Network Communication Using Shared
   Memory," Korea Software Congress (KSC), 2019, Selected for the Outstanding
   Paper Award.

---

## Technical Profile

- **Advanced Knowledge** Operating systems; computer networking; embedded
  programming; computer architecture.
- **Languages & Build** C; C++; Python; x86 assembly; CMake; DKMS.
- **Systems Programming** Linux kernel and user-space device drivers; device
  emulation, simulation, and virtualization; multithreading and concurrency;
  async-signal safety and reentrancy; debugging and performance analysis.
- **Networking** Inter-VM/container and localhost communication acceleration; VM
  and container/process (CRIU) live migration; Open vSwitch; network traffic and
  protocol (TCP/IP, USB, Bluetooth) analysis; switching, routing, and hardware
  offloading.
- **Platforms** Linux across desktop, server, embedded, virtualization, and
  container environments.

## Open-source Contributions

1. **Mainline Linux Kernel - AMD Promontory 21 xHCI Hardware Monitoring**.
   _Device driver_
   \[[Source](https://github.com/torvalds/linux/blob/master/drivers/hwmon/prom21-xhci.c)\].
   - Upstreamed Linux hwmon and xHCI PCI glue drivers for the AMD Promontory 21
     chipset temperature sensor.
   - Implemented MMIO access and runtime power management through the Linux
     auxiliary bus without affecting normal USB operation.

2. **OpenWrt Stack for High-Performance Wireless Router**. _Kernel
   network/crypto device drivers & framework_
   \[[Source](https://github.com/hurryman2212/OpenW1700k-test)\].
   - Introduced a dynamic CPU fallback framework for small request block sizes
     and applied it to the EIP93 lookaside crypto engine.
   - Added Linux driver support for the Realtek RTL8261CE 10GbE PHY and Airoha
     AN7581 SOE inline IPsec engine.
   - Debugged and enhanced Airoha packet processing (PPE/IFC TCAM) and the
     MT7996 Wi-Fi chipset.

3. **Airoha Network Processor Unit FDK**. _RISC-V firmware_
   \[[Source](https://github.com/hurryman2212/airoha-npu-fdk)\].
   - Developed a firmware development kit for the Airoha AN7581 8-core Network
     Processor Unit (RISC-V).
   - Reconstructed human-readable source from vendor firmware through
     AI-assisted reverse engineering, exposed firmware components as APIs, and
     developed build tools for firmware customization.

4. **NVIDIA Open GPU Kernel Modules - Hardware Monitoring & Recovery**. _Device
   driver_
   \[[PR](https://github.com/NVIDIA/open-gpu-kernel-modules/pull/1169)\].
   - Implemented Linux hwmon support for temperature and power monitoring and
     fan control.
   - Added automatic GPU recovery through PCIe Function Level Reset (FLR), with
     safe DRM teardown and preserved exported system-memory buffers.

5. **vDS - Virtual DualSense**. _Virtual device driver & user-space
   Bluetooth/USB stack_ \[[Source](https://github.com/hurryman2212/vds)\].
   - Built a virtual USB-to-Bluetooth bridge enabling DualSense's USB-only
     features over a Bluetooth connection.
   - Implemented a user-space daemon and virtual device driver for bidirectional
     Bluetooth HID–USB translation.

---

## Contact

- **GitHub:** [hurryman2212](https://github.com/hurryman2212)
- **Email:** [hurryman2212@gmail.com](mailto:hurryman2212@gmail.com)
