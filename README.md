# Hi, I'm Clark Cui

Embedded systems builder based in Wuhan, China.

I work across hardware, firmware, test tooling, and engineering automation. I am especially interested in making embedded development more observable and repeatable: understanding what happens on the wire, validating it with real measurements, and preserving enough evidence for someone else to reproduce the result.

我是一名来自武汉的嵌入式系统开发者，关注硬件、固件、测试工具与工程自动化。我喜欢把“设备能够工作”进一步变成“结果能够测量、复现和解释”。

## What I'm building

### [SBUS-RS422 Bridge](https://github.com/Sailiono/sbus-rs422-bridge)

An open-source isolated SBUS-to-RS-422 hardware bridge with a browser-based signal analyzer and reproducible verification workflow. The project covers the schematic, selectable signal polarity, live SBUS decoding, generic logic-capture analysis, and input/output consistency testing.

### [Liakia](https://github.com/Sailiono/liakia-ai-embedded-workflow)

An AI-assisted delivery loop for STM32 teams: build, flash, test, diagnose, collect evidence, and hand off. It keeps engineers in control while making firmware work easier to review and repeat on real or remote hardware.

### [OpenClaw Deploy](https://github.com/Sailiono/openclaw-deploy)

A practical deployment workflow for OpenClaw on Ubuntu and Debian, including dependency setup, local-only proxying, model configuration, bot integration, operational checks, and secret-safe handoff.

## Areas of interest

- Embedded hardware and STM32 firmware
- Serial protocols, signal integrity, and hardware-in-the-loop testing
- Flight-control, navigation, and positioning systems
- AI-assisted engineering workflows with human review
- Open-source tools backed by reproducible measurements

## How I work

```text
build -> measure -> diagnose -> verify -> document -> share
```

I prefer small, understandable systems; real bench evidence over assumptions; and documentation that includes limitations as clearly as successes.

Most repositories are works in progress. Safety-critical use requires independent design review, testing, and validation for the intended environment.
