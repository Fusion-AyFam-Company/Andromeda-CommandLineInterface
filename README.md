# PROJECT:
Name: Andromeda CommandLine Interface

"Per Ardua ad Astra" — Through Hardship to the Stars.

Current Build: v1.95745 (Codename: KANGAROO)

Platform: ARM64 Ubuntu Devices.

# SYSTEM OVERVIEW
**Andromeda-CLI is not just a shell script;** it is a Sub-System Environment (**SSE**) engineered for Ubuntu ARM64 and more devices. (releasing soon.) Such as NanoPi R6S. While standard Bash is a general-purpose tool, Andromeda is a precision instrument for hardware developers, security enthusiasts, and systems engineers.

It bypasses the clutter of standard Linux terminals to provide a high-telemetry, low-latency interface that talks directly to the SoC (System on Chip) thermal sensors and USB bus controllers.

# HARDWARE REQUIREMENTS
To run the Kangaroo Build at peak efficiency, the following hardware specs are mandated:

| Component | Technical Specification | Protocol / Interface | Performance Tier |
| :--- | :--- | :--- | :--- |
| **CPU (SoC)** | Rockchip RK3399 (ARMv8) | 64-bit Hexa-core (Dual A72 + Quad A53) | 🚀 **HIGH** |
| **GPU** | Mali-T860 MP4 | OpenGLES 1.1/2.0/3.0 / OpenCL | 🎨 **MID** |
| **RAM (LPDDR4)** | 4GB Dual-Channel | 1600MHz High-Speed Data Rate | 🧠 **STABLE** |
| **Storage (OS)** | MicroSD / eMMC 5.1 | SDIO 3.0 / HS400 High-Speed | ⚡ **BURST** |
| **Storage (Key)** | UEFI NTFS Partition | USB 3.0 SuperSpeed (5Gbps) | 🔒 **SECURE** |
| **Thermal Bus** | TSADCMonitor | `/sys/class/thermal/` Hardware Hook | 🌡️ **CRITICAL** |
| **Serial Bus** | CH340 / CP2102 | UART / TTL (5V/3.3V Logic) | 🛠️ **DEV-ACTIVE** |
| **Ethernet** | RTL8211E | 10/100/1000Mbps Base-T | 🌐 **GIGABIT** |

# DEEP-STRIKE INSTALLATION
The Andromeda-CLI is distributed as a Debian Binary Archive (.deb). This ensures that all symlinks, permissions, and dependencies are handled by the system's native package manager.

**1. The Standard Deployment**
If you have the .deb file locally on your device:

`sudo apt update && sudo apt install ./andromeda-cli_1.0.0_ubuntu_arm64.deb`

**2. Remote Deployment (wget)**
If you are installing on a fresh node:
`wget https://github.com/Fusion-AyFam-Company/[filenotfound-prerelease]`


