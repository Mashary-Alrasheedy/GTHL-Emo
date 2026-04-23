# GTHL-Emo

Official code repository for **GTHL-Emo: Adaptive Imbalance-Aware and Correlation-Aligned Training for Arabic Multi-Label Emotion Detection**.

## Overview
GTHL-Emo is an Arabic multi-label emotion detection framework that combines:
- transformer-based semantic encoding,
- adaptive hybrid loss weighting for class imbalance,
- correlation-aligned label dependency modeling, and
- graph-based structural learning.

The framework was evaluated on three Arabic benchmarks:
- SemEval-2018-Ec-Ar
- SemEval-2025 Track A (Arq)
- ExaAEC

## Repository Structure
- `SemEval-2018/`: code for the SemEval-2018-Ec-Ar experiments
- `SemEval-2025/`: code for the SemEval-2025-Arq experiments
- `ExaAEC/`: code for the ExaAEC experiments

## Dataset Access
This public repository does not include the raw benchmark datasets. Please obtain each dataset from its original source and place the files into the corresponding subfolders before running the code:

- `SemEval-2018/`: [SemEval-2018 Task 1: Affect in Tweets]([https://aclanthology.org/S18-1001/](https://huggingface.co/datasets/SemEvalWorkshop/sem_eval_2018_task_1))
- `SemEval-2025/`: [SemEval-2025 Task 11: Bridging the Gap in Text-Based Emotion Detection (official task page with dataset/download links)](https://github.com/emotion-analysis-project/SemEval2025-Task11)
- `ExaAEC/`: [ExaAEC: A New Multi-label Emotion Classification Corpus in Arabic Tweets](https://github.com/exaco/exaaec)

Please also acknowledge and cite the original organizers of these dataset sources.



## Citation
If you use this repository, please cite:

Alrasheedy, M. N., Tiun, S., & Fauzi, F. (2026). *GTHL-Emo: Adaptive Imbalance-Aware and Correlation-Aligned Training for Arabic Multi-Label Emotion Detection*. Electronics, 15(6), 1169. https://doi.org/10.3390/electronics15061169

### APA
Alrasheedy, M. N., Tiun, S., & Fauzi, F. (2026). GTHL-Emo: Adaptive Imbalance-Aware and Correlation-Aligned Training for Arabic Multi-Label Emotion Detection. *Electronics, 15*(6), 1169. https://doi.org/10.3390/electronics15061169

### BibTeX
```bibtex
@article{alrasheedy2026gthl,
  title={GTHL-Emo: Adaptive Imbalance-Aware and Correlation-Aligned Training for Arabic Multi-Label Emotion Detection},
  author={Alrasheedy, Mashary N and Tiun, Sabrina and Fauzi, Fariza},
  journal={Electronics},
  volume={15},
  number={6},
  pages={1169},
  year={2026},
  publisher={MDPI},
  doi={10.3390/electronics15061169}
}
```
