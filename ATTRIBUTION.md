# Attribution & Acknowledgments

## Foundation Project

### llama.cpp
**Efficient LLM Inference in C/C++**

- **Repository:** https://github.com/ggml-org/llama.cpp
- **License:** MIT
- **Copyright:** 2023-2026 The ggml authors
- **Maintainers:** ggml-org community

We gratefully acknowledge the llama.cpp team for creating an outstanding foundation for this research. Their clean, efficient C/C++ implementation enabled our quantization research and optimization work.

**Key contributions to our work:**
- Core LLM inference engine
- GGML tensor library
- Quantization support (Q8, Q4, etc.)
- Multi-backend support (CPU, CUDA, Metal, etc.)
- Comprehensive model support

---

## Core Dependencies

### GGML (GGML Tensor Library)
- **Repository:** https://github.com/ggml-org/ggml
- **License:** MIT
- **Purpose:** Tensor operations, quantization kernels
- **Used For:** Vector operation optimization research

### OpenSSL
- **License:** Apache 2.0 / OpenSSL License
- **Purpose:** SSL/TLS support
- **Included:** Via system dependencies

---

## Research Contributors

### Aviasole AI Innovation Lab
- **Organization:** Aviasole
- **Research Team:** AI/ML Research Division
- **Contributions:**
  - Quantization benchmarking framework
  - Vector operation optimization
  - Enterprise deployment analysis
  - Research methodology and documentation

---

## Upstream Projects & Inspiration

### Academic References
The research builds upon decades of work in:
- **Quantization techniques** - From academic ML research
- **CPU optimization** - From systems research
- **Performance analysis** - From computer architecture research

Key papers (not endorsed, but informative):
- Quantization-Aware Training techniques
- SIMD optimization strategies
- Cache-efficient algorithms

---

## Community & Acknowledgments

### Open Source Community
- llama.cpp maintainers and contributors
- GGML library contributors
- Hugging Face community
- Wider open-source AI/ML ecosystem

### Tools & Infrastructure
- **CMake:** Build system
- **GCC/Clang:** Compilers
- **Linux:** Operating system
- **Git:** Version control

---

## License Compliance Statement

### Repository License
This research project is released under the **MIT License** to respect the terms of the upstream llama.cpp project.

### License Hierarchy
```
Repository Root (MIT)
├── Llama.CPP/ (MIT - inherited from llama.cpp)
├── pocs/ (MIT - our research code)
├── benchmarks/ (MIT - our benchmark tools)
└── docs/ (MIT - our documentation)
```

### Using This Work

**You are free to:**
- ✅ Use for commercial purposes
- ✅ Modify the source code
- ✅ Distribute copies
- ✅ Use as a foundation for your own projects

**You must:**
- 📋 Include this license
- 📋 Provide attribution to original authors
- 📋 State significant changes

**You cannot:**
- ❌ Remove license information
- ❌ Hold us liable for issues
- ❌ Claim you wrote the original llama.cpp

See [LICENSE](LICENSE) for complete legal terms.

---

## Attribution When Using This Work

If you use this research, code, or findings in your project, please provide attribution:

### In Documentation
```markdown
This research builds upon Aviasole's Llama.cpp Quantization & Vector Operation
Optimization research (https://github.com/aviasole/aviasole-ai-exploration),
which itself builds on the llama.cpp project
(https://github.com/ggml-org/llama.cpp).
```

### In Academic Citations
```bibtex
@research{aviasole2026quantization,
  title={Quantization and Vector Operation Optimization for CPU-Based LLM Inference},
  author={Aviasole AI Research Lab},
  year={2026},
  organization={Aviasole},
  url={https://github.com/aviasole/aviasole-ai-exploration}
}

@software{llamacpp,
  title={llama.cpp: LLM inference in C/C++},
  author={{GGML Organization}},
  year={2023},
  url={https://github.com/ggml-org/llama.cpp}
}
```

### In Code Comments
```cpp
// Based on Aviasole's Llama.cpp Quantization Research
// https://github.com/aviasole/aviasole-ai-exploration
// Which builds upon llama.cpp: https://github.com/ggml-org/llama.cpp
// Licensed under MIT
```

---

## Data & Benchmark Attribution

### Benchmark Datasets
- **WikiText:** Used under standard academic license
- **LAMBADA:** Used for language understanding evaluation
- **Standard LLM Benchmarks:** Following research community standards

### Model Attribution
- **LLama 2 7B:** Meta Llama community license
- **Mistral 7B:** Mistral AI Apache 2.0 license
- **Qwen 7B:** Alibaba Qwen license

All models used comply with their respective licenses for research purposes.

---

## Special Thanks

### Individuals
- llama.cpp maintainers for responsive issue handling
- Research community for open-source quantization work
- Enterprise customers who provided deployment insights

### Organizations
- ggml-org for the excellent GGML library
- Meta AI for Llama models and research
- Hugging Face for model distribution infrastructure

---

## Modifications & Derivative Works

### What We Modified
- Added quantization benchmarking code in `pocs/`
- Created vector operation optimization implementations
- Developed performance analysis tools
- Wrote research methodology and documentation

### What Remains Unchanged
- Core llama.cpp source code (in `Llama.CPP/`)
- Official llama.cpp documentation
- Model format (GGUF)
- API compatibility

### How to Find Our Changes
```
aviasole-ai-exploration/
├── Llama.CPP/ (unchanged baseline)
├── pocs/ ← Our research code
├── benchmarks/ ← Our tools
├── projects/...-research/
│   ├── FINDINGS.md ← Our analysis
│   ├── setup-guide.md ← Our guide
│   └── docs/ ← Our documentation
```

---

## Backward Compatibility

This project maintains compatibility with:
- ✅ llama.cpp API (no breaking changes)
- ✅ GGUF model format (standard)
- ✅ Existing integrations (drop-in replacement)
- ✅ Community tools (full compatibility)

You can use our optimizations as a drop-in replacement for standard llama.cpp.

---

## Contributing & Collaborations

### If You Contribute to This Project
- Acknowledge the llama.cpp project
- Follow the MIT license terms
- Maintain attribution chain
- Document your additions

### If You Fork This Project
- Keep the license and attribution
- Add attribution for your modifications
- Update ATTRIBUTION.md with your contributions
- Submit improvements back if beneficial to community

### If You Use This in Products
- Include license in distribution
- Provide attribution in documentation
- Consider contributing improvements back
- Contact info@aviasole.com for partnership opportunities

---

## Contact & Inquiries

**Academic Questions:**
- info@aviasole.com

**Licensing Questions:**
- See [LICENSE](LICENSE) file
- Contact: info@aviasole.com

**Attribution Issues:**
- If we've missed attributing your work, please let us know
- Email: info@aviasole.com

---

## Version History

| Date | Version | Changes |
|------|---------|---------|
| Mar 30, 2026 | 1.0 | Initial release with comprehensive attribution |

---

**Thank you to the open-source community for making this research possible.** ❤️

This work stands on the shoulders of giants—the llama.cpp team, GGML contributors, and the wider AI/ML research community.

---

*Last Updated: March 30, 2026*
*MIT Licensed*
