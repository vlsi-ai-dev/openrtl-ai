# OpenRTL-AI 🔧
> Open-source LLM for Verilog/SystemVerilog/UVM/SystemC 
> RTL design and verification automation

[![HuggingFace](https://img.shields.io/badge/HuggingFace-Model-FFD21E)](https://huggingface.co/openrtl-ai)
[![License](https://img.shields.io/badge/License-Apache%202.0-blue)](LICENSE)
[![Status](https://img.shields.io/badge/Status-Active%20Development-green)]()

## 🎯 Goal
Fine-tune a 30B parameter code LLM to assist chip design 
engineers in:
- Writing production RTL for standard protocols
- Building complete UVM verification environments
- SystemC TLM modeling
- Lint-clean, synthesis-ready code generation

## 🗺️ Supported Protocols
| Protocol | RTL | UVM TB | Status |
|---|---|---|---|
| AXI4 | ✅ | ✅ | Planned |
| APB | ✅ | ✅ | Planned |
| PCIe Gen4 | ✅ | ✅ | Planned |
| USB 3.0 | ✅ | ✅ | Planned |
| Ethernet | ✅ | ✅ | Planned |

## 🧱 Model Stack
- **Base Model:** Qwen2.5-Coder-32B
- **Training:** SFT → GRPO
- **Framework:** HuggingFace + ml-intern
- **Evaluation:** VerilogEval + OpenRTL-Eval

## 📁 Repository Structure
