# Hi, I'm Clark Cui

Embedded and industrial systems engineer based in Hefei, Anhui, China.

I build systems from hardware bring-up to application software, algorithms, and verification.

[Portfolio / 个人作品集](https://sailiono.github.io)

[Email / 邮箱](mailto:clarkcui2you@gmail.com): clarkcui2you@gmail.com

我目前在安徽合肥，工作覆盖硬件、STM32/Linux 底层、应用架构、算法、测试平台与工程交付。我关注的不只是“功能做出来”，更重视能否通过 HIL、SIL、测量、回放和自动化测试证明它可靠地工作。

## Engineering profile

| Capability | Public proof |
| --- | --- |
| STM32 and flight-control engineering | [Aerakia Flight Stack](https://github.com/Sailiono/aerakia-flight-stack): drivers, RTOS, application integration, estimation algorithms, HIL, SIL, replay, and digital twin |
| Hardware-system development | [dpiny RTK Base Station](https://github.com/Sailiono/dpiny-rtk-base-station): isolated power, STM32 + GNSS, dual RS-422, firmware, diagnostics, and bench verification |
| AI-assisted engineering workflow | [Liakia](https://github.com/Sailiono/liakia-ai-embedded-workflow): repeatable build → flash → test → diagnose → evidence → handoff, proven on real STM32 hardware through dpiny |
| Linux and industrial vision | [Splicia Vision Platform](https://github.com/Sailiono/splicia-vision-platform): Linux camera pipelines, microscopic vision, multi-axis motion, closed-loop alignment, logging, and replay |
| Open hardware and protocol validation | [SBUS-RS422 Bridge](https://github.com/Sailiono/sbus-rs422-bridge): isolated transparent hardware bridge, browser analyzer, logic-capture analysis, and input/output consistency testing |

## Featured work

### [Aerakia Flight Stack](https://github.com/Sailiono/aerakia-flight-stack)

A sanitized flight-control engineering portfolio showing the full stack on STM32H743: low-level peripherals and sensors, FreeRTOS services, application data flow, attitude-estimation research, HIL/SIL, digital-twin tools, and evidence-backed debugging.

### [dpiny RTK Base Station](https://github.com/Sailiono/dpiny-rtk-base-station) × [Liakia](https://github.com/Sailiono/liakia-ai-embedded-workflow)

Two views of one engineering result. dpiny demonstrates the hardware and firmware system; Liakia extracts the reusable AI-assisted delivery workflow used to build, flash, test, diagnose, document, and hand off that real system.

### [Splicia Vision Platform](https://github.com/Sailiono/splicia-vision-platform)

A privacy-safe case study covering embedded Linux, dual global-shutter camera pipelines, microscopic fiber measurement, semantic multi-axis control, continuous alignment, product-state design, and replayable verification.

### [SBUS-RS422 Bridge](https://github.com/Sailiono/sbus-rs422-bridge)

An open-source hardware-and-software project that turns a small protocol bridge into a complete verification story: schematic, isolation, selectable polarity, live decoding, generic waveform import, consistency analysis, and a planned hardware-versus-MCU benchmark.

## Technology range

```text
hardware / schematic / interfaces
STM32 / C / C++ / FreeRTOS / DMA / USB / Ethernet
Linux / camera pipelines / OpenCV / Python
serial protocols / GNSS / RTCM / SBUS / RS-422
HIL / SIL / digital twin / replay / automated evidence
JavaScript / TypeScript / Shell / PowerShell / engineering automation
```

## How I work

```text
understand → build → measure → diagnose → verify → document → share
```

I use AI to increase engineering throughput, while keeping hardware measurements, reproducible tests, source review, and human judgment as the acceptance boundary.

Most projects are active engineering work. Safety-critical use always requires independent review and validation for the intended environment.
