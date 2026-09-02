# KAIT-CRONOS

**Language:** [Japanese](README.md) | English

---

KAIT‑CRONOS is a research project led by Prof. Mitsuru Maruyama at the Ultrahigh-speed Network Research Center, [Kanagawa Institute of Technology (KAIT)](https://en.kait.jp/index.html).
The project is part of the [JST CRONOS](Ultra-high-speed In-Network Computing Platform:JPMJCS24N9) program and focuses on building a software-based platform that enables high-speed, low-latency processing of 8K+ media streams in-network computing using SRv6 and DPDK.\
In fiscal year 2025, Visiting Researcher Dr. Yasuhiro Ohara is leading the development of an SRv6 software router, utilizing DPDK as the underlying technology. DPDK achieves high performance by decoupling CPU core resources and NICs from the OS and processing them directly from user space. However, its internal state is difficult to grasp during operation, requiring specialized expertise for program development. Therefore, we have designed and built a new “DPDK-dock development environment” consisting of a Shell that allows interactive control of DPDK thread operations and the DPDK thread execution environment (sdplane), and we were released it as open source software on September 8, 2025. \
We have developed a software router that supports SRv6, an IPv6 based implementation of segment routing, to serve as the core routing component of our platform, and we are now releasing it as customizable open-source software. It is implemented as an application running on sdplane, the already open-sourced DPDK thread execution environment. \
It implements IPv4 and IPv6 packet forwarding functions capable of handling 100Gbps-class traffic, along with a Linux netlink interface, enabling forwarding based on Linux routing information and integration with various dynamic routing daemons. Furthermore, it can be applied to next-generation network control technologies such as service function chaining and traffic engineering, as it supports the basic functions of SRv6.


## 🧭 Research Overview

This research project proposes an architectural framework leveraging in-network computing to facilitate autonomous functional collaboration by seamlessly integrating networks and computational resources. 
This approach allows real-time coordination between the network and computational resources, achieving high-speed and low-latency processing. Additionally, the study introduces a system that shares network status with application and user terminal sides, promoting more streamlined and adaptive network operations.

- Promote standardization, including that of a control plane that facilitates dynamic resource allocation to ensure uninterrupted processing in the event of a failure, using IETF SRv6 End.AN.
  - [SRv6 SFC Architecture with SR-aware Functions](https://datatracker.ietf.org/doc/draft-watal-spring-srv6-sfc-sr-aware-functions/)
- Development of a high-speed SRv6 software router using DPDK.
- By merging the software router section using DPDK and CPU processing and optimizing the data transfer, we will achieve ultra-high-speed and low latency performance of 1 Tbps and less than 1 μs.
- We will facilitate early social implementation through various application demonstration experiments on wide-area testbeds and provide the platform as an OSS.

## Software

- Repository: [**sdplane-oss**](https://github.com/kait-cronos/sdplane-oss)

## Features

  - High-performance packet processing: Zero-copy, user-space packet processing using DPDK
  - Layer 2/3 forwarding: Integrated LPM, and FIB support with SRv6 End functionality
  - Packet generator: Built-in packet generator for testing and benchmarking
  - Network virtualization: TAP interface support and VLAN switching
  - CLI management: Interactive command-line interface for configuration and monitoring
  - Multi-threading: Cooperative thread model with per-core workers

## Research Team

**Principal Investigator:** Prof. Mitsuru Maruyama

**Joint Investigator:** Prof. Yasuhiro Ohara and Prof. Katsuhiro Sebayashi 

**Institution:** [Ultrahigh-speed Network Research Center](https://www.kait.jp/tech_news/tech_20250530.html) *(Japanese only)*, [Kanagawa Institute of Technology (KAIT)](https://en.kait.jp/index.html)

**Contact:** sdplane [at] nwlab.org
