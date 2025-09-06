# KokoroSystem EX + Llama2 Research Implementation

[![License: BSD-3-Clause](https://img.shields.io/badge/License-BSD%203--Clause-blue.svg)](https://opensource.org/licenses/BSD-3-Clause)
[![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![PyTorch](https://img.shields.io/badge/PyTorch-2.0+-orange.svg)](https://pytorch.org/)

## Abstract

This repository presents a research implementation integrating the **KokoroSystem EX v2.0** theoretical framework with **Llama2** for structured emotion processing in artificial intelligence. The system demonstrates a novel three-stage pipeline combining symbolic emotion modeling with neural language processing, enabling cognitively-grounded empathetic AI responses.

Unlike traditional prompt-based emotion handling, this implementation employs mathematical formalization of emotional states through the **4D Kokoro Resonance Vector (KRV)** and real-time safety monitoring via the **Primordial Motive Core (PMC)**.

## Architecture Overview

```
┌─────────────────┐    ┌──────────────────┐    ┌─────────────────┐
│  Llama2         │───▶│  KokoroSystem    │───▶│  Llama2         │
│  Emotion        │    │  Mathematical    │    │  Response       │
│  Extraction     │    │  Processing      │    │  Generation     │
└─────────────────┘    └──────────────────┘    └─────────────────┘
       │                         │                        │
       ▼                         ▼                        ▼
 Pattern-based              4D KRV Update            Empathy-enhanced
 Recognition              (ER,GR,SR,IHR)             Context Response
```

### Core Components

- **4D KRV System**: Emotional Resonance, Goal Resonance, Self-awareness, Inner Hollow Resistance
- **Emotion Structure Theory**: 4-axis emotion modeling (Integrity, Layer, Time, Vector)
- **PMC Safety Framework**: Real-time coherence monitoring and ethical boundary maintenance
- **Hybrid Processing**: Combines symbolic mathematical operations with neural language understanding

## Theoretical Foundation

This implementation is based on the **KokoroSystem EX v2.0** theoretical framework:

- **Main Repository**: [KokoroSystem](https://github.com/YukiHoshino0203/KokoroSystem)
- **Academic Paper**: [KokoroSystem EX v2.0 - Zenodo](https://zenodo.org/records/16734920)
- **License**: Theoretical framework under CC BY-NC-ND, implementation under BSD-3-Clause

## Live Implementations

### Interactive Notebooks
- **English Version**: [Kaggle Notebook (EN)](https://www.kaggle.com/code/yukihoshino0203/en-kokorosys-with-llama2)
- **Japanese Version**: [Kaggle Notebook (JP)](https://www.kaggle.com/code/yukihoshino0203/jp-kokorosys-with-llama2)

## Prerequisites

### Hardware Requirements
- **GPU**: T4 x2 or equivalent (minimum 12GB VRAM)
- **RAM**: 16GB+ recommended
- **Storage**: 15GB+ for model downloads

### Software Dependencies
```bash
torch>=2.0.0
transformers>=4.30.0
numpy>=1.21.0
python>=3.8
```

### Platform Setup
1. **Kaggle Environment** (Recommended)
   - GPU: T4 x2 acceleration
   - Internet access enabled
   - HuggingFace token in Secrets

2. **Local Environment** (Advanced)
   - CUDA 11.8+ compatible GPU
   - Sufficient VRAM allocation

## Quick Start

### 1. Kaggle Setup (Recommended)
```bash
# In Kaggle Notebook
1. Set Accelerator → GPU T4 x2
2. Add HF_TOKEN to Secrets
3. Run all cells sequentially
```

### 2. HuggingFace Token Configuration
```bash
# Kaggle: Settings → Secrets → Add Secret
Name: HF_TOKEN
Value: [Your HuggingFace Read Token]
```

### 3. Model Execution
```python
# Basic usage pattern
system = TripleStageKokoroSystem()
result = system.process("I'm feeling anxious about the future")
```

## Research Features

### Emotion Detection Enhancement
- **60+ English emotion patterns** with intensity-aware confidence scoring
- **Cultural adaptation** for English-speaking contexts vs. Japanese patterns
- **Ambiguity handling** through clarification question generation

### Mathematical Emotion Processing
- **Real-time KRV calculation** with momentum-based state transitions
- **TR Extended values** incorporating Connective Integrity metrics
- **Safety thresholds** with PMC status monitoring (COHERENT/AT_RISK/VIOLATED)

### Response Strategy Optimization
- **Temporal awareness**: Past-regret, Present-empathy, Future-hope orientations
- **Intensity scaling**: Neutral → Balanced → Deep_empathy based on TR Extended
- **Contextual adaptation**: Self-directed vs. Other-directed emotional vectors

## Validation Results

### Performance Metrics
- **Processing Time**: 10-15 seconds per interaction (cold start: 3-5 minutes)
- **Memory Usage**: 10-12GB GPU, 8GB RAM
- **Emotion Detection Accuracy**: Enhanced for strong emotion words (devastated, thrilled)
- **Safety Coherence**: Real-time PMC monitoring with automatic failsafes

### Comparison Analysis
```
Input: "I'm absolutely devastated"
├── Raw Llama: "Sorry to hear that. What happened?"
└── Kokoro-processed: "Oh no, I'm so sorry to hear that you're feeling 
    absolutely devastated! It can be really tough when things aren't 
    going as planned..."
```

## Research Applications

### Academic Use Cases
- **Cognitive Architecture Studies**: Hybrid symbolic-neural emotion processing
- **Cross-cultural Validation**: Emotion pattern effectiveness across languages
- **Longitudinal Analysis**: KRV state evolution over extended interactions
- **Safety Research**: PMC effectiveness in maintaining ethical boundaries

### Technical Extensions
- **Model Substitution**: Replace Llama2 with other LLMs (GPT, Claude, etc.)
- **Multimodal Integration**: Incorporate visual/audio emotion signals
- **Scalability Studies**: Performance analysis with larger models
- **Real-time Applications**: Therapeutic AI, educational systems, social robotics

## Limitations and Considerations

### Technical Constraints
- **Computational Requirements**: Significant GPU resources (12GB+ VRAM)
- **Language Specificity**: Optimized for English; Japanese version has limited patterns
- **Context Window**: 50-interaction conversation history limit
- **Model Dependencies**: Performance bounded by base Llama2 capabilities

### Research Considerations
- **Experimental Status**: Research prototype requiring validation
- **Cultural Adaptation**: Emotion patterns may need localization for other cultures
- **Theoretical Validation**: KokoroSystem EX framework requires empirical studies
- **Ethical Boundaries**: Not intended for clinical/therapeutic applications without validation

## Troubleshooting

### Common Issues
```bash
# GPU Memory Error
Solution: Confirm T4 x2 allocation, restart kernel

# HuggingFace Token Error  
Solution: Verify token in Kaggle Secrets with Read permissions

# Slow Processing (>30s)
Solution: Check GPU allocation, verify model download completion
```

## Contributing

### Research Collaboration
- **Issue Reports**: Use GitHub Issues for bugs and enhancement requests
- **Academic Partnerships**: Contact for research collaboration opportunities
- **Validation Studies**: Contributions to cross-cultural emotion validation welcome

### Development Guidelines
- Follow BSD-3-Clause license requirements
- Maintain attribution to original theoretical framework
- Document experimental modifications for reproducibility

## Citation

If you use this implementation in academic research:

```bibtex
@software{hoshino2025kokorosystem_llama2,
  title={KokoroSystem EX + Llama2 Research Implementation},
  author={Hoshino, Yuki},
  year={2025},
  url={https://github.com/YukiHoshino0203/KokoroSystem-Llama2-Research},
  note={Research implementation of KokoroSystem EX v2.0 with Llama2 integration}
}
```

For the theoretical framework:
```bibtex
@article{hoshino2025kokorosystem_ex,
  title={KokoroSystem EX v2.0: A Self-Executable Cognitive-Emotional Architecture},
  author={Hoshino, Yuki},
  year={2025},
  publisher={Zenodo},
  doi={10.5281/zenodo.16734920},
  url={https://zenodo.org/records/16734920}
}
```

## License & Attribution

### Implementation Code
This implementation is licensed under **BSD 3-Clause License** - see [LICENSE](LICENSE) for details.

### Theoretical Framework  
The underlying KokoroSystem EX theoretical framework is licensed under **CC BY-NC-ND** - see [main repository](https://github.com/YukiHoshino0203/KokoroSystem) for details.

### Third-Party Components
- **Llama2**: Meta AI (subject to their license terms)
- **PyTorch/Transformers**: Apache 2.0 License

## Acknowledgments

- Meta AI for Llama2 model architecture
- HuggingFace for model hosting and tools
- Kaggle for computational resources and platform
- Research community for theoretical foundation validation

---

**Disclaimer**: This is a research prototype intended for academic and experimental purposes. Results should be interpreted within the context of current language model limitations and the exploratory nature of the KokoroSystem EX theoretical framework. Not intended for clinical or production applications without extensive validation.

For questions about implementation details or research collaboration, please open a GitHub Issue or refer to the [main KokoroSystem repository](https://github.com/YukiHoshino0203/KokoroSystem).
