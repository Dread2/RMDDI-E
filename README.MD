# CTS RMDDI-E™ Software

CTS RMDDI-E™ (Realtek Modern Device Driver Initiative: Ethernet) is an open-source stack, composed primarily of Linux kernel driver software, designed for Realtek Ethernet device support. RMDDI-E™ consists of a collection of drivers, patches, and development tools, written in C and Rust, that enable Realtek Ethernet devices including legacy, rare, and undocumented variants to perform optimally on modern Linux systems.

With RMDDI-E™, you can tailor Ethernet driver support to your specific needs. The platform enables development, collaboration, testing, and deployment of networking applications within a free, open-source, integrated, and maintainable software ecosystem. RMDDI-E™ is especially well-suited for embedded Linux, legacy or unstable hardware, and devices without official or ongoing driver support.

RMDDI-E™ is powered by CTS's [Ethernet Device Driver Interface for Portability (EDDIP)](https://github.com/RMDDI/EDDIP), an open-source software written in C and Rust. EDDIP enables developers to create portable, modular drivers that support a wide range of Realtek Ethernet devices, from common consumer NICs to legacy, rare, and undocumented variants. By abstracting hardware specifics into a unified API, EDDIP™ allows RMDDI-E™ drivers to maintain high performance, stability, and maintainability across Linux kernel versions.

RMDDI-E™ supports Linux kernel programming and includes all necessary drivers, patches, and utilities to ensure reliable operation. It contributes improvements to in-tree kernel drivers, providing enhanced performance, quality, and stability while maintaining compatibility with ongoing Linux kernel development. Core driver functionality is separated from device-specific modules, allowing seamless support for legacy, rare, and undocumented Realtek variants without destabilizing the kernel. Each module implements standardized interfaces for PHY, MAC, and DMA operations, enabling portable and maintainable driver code across multiple kernel versions. RMDDI-E™ also incorporates an automated benchmarking and profiling system, allowing developers to measure throughput, latency, and stability on any supported device and automatically generate optimized module parameters for improved performance and reliability.

> [!IMPORTANT]
> Kernel development and testing for RMDDI-E™ is performed on the latest Gentoo release `gentoo-sources` kernel, ensuring compatibility with modern kernel features and long-term maintainability.

## Getting and Building RMDDI-E™ from Source

Please refer to the repository for instructions on compiling and installing RMDDI-E™ drivers on supported Linux distributions.

## RMDDI-E™ Documentation

This repository contains source code, patches, and documentation including changelogs and development notes. The `/docs` folder has all current documentation. The `develop` branch contains the latest updates and upcoming improvements.

The RMDDI-E™ documentation homepage is [www.julianeatong.com/public/initiatives/linux/devices/ethernet](https://www.julianeatong.com/public/initiatives/linux/devices/ethernet).

For information on how to contribute to the RMDDI-E™ documentation, see [Contributing to RMDDI-E™](https://www.julianeatong.com/public/initiatives/linux/devices/ethernet/contribute).

## Older RMDDI-E™ Releases

For release information for older RMDDI-E™ versions, refer to the `/releases` folder of this repository.
