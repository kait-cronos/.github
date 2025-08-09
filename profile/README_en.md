# KAIT-CRONOS

**Language:** [Japanese](README.md) | English

---

KAIT-CRONOS is a research project that builds a software-based platform for high-speed, low-latency processing of 8K+ media streams using in-network computing with SRv6 and DPDK.

## About the Project

This research develops an architectural framework that seamlessly integrates networks and computational resources, enabling real-time coordination for high-speed and low-latency processing.

**Target Performance:**
- Speed: 1 Tbps
- Latency: Less than 1 μs

## Software

- **sdplane**: A high-performance open-source software router built on DPDK for software-defined networking
  - Repository: [**sdplane-oss**](https://github.com/kait-cronos/sdplane-oss) *(coming soon)*
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

**Funding:** [JST CRONOS](https://www.jst.go.jp/kisoken/cronos/en/overview/index.html) program (Japan Science and Technology Agency)


