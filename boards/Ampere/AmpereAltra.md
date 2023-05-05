  # Ampere:registered: Altra:registered:

Product page: [Ampere Altra](https://amperecomputing.com/processors/ampere-altra); [Data Sheet](https://solutions-portal-cms-prod-bucket.s3.amazonaws.com/Altra_Rev_A1_DS_v1_30_20220728_8170025756.pdf)

Arm IP:
- [Neoverse](https://github.com/ArmDeveloperEcosystem/board-of-boards/blob/main/ip/neoverse.md)- 1 & 2 CPUs, each at 32-80 cores, up to 3.30 GHz


Use Cases:
- [AI/ML](/use-cases/ai-ml.md)
- [Server](/use-cases/servers.md)
- [Desktop](/use-cases/desktop.md)
- [IoT](/use-cases/iot.md)


## Specifications

Processor Subsystem
- 80 Arm® v8.2+ 64-bit CPU cores up to 3.30 GHz maximum
- 64 KB L1 I-cache, 64 KB L1 D-cache per core
- 1 MB L2 cache per core
- 32 MB System Level Cache (SLC)
- 2x full-width (128b) SIMD
- Coherent Mesh Interconnect (CMI):
  - Distributed snoop filtering

Memory
- 8x 72-bit DDR4-3200 channels
- SECDED ECC, Symbol-based ECC, and DDR4 RAS features
- Up to 16 DIMMs and 4 TB/socket

System Resources
- Full interrupt virtualization (GICv3)
- Full I/O virtualization (SMMUv3)
- Enterprise server-class RAS

Connectivity
- 128 lanes of PCIe Gen4
  - 8 x8 PCIe + 4 x16 PCIe/CCIX with Extended Speed Mode (ESM) support for data transfers at 20/25 GT/s
  - 48 controllers to support up to 32 x2 links
- 192 PCIe lanes in 2P configuration
- Coherent multi-socket support
- 4 x16 CCIX lanes

Technology and Functionality
- Armv8.2+, SBSA Level 4
- Advanced Power Management
  - Dynamic estimation, Voltage droop mitigation

Performance and Power
- Est. SPECrate® 2017_int_base (SKU: AC-108025002): 301 at

Usage Power: 187 W
- Max TDP: 250 W

Process Technology
- TSMC 7 nm FinFET
