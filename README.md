

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

# 🦀 Rust‑Based Operating Systems  
A complete, categorized, badge‑enhanced index of every known operating system written in Rust.

---

# 📚 Categories
- **General‑Purpose OS**
- **Research / Academic OS**
- **Embedded / RTOS**
- **Unikernels**
- **Agent OS**
- **Experimental / Hobby OS**
- **Bootloaders / Stage‑0**

---

# 🟦 General‑Purpose Operating Systems

| OS | Badges | Architecture | Kernel | FS | Networking | License | Status |
|----|--------|--------------|--------|----|------------|----------|--------|
| **Redox OS** | ![Arch](https://img.shields.io/badge/arch-x86__64-blue) ![Kernel](https://img.shields.io/badge/microkernel-purple) ![License](https://img.shields.io/badge/license-MIT-green) | x86, x86_64, ARM64, RISC‑V | Microkernel | RedoxFS | smoltcp | MIT | Active |
| **ParvaOS** | ![Arch](https://img.shields.io/badge/arch-x86__64-blue) ![Kernel](https://img.shields.io/badge/monolithic-orange) | x86_64 | Monolithic | ParvaFS | ? | GPL‑3.0 | Active |
| **Aero** | ![Arch](https://img.shields.io/badge/arch-x86__64-blue) | x86_64 | Monolithic | ? | ? | GPL | Active |
| **Felix OS** | ![Arch](https://img.shields.io/badge/arch-x86__64-blue) | x86_64 | Monolithic | FAT16 (RO) | None | MIT | Active |
| **MOROS** | ![Arch](https://img.shields.io/badge/arch-x86__64-blue) | x86_64 | Monolithic | MFS | smoltcp | MIT | Active |
| **MyOS2026** | ![Arch](https://img.shields.io/badge/arch-x86__64-blue) ![Kernel](https://img.shields.io/badge/monolithic-orange) ![License](https://img.shields.io/badge/license-MIT-green) | x86_64 | Monolithic | Custom FS (WIP) | smoltcp | MIT | Active |

---

# 🟩 Research / Academic Operating Systems

| OS | Badges | Architecture | Kernel | FS | Networking | License | Status |
|----|--------|--------------|--------|----|------------|----------|--------|
| **Theseus OS** | ![Arch](https://img.shields.io/badge/arch-x86__64-blue) ![Kernel](https://img.shields.io/badge/safe--language-9cf) | x86_64, ARM | Safe‑Language OS | Custom | smoltcp | MIT | Active |
| **Tifflin (rust_os)** | ![Arch](https://img.shields.io/badge/arch-x86__64-blue) | x86_64 | Monolithic | ISO9660 | ? | BSD‑2 | Active |
| **rCore OS** | ![Arch](https://img.shields.io/badge/arch-RISC--V-blue) | RISC‑V | Teaching OS | Custom | smoltcp | MIT | Active |
| **zCore** | ![Arch](https://img.shields.io/badge/arch-x86__64-blue) | x86_64, RISC‑V | Zircon‑compatible | Custom | smoltcp | MIT | Active |
| **Rux (Tsinghua University)** | ![Arch](https://img.shields.io/badge/arch-RISC--V-blue) | RISC‑V | Teaching OS | Custom | ? | MIT | Active |
| **intermezzOS** | ![Arch](https://img.shields.io/badge/arch-x86__64-blue) | x86_64 | Educational | None | None | APL2/MIT | Inactive |

---

# 🟧 Embedded / RTOS

| OS | Badges | Architecture | Kernel | FS | Networking | License | Status |
|----|--------|--------------|--------|----|------------|----------|--------|
| **Tock OS** | ![Arch](https://img.shields.io/badge/arch-Cortex--M-blue) | Cortex‑M, RISC‑V, x86 | Embedded kernel | Custom | APL2/MIT | APL2/MIT | Active |
| **Hubris OS** | ![Arch](https://img.shields.io/badge/arch-Cortex--M-blue) | ARM Cortex‑M | Microkernel | Custom | ? | Apache‑2.0 | Active |
| **Drone OS** | ![Arch](https://img.shields.io/badge/arch-Cortex--M-blue) | ARM Cortex‑M | RTOS | Custom | ? | MIT | Active |
| **RTIC** | ![Arch](https://img.shields.io/badge/arch-Cortex--M-blue) | ARM | RTOS Framework | N/A | N/A | MIT | Active |
| **bkernel** | ![Arch](https://img.shields.io/badge/arch-ARM-blue) | ARM | Embedded | ? | smoltcp | GPL + Exception | Inactive |

---

# 🟥 Unikernels

| OS | Badges | Architecture | Kernel | FS | Networking | License | Status |
|----|--------|--------------|--------|----|------------|----------|--------|
| **Hermit / HermitCore** | ![Arch](https://img.shields.io/badge/arch-x86__64-blue) | x86_64, ARM64 | Unikernel | virtiofs | smoltcp | Apache/BSD | Active |
| **Nebulet** | ![Arch](https://img.shields.io/badge/arch-WASM-blue) | WebAssembly VM | Unikernel | None | None | MIT | Archived |
| **RuxOS (unikernel)** | ![Arch](https://img.shields.io/badge/arch-x86__64-blue) | x86_64 | Unikernel | ? | ? | MIT | Early Stage |

---

# 🟪 Agent OS

| OS | Badges | Architecture | Kernel | FS | Networking | License | Status |
|----|--------|--------------|--------|----|------------|----------|--------|
| **OpenFang OS** | ![Arch](https://img.shields.io/badge/arch-unknown-lightgrey) | ? | Agent OS | ? | ? | ? | Active |

---

# 🟨 Experimental / Hobby OS

| OS | Badges | Architecture | Kernel | FS | Networking | License | Status |
|----|--------|--------------|--------|----|------------|----------|--------|
| **RustOS** | ![Arch](https://img.shields.io/badge/arch-i386-blue) | i386 | PoC | None | None | MIT | Inactive |
| **RustOS64** | ![Arch](https://img.shields.io/badge/arch-x86__64-blue) | x86_64 | Monolithic | ? | ? | MIT | Active |
| **Ruxpin OS** | ![Arch](https://img.shields.io/badge/arch-x86__64-blue) | x86_64 | Monolithic | ? | ? | MIT | Semi‑active |
| **Rux (Unix‑like)** | ![Arch](https://img.shields.io/badge/arch-x86__64-blue) | x86_64 | Unix‑like | ? | ? | MIT | Early Stage |
| **Ruxpin Kernel** | ![Arch](https://img.shields.io/badge/arch-x86__64-blue) | x86_64 | Monolithic | ? | ? | MIT | Early Stage |
| **SOS** | ![Arch](https://img.shields.io/badge/arch-x86__64-blue) | x86_64 | Microkernel | None | None | MIT | Inactive |
| **Quasar** | ![Arch](https://img.shields.io/badge/arch-x86__64-blue) | x86_64 | ? | None | None | ? | Inactive |
| **Asterinas** | ![Arch](https://img.shields.io/badge/arch-unknown-lightgrey) | ? | ? | ? | ? | ? | Active |
| **Twilight OS** | ![Arch](https://img.shields.io/badge/arch-unknown-lightgrey) | ? | ? | ? | ? | ? | Active |
| **Proka OS** | ![Arch](https://img.shields.io/badge/arch-unknown-lightgrey) | ? | ? | ? | ? | ? | Active |
| **QuiltOS** | ![Arch](https://img.shields.io/badge/arch-unknown-lightgrey) | ? | ? | ? | ? | ? | Unknown |

---

# 🟫 Bootloaders / Stage‑0 (Optional Category)

| OS | Badges | Architecture | Kernel | FS | Networking | License | Status |
|----|--------|--------------|--------|----|------------|----------|--------|
| **rustboot** | ![Arch](https://img.shields.io/badge/arch-i386-blue) | i386 | Bootloader | None | None | MIT | Inactive |
| **rboot** | ![Arch](https://img.shields.io/badge/arch-x86__64-blue) | x86_64 | Bootloader | None | None | MIT | Active |
| **rust-barebones-kernel** | ![Arch](https://img.shields.io/badge/arch-x86__64-blue) | x86_64 | Template Kernel | None | None | MIT | Active |

---

# 🏁 End of Table



# 🤝 Contributing

Contributions are welcome — whether you're adding a new OS, improving metadata, or submitting corrections.

Please open an issue or PR.

---

# 📜 License

This repository is licensed under the **MIT License**.

---
