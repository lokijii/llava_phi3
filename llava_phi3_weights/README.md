---
license: mit
---

[![CODE](https://img.shields.io/badge/GitHub-Repository-<COLOR>)](https://github.com/mbzuai-oryx/LLaVA-pp)

# Phi-3-V: Extending the Visual Capabilities of LLaVA with Phi-3

## Repository Overview

This repository features LLaVA v1.5 trained with the Phi-3-mini-3.8B LLM. This integration aims to leverage the strengths of both models to offer advanced vision-language understanding.

## Training Strategy
- Only Vision-to-Language projector is trained. The rest of the model is frozen.
- **Note:** The repository contains only the projector weights.

## Key Components

- **Base Large Language Model (LLM):** [Phi-3-mini-4k-instruct](https://huggingface.co/microsoft/Phi-3-mini-4k-instruct)
- **Base Large Multimodal Model (LMM):** [LLaVA-v1.5](https://github.com/haotian-liu/LLaVA)

## Training Data

- **Pretraining Dataset:** [LCS-558K](https://huggingface.co/datasets/liuhaotian/LLaVA-Pretrain)

## Download It As

```
git lfs install
git clone https://huggingface.co/MBZUAI/LLaVA-Phi-3-mini-4k-instruct-pretrain
```

---

## License

This project is available under the MIT License.

## Contributions

Contributions are welcome! Please 🌟 our repository [LLaVA++](https://github.com/mbzuai-oryx/LLaVA-pp) if you find this model useful.

---
