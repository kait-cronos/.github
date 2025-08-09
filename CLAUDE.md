# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is the **KAIT-CRONOS** research project repository, focused on developing a high-performance software-based platform for 8K+ media stream processing using SRv6 and DPDK. The project is led by Prof. Mitsuru Maruyama at the Ultra-Broadband Network Research Center, Kanagawa Institute of Technology (KAIT), as part of the JST CRONOS program.

## Repository Status

**⚠️ Important Note**: This repository currently contains only documentation and project information. The actual codebase for the `sdplane` software router (mentioned in the README) is marked as "coming soon" and has not yet been committed to this repository.

## Repository Structure

The repository is minimal and consists of:
- `README.md` - Main project documentation
- `profile/README.md` - GitHub profile README for the organization

## Key Project Components (Future)

Based on the documentation, the main software component will be:

### `sdplane` - Software Router
A high-performance open-source software router built on DPDK with these planned features:
- High-Performance Packet Processing using DPDK
- Layer 2/3 Forwarding with ACL, LPM, and FIB support
- Built-in packet generator for testing and benchmarking
- Network Virtualization with TAP interface support and VLAN switching
- CLI Management interface
- Multi-threading with cooperative threading model

## Development Status

This repository is in early stages with no source code currently available. When development begins, expect:
- C/C++ codebase (typical for DPDK applications)
- DPDK-based packet processing architecture
- Likely build system using Make or CMake
- Performance testing and benchmarking tools

## Research Context

The project aims to achieve:
- Ultra-high-speed performance (1 Tbps)
- Ultra-low latency (less than 1 μs)  
- In-network computing capabilities
- SRv6 End.AN standardization support
- Integration with wide-area testbeds for demonstration

When source code becomes available, development will likely involve DPDK knowledge, network programming, and high-performance computing techniques.