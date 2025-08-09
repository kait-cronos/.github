# KAIT-CRONOS

*[Japanese](README_ja.md)*

KAIT-CRONOS is a research project led by Prof. Mitsuru Maruyama at the Ultra-Broadband Network Research Center, [Kanagawa Institute of Technology (KAIT)](https://www.kait.jp/). The project is part of the [JST CRONOS](https://www.jst.go.jp/kisoken/cronos/overview/index.html) program and focuses on building a software-based platform that enables high-speed, low-latency processing of 8K+ media streams using in-network computing with SRv6 and DPDK.

## 🧭 Research Overview

This research project proposes an architectural framework leveraging in-network computing to facilitate autonomous functional collaboration by seamlessly integrating networks and computational resources. This approach allows real-time coordination between network and computational resources, achieving high-speed and low-latency processing. Additionally, the study introduces a system that shares network status with application and user terminal sides, promoting more streamlined and adaptive network operations.

### Key Research Goals

- **Standardization**: Promote standardization, including that of a control plane that facilitates dynamic resource allocation to ensure uninterrupted processing in the event of a failure, using IETF SRv6 End.AN
- **Ultra-High Performance**: By merging the software router section using DPDK and CPU processing and optimizing the data transfer, we will achieve ultra-high-speed and low latency performance of **1 Tbps** and less than **1 μs**
- **Open Source Implementation**: We will facilitate early social implementation through various application demonstration experiments on wide-area testbeds and provide the platform as an OSS

## 💻 Software

### `sdplane` *(coming soon)*  
A high-performance open-source software router built on DPDK (Data Plane Development Kit), designed for software-defined networking applications.

**Key Features:**
- **High-Performance Packet Processing**: Leverages DPDK for zero-copy, user-space packet processing
- **Layer 2/3 Forwarding**: Integrated L2 and L3 forwarding with ACL, LPM, and FIB support
- **Packet Generation**: Built-in packet generator for testing and benchmarking
- **Network Virtualization**: TAP interface support and VLAN switching capabilities
- **CLI Management**: Interactive command-line interface for configuration and monitoring
- **Multi-threading**: Cooperative threading model with per-core workers

## 🏛️ Institution

**Ultra-Broadband Network Research Center**  
[Kanagawa Institute of Technology (KAIT)](https://www.kait.jp/)  
Principal Investigator: Prof. Mitsuru Maruyama

## 💰 Funding

This research is supported by the [JST CRONOS](https://www.jst.go.jp/kisoken/cronos/overview/index.html) program (Japan Science and Technology Agency).

<!--
## 📚 Publications

(To be added)

## 📅 Events

(To be added)

## 🔗 Links

(To be added)
-->


