<div align="center">
  <img src="./VIGIL%20Logo.png" alt="VIGIL-IoT logo" width="160" />
  <h1>VIGIL-IoT</h1>
  <p>
    <strong>Vulnerability Intelligence &amp; Guarding for IoT Layers</strong><br />
    Researching security across connected systems, from hardware and firmware to communication, networks, and cyber-physical environments.
  </p>
  <p align="center">
    <a href="https://vigil-iot.vercel.app"><img src="https://img.shields.io/badge/Website-Overview-3A8077?style=flat-square&amp;logo=vercel&amp;logoColor=white" alt="Overview website" /></a>
    <a href="https://github.com/orgs/VIGIL-IoT/repositories"><img src="https://img.shields.io/badge/GitHub-Browse%20repositories-64748B?style=flat-square&amp;logo=github&amp;logoColor=white" alt="Browse repositories" /></a>
  </p>
</div>

---

## About

VIGIL-IoT is an engineering and research initiative focused on security across embedded devices and the Internet of Things. We study how weaknesses in hardware, firmware, communication, applications, and networks can affect a connected system, then explore practical ways to improve its resilience.

## Projects

### SPECTRA-32

An experimental, low-cost ESP32 security testbed for controlled IoT vulnerability and defense research. The current software milestone includes a Python behavior model and a Streamlit console. Hardware validation is planned. SPECTRA-32 explores secure communication, attack and defense mechanisms, and cyber-physical resilience.

<a href="https://github.com/VIGIL-IoT/VIGIL-Spectra-32"><img src="https://img.shields.io/badge/Explore-SPECTRA--32-3A8077?style=flat-square&amp;logo=github&amp;logoColor=white" alt="Explore SPECTRA-32" /></a>

### VIGIL-FUSE

A command-line security analysis module for embedded firmware and configuration. FUSE scans selected files for common security indicators and reports candidate findings with evidence, severity, confidence, and remediation guidance. Optional tools support component inventory, dependency vulnerability matching, and firmware signature identification. FUSE can help select issues for controlled validation with SPECTRA-32.

<a href="https://github.com/VIGIL-IoT/VIGIL-FUSE"><img src="https://img.shields.io/badge/Explore-VIGIL--FUSE-3A8077?style=flat-square&amp;logo=github&amp;logoColor=white" alt="Explore VIGIL-FUSE" /></a>

## Areas of focus

- Embedded devices, hardware trust boundaries, and interfaces
- Firmware integrity, updates, configuration, and dependencies
- IoT identity, authentication, communication protocols, and trust
- Network exposure, visibility, segmentation, and containment
- Evidence-based defenses for resource-constrained systems

## Research approach

**Observe → Analyze → Validate → Harden**

We map system behavior and trust boundaries, examine security assumptions, validate hypotheses through controlled and repeatable experiments, and evaluate defensive changes against evidence.

## Principles

- **Evidence first:** make claims that can be observed and reviewed.
- **Layered thinking:** account for how device, firmware, communication, and network security interact.
- **Resource awareness:** consider memory, compute, bandwidth, and energy constraints.
- **Responsible testing:** use owned devices, simulations, isolated lab networks, or explicitly authorized environments.
- **Transparency:** state assumptions, capabilities, and limitations clearly.

Visit the [VIGIL-IoT overview website](https://vigil-iot.vercel.app) to learn more.
