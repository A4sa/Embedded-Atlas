
<div align="center">

<!-- Replace with your actual banner image once created -->
<!-- <img src="assets/banner.png" alt="Embedded Atlas" width="100%"/> -->

# 🗺️ Embedded Atlas

**A structured roadmap and resource guide for engineers entering embedded systems.**
From first principles to industry-level expertise — hardware, MCU, Linux BSP, and automotive.

<br/>

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Contributions Welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg)](CONTRIBUTING.md)
[![Stars](https://img.shields.io/github/stars/A4sa/Embedded-Atlas?style=social)](https://github.com/A4sa/Embedded-Atlas/stargazers)
[![Last Commit](https://img.shields.io/github/last-commit/A4sa/Embedded-Atlas)](https://github.com/A4sa/Embedded-Atlas/commits/main)

<br/>

[**📖 Docs Website**](https://a4sa.github.io/Embedded-Atlas) &nbsp;·&nbsp;
[**🚀 Start Here**](#-start-here) &nbsp;·&nbsp;
[**🗂️ Domains**](#-domains) &nbsp;·&nbsp;
[**🤝 Contribute**](CONTRIBUTING.md)

</div>

---

## Why Embedded Atlas?

Most resources for embedded engineering are scattered — a YouTube video here, a datasheet there, a Reddit thread someone bookmarked. There is no single place that maps the full territory, explains how domains relate, and tells you what to learn in which order.

**Embedded Atlas is that place.**

It is not a tutorial. It is a **map** — structured, opinionated, and built from real engineering experience across hardware bring-up, Linux BSP, automotive electronics, and Edge AI. Whether you are a CS graduate entering the field, a hobbyist moving into professional work, or an experienced engineer switching domains — this atlas helps you navigate.

> Built by a Lead ARAS Engineer who has worked across BSP, AAOS, OpenCV, and automotive embedded systems at the founding level. The content comes from the field, not from textbooks.

---

## 🗂️ The Four Domains

Embedded systems engineering is not one discipline — it is four overlapping domains, each with its own depth and career path.

```
┌──────────────────────────────────────────────────────────────────────┐
│                       EMBEDDED SYSTEMS                               │
│                                                                      │
│   ┌────────────┐   ┌─────────────┐   ┌───────────┐   ┌──────────┐  │
│   │  Hardware  │   │    MCU /    │   │  Linux    │   │  Auto-   │  │
│   │Electronics │   │  Firmware   │   │   BSP     │   │ motive   │  │
│   │            │   │             │   │           │   │          │  │
│   │ Schematics │   │ Bare metal  │   │ Drivers   │   │ CAN bus  │  │
│   │ PCB layout │   │ RTOS        │   │ Yocto     │   │ AUTOSAR  │  │
│   │ Bring-up   │   │ Peripherals │   │ DTS/DTSI  │   │ ISO26262 │  │
│   └────────────┘   └─────────────┘   └───────────┘   └──────────┘  │
│                                                                      │
│               ── All domains share these foundations ──              │
│            C Programming · Toolchain · Git · Electronics             │
└──────────────────────────────────────────────────────────────────────┘
```

---

## 🚀 Start Here

**New to embedded systems?** Start with foundations. Do not jump into a domain until the fundamentals are solid.

**Already have experience?** Pick your domain directly and use the roadmap to identify gaps.

| Your situation | Where to go |
|---|---|
| New to embedded, never written firmware | [00 · Foundations](00_foundations/) |
| Know C, want to work on hardware | [03 · Hardware](03_hardware/) |
| Know C, want to write firmware | [01 · Microcontroller](01_microcontroller/) |
| Know Linux, want to write drivers | [02 · Linux BSP](02_linux_bsp/) |
| Working in or targeting automotive | [04 · Automotive](04_automotive/) |
| Want cross-domain depth | [05 · Cross-Domain](05_cross_domain/) |
| Looking for project ideas | [Projects](projects/) |
| Preparing for interviews | [Interviews](interviews/) |

---

## 📚 Domains

### [00 · Foundations](00_foundations/)
> Before picking a domain — skills every embedded engineer must have

| Topic | Status | What you learn |
|---|---|---|
| [Electronics Basics](00_foundations/electronics_basics.md) | 🚧 In Progress | Ohm's law → digital logic → signal fundamentals |
| [C for Embedded](00_foundations/c_programming.md) | 🚧 In Progress | Pointers, memory layout, bitwise ops, volatile, const |
| [Toolchain](00_foundations/toolchain.md) | 📋 Planned | GCC, Make, GDB, objdump, linker scripts |
| [Version Control](00_foundations/version_control.md) | 📋 Planned | Git for hardware + software teams |

---

### [01 · Microcontroller / Firmware](01_microcontroller/)
> Embedded software without an OS — the foundation of all embedded work

| Topic | Status | What you learn |
|---|---|---|
| [Roadmap](01_microcontroller/roadmap.md) | 🚧 In Progress | Structured path from beginner to advanced |
| [Bare Metal](01_microcontroller/bare_metal.md) | 📋 Planned | Register access, startup code, linker scripts |
| [RTOS](01_microcontroller/rtos.md) | 📋 Planned | FreeRTOS, Zephyr — tasks, queues, semaphores |
| [Peripherals](01_microcontroller/peripherals.md) | 📋 Planned | UART, SPI, I2C, CAN, USB, ADC/DAC |
| [Debugging](01_microcontroller/debugging.md) | 📋 Planned | JTAG, SWD, OpenOCD, GDB, logic analyzer |
| [Resources](01_microcontroller/resources.md) | 📋 Planned | Books, courses, recommended dev boards |

---

### [02 · Linux BSP](02_linux_bsp/)
> Board Support Package — bringing Linux to custom hardware

| Topic | Status | What you learn |
|---|---|---|
| [Roadmap](02_linux_bsp/roadmap.md) | 🚧 In Progress | Structured path from beginner to advanced |
| [Kernel Basics](02_linux_bsp/kernel_basics.md) | 📋 Planned | Architecture, compilation, Kconfig, menuconfig |
| [Device Drivers](02_linux_bsp/device_drivers.md) | 📋 Planned | Character, platform, I2C, SPI, interrupt drivers |
| [Device Tree](02_linux_bsp/device_tree.md) | 📋 Planned | DTS/DTSI from scratch, bindings, overlays |
| [Yocto](02_linux_bsp/yocto.md) | 📋 Planned | Custom Linux distro for your board |
| [Debugging](02_linux_bsp/debugging.md) | 📋 Planned | kgdb, ftrace, perf, dmesg, serial console |
| [Resources](02_linux_bsp/resources.md) | 📋 Planned | Books, kernel.org docs, community |

---

### [03 · Hardware Electronics](03_hardware/)
> PCB design, board bring-up, and test equipment

| Topic | Status | What you learn |
|---|---|---|
| [Roadmap](03_hardware/roadmap.md) | 📋 Planned | Structured path from beginner to advanced |
| [Schematic Design](03_hardware/schematic.md) | 📋 Planned | Reading and drawing schematics with KiCad |
| [PCB Design](03_hardware/pcb_design.md) | 📋 Planned | Layout rules, stackup, design for manufacturing |
| [Signal Integrity](03_hardware/signal_integrity.md) | 📋 Planned | High-speed design, impedance, EMC basics |
| [Board Bring-Up](03_hardware/bring_up.md) | 📋 Planned | Power sequencing, first boot, systematic debugging |
| [Test Equipment](03_hardware/test_equipment.md) | 📋 Planned | Oscilloscope, logic analyzer, DMM, JTAG probe |
| [Resources](03_hardware/resources.md) | 📋 Planned | Books, courses, simulators, reference designs |

---

### [04 · Automotive Electronics](04_automotive/)
> CAN bus, AUTOSAR, functional safety, Android Automotive

| Topic | Status | What you learn |
|---|---|---|
| [Roadmap](04_automotive/roadmap.md) | 🚧 In Progress | Structured path from beginner to advanced |
| [CAN Bus](04_automotive/can_bus.md) | 🚧 In Progress | CAN, CAN-FD, LIN, FlexRay — protocol to implementation |
| [AUTOSAR](04_automotive/autosar.md) | 📋 Planned | Classic and Adaptive AUTOSAR architecture |
| [Functional Safety](04_automotive/functional_safety.md) | 📋 Planned | ISO 26262, ASIL levels, safety lifecycle |
| [AAOS](04_automotive/aaos.md) | 📋 Planned | Android Automotive OS — HAL, VHAL, integration |
| [ADAS](04_automotive/adas.md) | 📋 Planned | Sensors, perception, safety-critical RTOS |
| [Resources](04_automotive/resources.md) | 📋 Planned | Standards, tools, simulators, community |

---

### [05 · Cross-Domain Skills](05_cross_domain/)
> Depth that every embedded engineer needs regardless of specialization

| Topic | Status | What you learn |
|---|---|---|
| [Communication Protocols](05_cross_domain/protocols.md) | 📋 Planned | UART, SPI, I2C, USB, Ethernet — the full picture |
| [Power Management](05_cross_domain/power_management.md) | 📋 Planned | Low-power design, sleep modes, power rail sequencing |
| [OTA Updates](05_cross_domain/ota_updates.md) | 📋 Planned | Firmware update strategies, rollback, A/B partitions |
| [Embedded Security](05_cross_domain/security.md) | 📋 Planned | Secure boot, TrustZone, HSM, code signing |
| [Testing](05_cross_domain/testing.md) | 📋 Planned | Unit testing, HIL, static analysis, CI for embedded |

---

## 🗺️ Learning Paths

Three common journeys through the atlas — pick the one closest to your situation.

**Path A — Complete Beginner → BSP Engineer**
```
Foundations          (2–3 months)  → Electronics, C, toolchain, git
Microcontroller      (2–3 months)  → Bare metal, RTOS, peripherals
Linux fundamentals   (1–2 months)  → File system, processes, shell
Linux BSP            (6–12 months) → Drivers, DTS, Yocto, debugging
Automotive (optional)(ongoing)     → CAN, AAOS, functional safety
```

**Path B — Software Engineer → Embedded Systems**
```
Electronics basics   (1 month)     → Circuits, signals, power
C for embedded       (1 month)     → Memory, pointers, bitops
MCU + RTOS           (2–3 months)  → Bare metal, FreeRTOS
Domain choice        (6–12 months) → BSP or Automotive
```

**Path C — Hardware Engineer → Full-Stack Embedded**
```
C programming        (1–2 months)  → Embedded C patterns
Bare metal firmware  (2 months)    → Register-level programming
Linux BSP            (6 months)    → Drivers, device tree, Yocto
Cross-domain skills  (ongoing)     → Security, OTA, testing
```

---

## 📊 Content Progress

> Actively being built — content added weekly.

| Domain | Topics | Progress |
|---|---|---|
| 00 · Foundations | 4 | 🟩🟩⬜⬜⬜⬜⬜⬜⬜⬜ 25% |
| 01 · Microcontroller | 6 | 🟩⬜⬜⬜⬜⬜⬜⬜⬜⬜ 10% |
| 02 · Linux BSP | 6 | 🟩⬜⬜⬜⬜⬜⬜⬜⬜⬜ 15% |
| 03 · Hardware | 6 | ⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜ 0% |
| 04 · Automotive | 6 | 🟩🟩⬜⬜⬜⬜⬜⬜⬜⬜ 20% |
| 05 · Cross-Domain | 5 | ⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜ 0% |
| Projects | 3 levels | ⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜ 0% |
| Interviews | 4 domains | ⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜ 0% |

**Status legend:** ✅ Complete &nbsp; 🚧 In Progress &nbsp; 📋 Planned

---

## 🏗️ Repository Structure

```
Embedded-Atlas/
│
├── 00_foundations/          ← start here
│   ├── electronics_basics.md
│   ├── c_programming.md
│   ├── toolchain.md
│   └── version_control.md
│
├── 01_microcontroller/
│   ├── roadmap.md
│   ├── bare_metal.md
│   ├── rtos.md
│   ├── peripherals.md
│   ├── debugging.md
│   └── resources.md
│
├── 02_linux_bsp/
│   ├── roadmap.md
│   ├── kernel_basics.md
│   ├── device_drivers.md
│   ├── device_tree.md
│   ├── yocto.md
│   ├── debugging.md
│   └── resources.md
│
├── 03_hardware/
│   ├── roadmap.md
│   ├── schematic.md
│   ├── pcb_design.md
│   ├── signal_integrity.md
│   ├── bring_up.md
│   ├── test_equipment.md
│   └── resources.md
│
├── 04_automotive/
│   ├── roadmap.md
│   ├── can_bus.md
│   ├── autosar.md
│   ├── functional_safety.md
│   ├── aaos.md
│   ├── adas.md
│   └── resources.md
│
├── 05_cross_domain/
│   ├── protocols.md
│   ├── power_management.md
│   ├── ota_updates.md
│   ├── security.md
│   └── testing.md
│
├── projects/
│   ├── beginner.md
│   ├── intermediate.md
│   └── advanced.md
│
├── interviews/
│   ├── hardware.md
│   ├── mcu.md
│   ├── bsp.md
│   └── automotive.md
│
├── assets/                  ← diagrams, banner, screenshots
├── CONTRIBUTING.md
├── LICENSE
└── README.md
```

---

## 🤝 Contributing

Domain knowledge from the field beats anything written from documentation alone.
If you have experience, a better resource, a missing topic, or a correction — open a PR.

**The one rule:** every entry needs a WHY. A link without context is not documentation.
Explain what it teaches and why it belongs here.

```bash
# Fork → clone → branch
git checkout -b content/your-topic

# Add content, then open a PR against main
```

See [CONTRIBUTING.md](CONTRIBUTING.md) for content style, structure, and the review process.

---

## 👤 Author

**Abdul Sattar** — Lead ARAS Engineer
Founding engineer building India's first Advanced Rider Assistance System for 2-wheelers.
Working across Linux BSP · AAOS · OpenCV · Automotive Embedded Systems.

[![GitHub](https://img.shields.io/badge/GitHub-A4sa-black?logo=github)](https://github.com/A4sa)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Abdul%20Sattar-blue?logo=linkedin)](https://linkedin.com/in/a4sa)
[![Medium](https://img.shields.io/badge/Medium-@abdul__sattar-black?logo=medium)](https://medium.com/@abdul_sattar)
[![Dev.to](https://img.shields.io/badge/Dev.to-@abdul__sattar-black?logo=devdotto)](https://dev.to/abdul_sattar)

---

## 📄 License

MIT — see [LICENSE](LICENSE) for details.
Free to use, share, and build upon.
If this helped you, a ⭐ or a contribution back is appreciated.

---

<div align="center">
<br/>
<sub>Embedded systems is one of the most technically demanding and rewarding fields in engineering.</sub>
<br/>
<sub>This atlas exists to make the path clearer.</sub>
<br/><br/>
</div>
