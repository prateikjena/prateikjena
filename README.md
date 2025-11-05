# Prateek Jena

**Embedded Software Engineer | Firmware | RTOS | Linux Systems**

---

## About

I work on software that interacts directly with hardware: bootloaders, device drivers, schedulers, and systems that can’t afford to crash.  
Currently part of the **Ciena Optical** platform team, focusing on board bring-up, communication interfaces, and system reliability.

Most of my work starts long before user-space exists, somewhere between reset vectors and linker scripts.

---

## Technical Focus

- **Firmware and Drivers**
  - Peripheral interfaces: SPI, I²C, UART, GPIO, 1-Wire
  - Interrupt handling, DMA-driven transfers, timing analysis
  - Device drivers for FPGA-based modules and custom boards

- **RTOS and Bare-Metal Systems**
  - FreeRTOS, VxWorks, and experimental schedulers
  - Task switching, IPC mechanisms, timers, and tick configuration
  - Memory management on constrained MCUs and ISR latency reduction

- **Bootloaders and Firmware Update**
  - STM32 bootloader with UART/SPI update capability
  - Flash mapping, integrity checks, and handoff to application
  - Experimenting with fail-safe update and recovery paths

- **Linux and System Integration**
  - Yocto build customization for ARM targets  
  - Device tree configuration, initramfs tuning, kernel module builds  
  - Cross-compilation workflows and rootfs optimization

---

## Current Projects

| Project | Description |
|----------|--------------|
| **stm32-bootloader** | Custom bootloader supporting firmware updates over UART with CRC validation |
| **mini-rtos** | Lightweight scheduler implementing preemption, round-robin, and message passing |
| **emmc-layout** | Exploring eMMC boot stages, flash partitioning, and address remapping |
| **qemu-lab** | Virtual ARM environment using QEMU + GDB for debugging RTOS internals |

---

## Toolchain & Workflow

- **Languages:** C, C++, Bash, Makefile  
- **MCUs:** STM32 (F4/F7), ARM Cortex-M  
- **Debugging:** GDB, OpenOCD, ST-Link, occasional `printf()` rescue  
- **Build Systems:** GNU Make, CMake, Yocto  
- **Version Control:** Git, Gerrit  
- **Analysis:** objdump, readelf, map inspection, linker script tuning  
- **Environment:** Ubuntu (WSL / native), macOS for cross-builds  

Somewhere in flash memory, around `0x08000000`, there’s always a version that finally works.

---

## Interests

- Designing compact, deterministic RTOS kernels  
- Understanding how context switches actually propagate through stacks  
- Building robust firmware update flows with rollback and validation  
- Using QEMU for system-level testing and fault injection  
- Low-level debugging with memory dumps and peripheral register tracing  

---

## Contact

- GitHub: [github.com/prateikjena](https://github.com/prateikjena)  
- Email: pratik.mcs20.du@gmail.com
- LinkedIn: [Prateek Jena](https://www.linkedin.com/in/prateek-jena/)

---

> *If it boots, that’s progress. If it jumps to application, that’s success.*
