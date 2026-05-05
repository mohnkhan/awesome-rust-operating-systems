

# 📘 Operating Systems Written in Rust  
*A Comprehensive, Continuously‑Updated Catalog (Including MyOS2026)*

Rust has become one of the most influential systems‑programming languages of the modern era. Its guarantees around memory safety, fearless concurrency, and zero‑cost abstractions have inspired a new generation of operating systems — from research kernels to production‑grade systems.

This repository maintains a **complete, authoritative list of all known operating systems written in Rust**, including my project **MyOS2026**.

---

## 🧭 Purpose of This Repository

- Provide a **single, authoritative index** of Rust‑based operating systems  
- Track **architectures, kernel types, licenses, and activity status**  
- Help researchers, students, and systems engineers discover Rust OS projects  
- Support maintainers by giving visibility to their work  
- Serve as a reference for anyone building a new Rust OS  

If you know of a Rust OS not listed here, please open an issue or PR.

---

# 🧵 Complete List of Operating Systems Written in Rust

---

## 📑 OS Comparison Table

| **OS Name** | **Architecture** | **Pure Rust?** | **Active?** | **Kernel Type** | **Target Use** | **GUI?** | **Filesystem** | **Network Stack** | **License** |
|------------|------------------|----------------|-------------|------------------|----------------|-----------|------------------|--------------------|-------------|
| **Redox OS** | x86, x86_64, ARM64, RISC‑V | Yes | Yes | Microkernel | General purpose | Yes | RedoxFS / FAT32 | smoltcp | MIT |
| **Theseus OS** | x86_64, ARM | Yes | Yes | Safe-language OS | Research + General | Yes | Custom/FAT32 | smoltcp | MIT |
| **Tock OS** | Cortex‑M, RISC‑V, x86 | Yes | Yes | Embedded kernel | Microcontrollers | No | Custom | APL2/MIT | APL2/MIT |
| **intermezzOS** | x86_64 | No | No | Educational | Teaching OS dev | No | None | None | APL2/MIT |
| **ParvaOS** | x86_64 | Yes | Yes | Monolithic | General purpose | Yes | ParvaFS | ? | GPL‑3.0 |
| **RustOS** | i386 | ? | No | PoC | Educational | No | None | None | MIT |
| **rustboot** | i386 | ? | No | Bootloader/OS | Educational | No | None | None | MIT |
| **bkernel** | ARM | Yes | No | Embedded | Embedded devices | No | ? | smoltcp | GPL + exception |
| **SOS** | x86_64 | Yes | No | Microkernel | PoC | No | None | None | MIT |
| **reenix** | x86_64 | No | No | Monolithic | PoC | No | None | None | Unknown |
| **Quasar** | x86_64 | ? | No | ? | ? | No | None | None | ? |
| **Tifflin (rust_os)** | x86_64 | Almost | Yes | Monolithic | Research | Yes | ISO9660 | ? | BSD‑2 |
| **MOROS** | x86_64 | Yes | Yes | Monolithic | Minimal OS | No | MFS | smoltcp | MIT |
| **Felix OS** | x86_64 | Yes | Yes | Monolithic | General | No | FAT16 (RO) | None | MIT |
| **Aero** | x86_64 | ? | Yes | Monolithic | General | Yes | ? | ? | GPL |
| **Hermit / HermitCore** | x86_64, ARM64 | Yes | Yes | Unikernel | Cloud/HPC | No | virtiofs | smoltcp | Apache/BSD |
| **Asterinas** | ? | Yes | Yes | ? | ? | ? | ? | ? | ? |
| **Twilight OS** | ? | Yes | Yes | ? | ? | ? | ? | ? | ? |
| **Proka OS** | ? | Yes | Yes | ? | ? | ? | ? | ? | ? |
| **QuiltOS** | ? | ? | ? | ? | ? | ? | ? | ? | ? |
| **OpenFang OS** | ? | Yes | Yes | Agent OS | Autonomous agents | No | ? | ? | ? |
| **Kerla** | x86_64 | Yes | Yes | Linux‑compatible | Linux ABI | No | ? | ? | ? |
| **Maestro** | x86_64 | Yes | Yes | Linux‑compatible | General | No | ? | ? | ? |
| **Bottlerocket** | x86_64, ARM | Mostly Rust | Yes | Container OS | Cloud/Containers | No | ? | ? | Apache‑2.0 |
| **MyOS2026** | x86_64 | Yes | Yes | Monolithic | Educational + Research | Planned | Custom FS (WIP) | Planned | MIT |

---


# 🤝 Contributing

Contributions are welcome — whether you're adding a new OS, improving metadata, or submitting corrections.

Please open an issue or PR.

---

# 📜 License

This repository is licensed under the **MIT License**.

---
