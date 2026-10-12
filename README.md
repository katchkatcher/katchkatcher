# Daniil Loban

**C/C++ Network & Systems Software Engineer** focused on Linux systems programming, network protocols, and cryptographic information protection software.

---

### Professional Summary
C/C++ Software Engineer with commercial experience at **S-Terra Bel**, developing Linux-based IPsec/VPN solutions and cryptographic protection software. Experienced in license verification mechanisms, IKEv1 Quick Mode handling, GRE-over-IPsec tunnel management, low-level networking protocols, and kernel-space/user-space interaction.

---

### Technical Profile
- **Languages:** C, C++17, Python, Bash, SQL
- **C/C++ Core:** STL, RAII, Memory Management, Object-Oriented Programming
- **Networking:** TCP/IP, UDP, Ethernet, ARP, ICMP, IPsec, IKEv1, GRE-over-IPsec, Raw Sockets, AF_PACKET
- **Linux Systems Programming:** Linux API, Kernel Modules, ProcFS, `sk_buff`, User/Kernel Space interaction, GDB, DPDK
- **Tools & Frameworks:** CMake, Make, Git, VMware, Clang, Clang-Tidy, CTest, Boost.Asio, Buildroot, Device Tree (DTS)
- **Spoken Languages:** Russian (Native), English (A2 – Technical Reading)

---

### Highlighted Projects

#### [Linux Virtual Network Interface (`virt_iface`)](https://github.com/katchkatcher/virt_iface)
*Linux Kernel Module providing a virtual Ethernet interface with ICMP ping response.*
- Implemented ARP and ICMP echo request/reply processing, packet header transformation, and injection into the Linux network stack.
- Added real-time IP interface configuration via ProcFS.
- Created automated test scripts covering module building, loading, configuration, and ping validation.
- **Technologies:** C, Linux Kernel APIs, Network Devices, `sk_buff`, ProcFS, ARP, ICMP, Make

#### [Network Packet Sniffer (`Sniffer`)](https://github.com/katchkatcher/Sniffer)
*Linux packet analyzer implemented using AF_PACKET / RAW sockets.*
- Parsed Ethernet, IPv4, IPv6, TCP, UDP, ICMP, ARP, and 802.1Q VLAN frames.
- Implemented runtime filtering by protocol, IP address, port, and network interface with hex-dump payload output.
- Included packet length validation, truncated packet handling, unit tests, and AddressSanitizer integration.
- **Technologies:** C++17, Linux Sockets, AF_PACKET, CMake, CTest, Clang-Tidy, AddressSanitizer

#### Stanford CS144 Networking Project *(Private Repository)*
*Implementation of custom TCP protocol stack components.*
- Developed `ByteStream`, `Reassembler`, `TCP Sender`, and `TCP Receiver` components.
- Applied sliding window, stream reassembly, and flow control concepts.
- **Technologies:** C++, TCP, Flow Control, Algorithms & Data Structures

#### [Embedded Linux / Buildroot (`buildroot-external-inmys`)](https://github.com/katchkatcher/buildroot-external-inmys)
*Customized embedded Linux system for Rockchip hardware.*
- Configured Buildroot and updated Device Tree (DTS) to enable an additional CAN interface.
- Built and flashed custom firmware images.
- **Technologies:** Embedded Linux, Buildroot, Device Tree (DTS), CAN, Rockchip

---

### Contact & Links
- **Telegram:** [@daniilcpp](https://t.me/daniilcpp)
- **Email:** daniilloban333@gmail.com
- **Location:** Minsk, Belarus
