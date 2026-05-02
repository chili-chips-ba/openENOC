# Scalable Ethernet-based Network-on-Chip

<p align="center">
  <img width="30%" src="0.doc/artwork/openENOC.hex.png">
</p>

**openENOC** is an open-source hardware and software initiative that develops a modular and scalable Ethernet-based Network-on-Chip (NoC) architecture for FPGA SoCs and advanced MPSoC designs. By adopting standard Ethernet Layer 2 as the native on-chip transport protocol, rather than relying on traditional mesh or proprietary interconnects, openENOC enables seamless integration with existing Ethernet infrastructure and establishes a unified communication and programming model across both on-chip and off-chip systems.

This approach allows processors, accelerators, and peripherals to be connected through a flexible, packet-switched network based on L2 switching, effectively bridging the gap between on-chip and off-chip networking while lowering the complexity of building large-scale systems.

The concept originated from practical challenges encountered during the development of the NLnet-funded WireGuard FPGA project, where scaling cryptographic workloads such as Curve25519 and ChaCha20-Poly1305 exposed limitations of conventional interconnect architectures. In response, openENOC introduces an Ethernet-based interconnect designed to support efficient, network-oriented scaling of cryptographic processing, edge computing, and AI acceleration workloads.

openENOC aims to deliver a complete, freely licensed full-stack solution combining reusable hardware and software gateware developed in SystemVerilog and C/C++. Built in alignment with open hardware and open source software principles, the project will provide RTL components, integration APIs, verification infrastructure, and reference designs, forming a cohesive and production ready foundation.

Its primary goal is to unlock the potential of networked reconfigurable computing by making it accessible, portable, and adaptable across a wide range of use cases. The architecture is designed with modularity at its core, enabling gradual adoption, straightforward customization, and seamless extension. This makes it suitable not only for demanding workloads such as cryptography and edge computing, where traditional interconnects struggle to scale, but also for a broad audience including academia, industry, hobbyists, and the maker community.

All results will be released openly to encourage reuse, strengthen the open hardware ecosystem, and empower developers and organizations to build interoperable, future proof, and community driven MPSoC solutions.

👉 For additional detail: [https://github.com/eniokaljic/openENOC](https://github.com/eniokaljic/openENOC)

----
#### End-of-Document
