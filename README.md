# Daniil Loban

Software Engineer focused on **Linux Systems Programming**, **C++**, and **Network Infrastructure**.

I specialize in L2/L3 packet processing, user space network services, and Linux-based infrastructure debugging. Passionate about modern C++ (17/20), network protocols, and system internals.

---

### Technical Profile

- **Languages:** C++17, C, Bash, Python (automation), SQL.
- **Networking:** TCP/IP, UDP, IPsec, RAW Sockets, L2/L3 framing, Boost.Asio/Beast.
- **System & OS:** Linux (Debian, Ubuntu), POSIX API, Multithreading, Memory Management, Linux Kernel Module basics.
- **Tools & Infra:** CMake, Git, Docker, GitLab CI/CD, GDB, Valgrind, Clang-Tidy, CTest, VMware.

---

### Highlighted Projects

#### [Linux Virtual Network Interface (`virt_iface`)](https://github.com/katchkatcher/virt_iface)
*Linux Kernel Module implementing a virtual Ethernet interface with an active packet reflector.*
- Intercepts outgoing ARP and ICMP Echo requests and reflects them back into the kernel RX path using `netif_rx()`.
- Implemented real-time IP configuration via ProcFS API (`/proc/virt_iface`).
- Adheres to Linux kernel coding standards (`checkpatch.pl` compliant) and includes automated test scripts.

#### [Network Packet Sniffer](https://github.com/katchkatcher/Sniffer)
*Lightweight L2/L3 packet analyzer written in C++17 using RAW/AF_PACKET sockets.*
- Manual parsing for Ethernet (L2), IPv4/IPv6, TCP, UDP, ICMP(v6), ARP, and 802.1Q VLAN tags.
- CLI interface with runtime filtering (IP, Port, Protocol, Interface) and terminal color-coded hexdump.
- Integrated `Clang-Tidy` static analysis, `AddressSanitizer` support, and unit tests via `CTest`.

#### [Asynchronous WebSocket Server](https://github.com/katchkatcher/WebSocketMessenger)
*Multi-threaded WebSocket chat server built with Modern C++ and Boost.Beast / Boost.Asio.*
- Implemented room-based message routing, UTF-8 validation (`utf8cpp`), and structured log rotation via `spdlog`.
- Designed for high-concurrency connection handling with graceful shutdown support (`SIGINT`/`SIGTERM`).

#### [Custom `UniquePtr` Implementation](https://github.com/katchkatcher/UniquePtr-implementation)
*Educational implementation of a modern C++ smart pointer.*
- Demonstrates RAII, strict move semantics, deleted copy operations, and custom deleter support.

---

### Contact & Links
- **Telegram:** [@daniilcpp](https://t.me/daniilcpp)
- **Email:** daniilloban333@gmail.com
- **Location:** Minsk, Belarus
