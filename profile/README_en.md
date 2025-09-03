# KAIT-CRONOS

**Language:** [Japanese](README.md) | English

---

KAIT‑CRONOS is a research project led by Prof. Mitsuru Maruyama at the Ultrahigh-speed Network Research Center, [Kanagawa Institute of Technology (KAIT)](https://en.kait.jp/index.html).
The project is part of the [JST CRONOS](Ultra-high-speed In-Network Computing Platform:JPMJCS24N9) program and focuses on building a software-based platform that enables high-speed, low-latency processing of 8K+ media streams in-network computing using SRv6 and DPDK.

## 🧭 Research Overview

This research project proposes an architectural framework leveraging in-network computing to facilitate autonomous functional collaboration by seamlessly integrating networks and computational resources. 
This approach allows real-time coordination between the network and computational resources, achieving high-speed and low-latency processing. Additionally, the study introduces a system that shares network status with application and user terminal sides, promoting more streamlined and adaptive network operations.

- Promote standardization, including that of a control plane that facilitates dynamic resource allocation to ensure uninterrupted processing in the event of a failure, using IETF SRv6 End.AN.
- By merging the software router section using DPDK and CPU processing and optimizing the data transfer, we will achieve ultra-high-speed and low latency performance of 1 Tbps and less than 1 μs.
- We will facilitate early social implementation through various application demonstration experiments on wide-area testbeds and provide the platform as an OSS.

## Software

- **sdplane**: DPDK-dock Development Environment for software-defined networking
  - Repository: [**sdplane-oss**](https://github.com/kait-cronos/sdplane-oss) 
  - Features:
    - High-performance packet processing with DPDK
    - Layer 2/3 forwarding with ACL, LPM, and FIB support  
    - Built-in packet generator for testing
    - Network virtualization with TAP interface and VLAN switching
    - CLI management interface
    - Multi-threading with per-core workers

## Research Team

**Principal Investigator:** Prof. Mitsuru Maruyama

**Institution:** [Ultra-Broadband Network Research Center](https://www.kait.jp/tech_news/tech_20250530.html) *(Japanese only)*, [Kanagawa Institute of Technology (KAIT)](https://en.kait.jp/index.html)

**Funding:** [JST CRONOS](https://www.jst.go.jp/kisoken/cronos/en/overview/index.html) Program (Japan Science and Technology Agency)


