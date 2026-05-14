# 🛡️ BAKOME FISCO Guard – FISCO BCOS 智能合约安全分析器

**用 Rust 编写的静态安全分析工具，专为 FISCO BCOS 联盟链设计。检测 Solidity 智能合约中的重入、整数溢出、访问控制缺失、时间戳依赖等常见漏洞，生成 HTML / JSON 报告。**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Rust](https://img.shields.io/badge/Rust-1.80%2B-orange)](https://www.rust-lang.org/)

---

## 🚀 快速开始

### 前置要求
- Rust 1.80+ ([安装指南](https://rustup.rs/))
- 一个 FISCO BCOS 智能合约的 Solidity 源文件

### 安装与运行

```bash
git clone https://github.com/BAKOME-Hub/BAKOME_FISCO_Guard.git
cd BAKOME_FISCO_Guard
cargo build --release
./target/release/fisco_guard -i 合约.sol -o 报告.html./target/release/fisco_guard -i 合约.sol --json 结果.json
