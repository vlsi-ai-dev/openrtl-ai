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
openrtl-ai/
├── dataset/          # Data collection scripts
├── training/         # Fine-tuning configs
├── evaluation/       # Benchmark scripts
├── examples/         # Sample RTL + UVM outputs
└── docs/             # Technical documentation

## 📅 Timeline
- **Month 1:** Dataset collection and curation
- **Month 2:** 7B baseline fine-tuning
- **Month 3:** GRPO alignment
- **Month 4-5:** 30B scale-up
- **Month 6:** Public release + arXiv paper

## 🤝 Contributing
Contributions welcome — especially:
- RTL/UVM dataset contributions
- Domain expert validation
- Evaluation benchmark design

## 📜 License
Apache 2.0 — fully open source

## 🙏 Acknowledgements
Built using the Hugging Face ecosystem and ml-intern.
